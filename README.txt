This repository contains various tools that are used in the LuaDist [1,2] project.

travis
	travis - Utility functions for travis-ci[3] hooks
	travis.yml - Hook definition. copy to project roos as ".travis.yml"
cmake
	dist.cmake - CMake[4] utility functions to be called from the "CMakeLists.txt" files in each package.
 	lua.cmake - CMake utility functions for use when building Lua modules.
 	FindLua.cmake - Recommended Lua find module that will also work with lua 5.2 and luajit

[1] http://luadist.org
[2] https://github.com/LuaDist/
[3] http://travis-ci.org
[4] http://cmake.org
