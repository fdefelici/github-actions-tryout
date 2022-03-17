project(TravisCPrj LANGUAGES C)

file(GLOB_RECURSE SOURCES ${CMAKE_CURRENT_SOURCE_DIR}/src/*.c)
add_executable(TravisExec ${SOURCES})
set_property(TARGET TravisExec PROPERTY C_STANDARD 11)
