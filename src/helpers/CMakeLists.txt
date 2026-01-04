add_library(fd_chelpers SHARED)

target_sources(fd_chelpers
    PRIVATE
        fdch_files.c
    PUBLIC
        FILE_SET fd_helpers_headers
        TYPE HEADERS
        BASE_DIRS
            ${PROJECT_SOURCE_DIR}/src/include
        FILES
            ${PROJECT_SOURCE_DIR}/src/include/fdch_files.h
)
