cmake_minimum_required(VERSION 3.15) 
									 
									 

set(PROJECT_NAME Final-lab)				 		 
project("${PROJECT_NAME}")


set(CMAKE_CXX_STANDARD 17)			
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

include_directories("inc/")

add_executable("${PROJECT_NAME}" main.cpp
				 main.h
				 Game.cpp
				 Game.h
				 game_interface.cpp
				 game_interface.h
)