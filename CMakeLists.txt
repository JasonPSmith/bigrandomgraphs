cmake_minimum_required(VERSION 3.15)
project(pybrg LANGUAGES CXX)

find_package(pybind11 CONFIG REQUIRED)

pybind11_add_module(pybrg src/wrapper_bindings.cpp)

install(TARGETS pybrg DESTINATION .)
