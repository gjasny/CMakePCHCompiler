add_library(engine STATIC src/engine.cpp src/library.cpp)
target_precompiled_header(engine src/prefix.h)

add_executable(demo src/demo.cpp)
target_link_libraries(demo engine)
target_precompiled_header(demo src/prefix.h REUSE engine)
