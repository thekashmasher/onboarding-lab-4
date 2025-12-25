cmake_minimum_required(VERSION 3.24)

include(cmake/BootstrapVcpkg.cmake)
nyu_add_sv(lab4
  Exercise1.sv Exercise2.sv Exercise3.sv Exercise4.sv
  Mysteries/Mystery1.sv Mysteries/Mystery2.sv
)

project(week-four-lab VERSION 1.0.0)
