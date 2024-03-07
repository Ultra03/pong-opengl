add_executable(pong main.cpp)
target_include_directories(pong PRIVATE ../dep/glfw/include)
target_compile_features(pong PRIVATE cxx_std_17)
target_link_libraries(pong glfw ${GLFW_LIBRARIES})
