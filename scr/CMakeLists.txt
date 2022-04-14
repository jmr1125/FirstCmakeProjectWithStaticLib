cmake_minimum_required(VERSION 3.0)


#set(executable_output_path "${project_binary_dir}/bin")
#link_directories("${project_binary_dir}/lib")

#include_directories("${project_binary_dir}/include")
# message("${project_binary_dir}/include")
#message("${PROJECT_BINARY_DIR}")

set(EXECUTABLE_OUTPUT_PATH "${PROJECT_BINARY_DIR}/bin")
#link_directories("${PROJECT_BINARY_DIR}/lib")
# include_directories("${PROJECT_BINARY_DIR}/../include")
# message("${PROJECT_BINARY_DIR}/../include/")
# message("${DIRS}")
# include_directories(../include)
include_directories("${PROJECT_SOURCE_DIR}/include")
message("${PROJECT_SOURCE_DIR}/include")


add_executable(main main.cpp)

target_link_libraries(main lib)
