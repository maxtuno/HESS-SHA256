cmake_minimum_required(VERSION 2.12)
project(HESS_ORACLES_COMPLETE)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)
# set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/lib)
# set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/lib)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_CXX_FLAGS "-mtune=native -static")

add_executable(hess-sha256 hess_sha256.cc)
add_executable(hess-sha256-mt hess_sha256_mt.cc)
add_executable(hess-sha256-mt-ascii hess_sha256_mt_ascii.cc)

