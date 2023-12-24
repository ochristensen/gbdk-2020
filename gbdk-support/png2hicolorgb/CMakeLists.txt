cmake_minimum_required(VERSION 3.28)

add_executable(png2hicolorgb
    src/c_source.c
    src/common.c
    src/files.c
    src/hicolor/hicolour.c
    src/hicolor/median.c
    src/hicolor/Wu.c
    src/lodepng/lodepng.c
    src/image_load.c
    src/logging.c
    src/main.c
    src/options.c
    src/path_ops.c
    src/tile_dedupe.c
)

target_include_directories(png2hicolorgb PRIVATE
    src/
    src/hicolor
    src/lodepng
)
