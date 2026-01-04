
add_executable(test_fd_chelpers
    test_main.c)

target_link_libraries(test_fd_chelpers
    PRIVATE
        fd_chelpers
)

target_include_directories(test_fd_chelpers
    PUBLIC
        ${PROJECT_SOURCE_DIR}/src/include
)
