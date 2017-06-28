cmake_minimum_required(VERSION 2.8)

project(anyoption)

set(anyoption_SRCS
    anyoption.cpp)

include_directories(.)

add_library(anyoption
            ${anyoption_SRCS})

install(TARGETS anyoption DESTINATION lib)
install(FILES anyoption.h DESTINATION include)
