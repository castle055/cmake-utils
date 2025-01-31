# Copyright (c) 2025, Víctor Castillo Agüero.
# SPDX-License-Identifier: GPL-3.0-or-later

SET(CMAKE_UTILS_DIR ${CMAKE_CURRENT_SOURCE_DIR}/src)

message(${CMAKE_UTILS_DIR}/compiler_flags.cmake)
include(${CMAKE_UTILS_DIR}/compiler_flags.cmake)
include(${CMAKE_UTILS_DIR}/ctest.cmake)
include(${CMAKE_UTILS_DIR}/docs.cmake)
