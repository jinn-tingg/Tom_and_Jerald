Tom and Jerald
A 2D jetpack side-scroller written in C++ on DigiPen's Alpha Engine. You steer with a jetpack, manage your fuel, dodge obstacles and outrun a chasing cat, and spend the cheese you collect on upgrades.

Team project for GAM 150 at Singapore Institute of Technology / DigiPen Institute of Technology Singapore, Jan to Apr 2026. Team of 5.

Features
Endless mode: obstacles, spikes and walls get harder the longer you survive.
Maze mode: a new maze is generated each run with depth-first search.
Level editor: place tiles, save the level to a file, and play it as a custom level.
Shop and upgrades: spend cheese on upgrades, which change your size and fuel. Progress is saved to file.
Leaderboard: the top 10 scores are saved between sessions.
Tutorial: teaches jetpack movement, fuel and avoiding obstacles.

Controls
Action	              Keys
Jetpack thrust	      W, Space or Up
Move left / right	    A / D or Left / Right
Pause	                P
Back / menu	          Esc
Menus	                Mouse

Build and run
You need Windows and Visual Studio 2022 with the Desktop development with C++ workload (toolset v143, C++17).
1. Clone the repo.
2. Open Tom_and_Jerald.sln.
3. Pick Debug | x64 or Release | x64 and press F5.
The Alpha Engine headers and libraries are in Extern/AlphaEngine. A post-build step copies Assets/ next to the executable, so the game finds its textures, sounds and config files.

Project layout
Tom_and_Jerald/      game source: one .cpp/.hpp pair per game state or system
Assets/              textures, fonts, audio and config files
Assets/data/         levels, high scores, upgrades and other save data
Extern/AlphaEngine/  DigiPen Alpha Engine (headers and libraries)

Team
Tan Choon Ming, Dan Ng Cher Kai, Peng Rong Jun Jerald, Loh Kai Xin, Ong Jin Ting

Original repository: choonzs/Tom_and_Jerald

Copyright © 2026 DigiPen. All rights reserved.
