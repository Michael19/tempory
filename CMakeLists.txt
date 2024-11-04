cmake_minimum_required(VERSION 3.5)

add_subdirectory(src)

add_custom_target(release
    SOURCES .github/workflows/release.yaml)
