
Sizes of directories after running the corresponding command.  

KB	DIR	INIT	
COMMAND	BUILT	TOTAL	
KB	DIR	BUILT	

git clone https://github.com/sdrausty/buildAPKs
4220    buildAPKs
672     buildAPKs/sources/Apps
./buildAPKs/buildMyFirstAPKs.sh	2
1012    buildAPKs/sources/Apps
4568    buildAPKs
cd buildAPKs
git submodule update --init -- ./sources/entertainment/
668     sources/entertainment
5592    .
./buildEntertainment.sh	5	7
872     sources/entertainment
5808    .
git submodule update --init -- ./sources/flashlights/
2744    sources/flashlights/
11104   .
./buildFlashlights.sh	4	11
3000    sources/flashlights/
11376   .
git submodule update --init -- ./sources/tools
2752    sources/tools/
16380   .
./buildTools.sh		4	15
2952    sources/tools/
16604   .
git submodule update --init -- ./sources/widgets
3324    sources/widgets/
22504   .
./buildWidgets.sh	8	23
4144    sources/widgets/
22996   .
git submodule update --init -- ./sources/top10
4928    sources/top10/
29984   .
./buildTop10.sh		10	33
6008    sources/top10/
31104   .
git submodule update --init -- ./sources/liveWallpapers
12412   sources/liveWallpapers/
54444   .
./buildLiveWallpapers.sh 13	46
15924   sources/liveWallpapers/
58012   .
git submodule update --init -- ./sources/browsers
6736    sources/browsers/
78572   .
./buildBrowsers.sh	 4	50
8188    sources/browsers/
80308   .
git submodule update --init -- ./sources/games
19604   sources/games/
114780  .
./buildGames.sh
33996	games
git submodule update --init -- ./sources/samples
./buildSamples.sh (buildHelloWorlds.sh)
61808	samples
git submodule update --init -- ./sources/apps
./buildApplications.sh
73924	apps
git submodule update --init -- ./sources/tutorials
./buildTutorials.sh
138980	tutorials
Note: these build scripts pull more than one module.
git submodule update --init -- ./sources/clocks
./buildClocks.sh
6636	clocks
git submodule update --init -- ./sources/compasses
./buildCompasses.sh
2164	compasses 	6

./buildAll.sh
./buildAllInDir.sh

Total APKs
588
