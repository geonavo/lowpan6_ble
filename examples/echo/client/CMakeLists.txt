cmake_minimum_required(VERSION 3.22)

set(EXTRA_COMPONENT_DIRS "../../..")

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

project(example-client
  VERSION 1.0
  LANGUAGES C
)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_COLOR_DIAGNOSTICS ON)
