CMAKE_MINIMUM_REQUIRED(VERSION 4.4.5)
PROJECT(elgato-gchd-lite)
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -Wall -Wextra -Wno-unused-parameter -Wno-reorder -Wno-missing-field-initializers")

ADD_SUBDIRECTORY(src)
