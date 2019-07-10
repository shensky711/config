# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(crtend_android)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/bin/aarch64-linux-android-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9/bin/aarch64-linux-android-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/bionic/libc/arch-common/bionic/crtend.S
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ibionic/libc/arch-arm64/include -Ibionic/libc/include'
# Raw param [1] = ''
include_directories( 
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include -Ibionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include -Ibionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


# CFLAGS:
# Raw param [0] = '-DANDROID_STRICT'
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# FLAG '-std=gnu99' became -std=gnu99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++11'
# FLAG '-std=gnu++11' became -std=gnu++11
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")

# SYSTEM INCLUDE FLAGS:

add_executable(crtend_android ${SOURCE_FILES})
