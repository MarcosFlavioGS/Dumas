cmake_minimum_required(VERSION 2.27.4)

project(Dumas)

# Define the sources for your library
#set(LIB_SOURCES src/tree.cpp src/list.cpp)

# Create a static library from your sources
#add_library(${PROJECT_NAME}_lib STATIC ${LIB_SOURCES})

# Optionally, you can set the output directory for the library
#set_target_properties(${PROJECT_NAME}_lib PROPERTIES ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)

# Optionally, you can specify an include directory for headers
#target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_SOURCE_DIR}/include)

# If you want to create an executable that uses the static library
add_executable(${PROJECT_NAME} src/main/main.cpp)

# Link the executable with your library
#target_link_libraries(${PROJECT_NAME} PRIVATE ${PROJECT_NAME}_lib)
