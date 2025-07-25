cmake_minimum_required(VERSION 3.28)

project(course_project)

set(CMAKE_CXX_STANDARD 17)

include_directories(allocators)

add_executable(course_project
        allocators/allocator.h
        allocators/allocator_guardant.h
        allocators/allocator_guardant.cpp
        logger/logger.h
        logger/logger_builder.h
        logger/logger_guardant.h
        logger/logger.cpp
        tree/associative_container.h
        tree/search_tree.h
        tree/b_tree.h
        tree/binary_search_tree.h
        containers/database.h
        containers/pool.h
        containers/scheme.h
        containers/collection.h
        main.cpp
        containers/wb.h
        comparator/comparer.h
        logger/client_logger_builder.h
        logger/client_logger.h
        logger/client_logger_builder.cpp
        logger/client_logger.cpp
        logger/logger_builder.cpp
        logger/logger_guardant.h
        logger/logger_guardant.cpp
        enums/allocator_types.h
        allocators/allocator_with_fit_mode.h
        enums/enums.h
        allocators/allocator_sorted_list.cpp
        allocators/allocator_global_heap.cpp
        allocators/allocator_buddies_system.cpp
        allocators/allocator_boundary_tags.cpp
        validate/validate_parameters.h
        command/command.h
        command/command_add_value.h
        command/command_find_value.h
        command/command_update_value.h
        command/command_update_value.h
        command/command_find_between_value.h
        command/command_delete_value.h
        command/command_delete_value.h
        command/command_delete_pool.h
        command/command_add_scheme.h
        command/command_delete_scheme.h
        command/command_add_collection.h
        command/command_delete_collection.h
        command/command_add_pool.h
        command/file_save.h
        logger/logger_singleton.h
        validate/errors.h
        flyweight/flyweight_string.h
        flyweight/flyweight_fabric.h
        command/command_find_time_value.h
        chain__of_resposibility/handler.h
        chain__of_resposibility/request_with_command.h
        chain__of_resposibility/request_with_command_chain.h
)
