Skip to content
Navigation Menu
ice-HoTF
DZL-Beta-SteamDeck

Type / to search
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
DZL-Beta-SteamDeck
/
README.md
in
main

Edit

Preview
Indent mode

Spaces
Indent size

2
Line wrap mode

Soft wrap
Editing README.md file contents
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
# DZL - A Simple DayZ Mod Launcher for SteamDeck
\
 **Beta released 17/02/2025**
\
\
By: ice_hotf
\
\
Tested with SteamDeck (Arch)
\
\
\
**FLATPAK STEAM NOT SUPPORTED!**
This script only works with the official steam package: https://wiki.debian.org/Steam
\
\
\
This script will wait for user input and automatically identify missing mods, download them and launch DayZ with the mods. 
This script will also allow you to delete mods, save shortcut script or an alias in the terminal interface.
Just follow the instructions in the terminal window
\
\
This script supports modded servers and vanilla servers.
\
\
\
\
**How To:**
\
\
\
1: Extract 'DZL_Beta_main-SteamDeck.zip' and copy the 'DZL' Folder to your '/home/$USER' Directory.
\
\
2: Take ownership of the '/home/$USER/DZL' folder in the Terminal:
\
\
   sudo chmod +x /home/$USER/DZL/./*
\
\
3: Run DZL from Terminal:
\
\
   bash /home/$USER/DZL/DZL.sh 
\
\
4: Run DZL from Application Shortcut: 
\
\
4-1: Copy 'DZL.desktop' to /home/$USER/.local/share/applications/ in the Terminal:
\
\
   cp /home/$USER/DZL/DZL.desktop /home/$USER/.local/share/applications/DZL.desktop
\
\
4-2: Copy the .png-icon to the '/usr/share/icons' folder in the Terminal:
\
\
   sudo cp /home/$USER/DZL-Beta-main/DZL/dzl.png /usr/share/icons/
\
\
4-3: Open the Application Shortcut from the Application Launcher/StartMenu/Dashboard.
\
\
\
\
Join Server:
\
\
![join_server_1](https://github.com/user-attachments/assets/6ec5261a-aed7-4f57-ad87-721ffee2bd58)
\
\
Add Favorite:
\
\
![add_favorite](https://github.com/user-attachments/assets/bda435ef-ce73-4eac-9d0e-c721d347d628)
\
\
Join Favorite:
\
\
![join_favorite](https://github.com/user-attachments/assets/419abb14-c5ad-4e40-92d9-0454825296f9)
\
\
Remove Favorite:
\
\
![remove_favorite](https://github.com/user-attachments/assets/30ff3c24-fd89-4919-a65e-d58349de3783)
Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
Editing DZL-Beta-SteamDeck/README.md at main · ice-HoTF/DZL-Beta-SteamDeck 
