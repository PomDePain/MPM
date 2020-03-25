cmake_minimum_required(VERSION 2.6)
project(mpm_appli)
add_executable(mpm_appli main.c)
install(TARGETS mpm_appli DESTINATION bin)
