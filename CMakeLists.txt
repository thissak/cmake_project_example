CMAKE_MINIMUM_REQUIRED (VERSION 3.15 )

# project setting
SET ( PROJECT_NAME cmake_project_example )
PROJECT ( ${PROJECT_NAME} )
SET( EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR} )

# C++ settings
SET( CMAKE_CXX_STANDARD 17 )

# set source and headers
SET ( SRC_FILES src/main.cpp )

# build 
ADD_EXECUTABLE( ${PROJECT_NAME} ${SRC_FILES} )