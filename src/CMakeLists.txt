add_executable(main main.cpp)

# Specify version
target_compile_definitions(main PUBLIC VERSION_MAJOR=0)
target_compile_definitions(main PUBLIC VERSION_MINOR=0)
target_compile_definitions(main PUBLIC VERSION_PATCH=0)
