cmake_minimum_required(VERSION 2.8)
project(SalMetric. C CXX)


set(SalMetric_INCLUDE_DIR ${PROJECT_SOURCE_DIR}/include)
include_directories(${SalMetric_INCLUDE_DIR})
message(STATUS ${SalMetric_INCLUDE_DIR})

add_subdirectory(src)

