include_directories(${PROJECT_SOURCE_DIR}/Library)
file(GLOB_RECURSE SOURCES ${PROJECT_SOURCE_DIR}/Library/**.cpp)

add_library(sdg ${SOURCES})