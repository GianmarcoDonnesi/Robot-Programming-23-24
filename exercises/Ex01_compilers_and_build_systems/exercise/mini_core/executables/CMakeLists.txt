# Compile executable that will be run
add_executable(many_objects_in_stack_example
    many_object_in_stack_example.cpp)

# Correcting the typo and linking against 'messages' and 'utils' libraries
target_link_libraries(many_objects_in_stack_example messages utils)
