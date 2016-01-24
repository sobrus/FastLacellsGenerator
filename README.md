# FastLacellsGenerator
Simple script to quickly generate lacells.db cell database for LocalGSMBackend.

Using very fast internet connection, it can generate Poland (~1.000.000 cells) database in just under 2 minutes on dual core x64 Atom D510 CPU.
On old Core2 3,2Ghz with SSD it can genrate Poland database in 26 seconds and full database in about 7 minutes.
Should be even twice as fast on modern processors.

Uses both Mozilla Location Service and OpenCellID databases as source

Based on lacells-creator by wvengen and n76
https://github.com/n76/lacells-creator

Licensed under GPLv3 or later
(C)2016 Sebastian Obrusiewicz

Usage: all parameters are defined as script variables and described inside
