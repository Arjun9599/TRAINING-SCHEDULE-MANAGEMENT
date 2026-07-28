cmake_minimum_required(VERSION 3.10...3.30)

project(TraingScheduleManagement 
VERSION 1.0.1 
DESCRIPTION "Training Schedule Management in C++" 
HOMEPAGE_URL "https://github.com/kishanrajput23/Training-Schedule-Management"
LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(app src/main.cpp)