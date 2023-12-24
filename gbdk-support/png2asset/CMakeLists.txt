cmake_minimum_required(VERSION 3.28)

add_executable(png2asset
    cmp_int_color.cpp
    image_data.cpp
    lodepng.cpp
    map_attributes.cpp
    metasprites.cpp
    png2asset.cpp
    rgb_to_nes_lut.cpp
    export.cpp
    image_utils.cpp
    main.cpp
    maps.cpp
    palettes.cpp
    process_arguments.cpp
    tiles.cpp
)
