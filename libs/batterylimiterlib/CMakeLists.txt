add_library(batterylimiterlib src/batterylimiterlib.cpp)

target_include_directories(batterylimiterlib PUBLIC include)

install(TARGETS batterylimiterlib)
install(DIRECTORY include/ DESTINATION include/batterylimiterlib)
