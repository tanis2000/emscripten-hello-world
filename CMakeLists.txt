project(hello)

cmake_minimum_required(VERSION 3.17)

file(GLOB SOURCE_FILES
${CMAKE_SOURCE_DIR}/src/*.c
)

add_executable(${PROJECT_NAME} MACOSX_BUNDLE ${EXE_TYPE} ${SOURCE_FILES})