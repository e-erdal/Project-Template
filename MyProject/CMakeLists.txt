add_executable(${CMAKE_PROJECT_NAME} main.cc)
    # target_link_libraries(${CMAKE_PROJECT_NAME} PUBLIC lib)
    target_include_directories(${CMAKE_PROJECT_NAME} PUBLIC ./)
    set_target_properties(${CMAKE_PROJECT_NAME} PROPERTIES OUTPUT_NAME "${CMAKE_PROJECT_NAME}-${CMAKE_BUILD_TYPE}")
