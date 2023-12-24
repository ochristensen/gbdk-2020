cmake_minimum_required(VERSION 3.28)

add_executable(gbcompress
    files_c_source.c
    files.c
    gbcompress.c
    main.c
    rlecompress.c
)
