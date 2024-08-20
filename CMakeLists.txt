cmake_minimum_required (VERSION 3.5) #Enter the CMAKE version 
project (Radar-Fetch) #Project name
add_executable(main src/main.cpp) #If the first or second param (the output name of the exec) is changed, ensure it is also changed in the build.sh file