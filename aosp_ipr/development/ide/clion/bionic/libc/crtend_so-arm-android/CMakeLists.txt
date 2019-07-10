# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(crtend_so)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9/bin/arm-linux-androideabi-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/bionic/libc/arch-common/bionic/crtend_so.S
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ibionic/libc/arch-arm/include -Ibionic/libc/include'
# Raw param [1] = '${config.ArmToolchainCflags} ${config.ArmArmv7ANeonCflags} ${config.ArmGenericCflags}'
# variable ${config.ArmToolchainCflags} ${config.ArmArmv7ANeonCflags} ${config.ArmGenericCflags} = '-mthumb-interwork -msoft-float -mfloat-abi=softfp -mfpu=neon -march=armv7-a'
# Raw param [0] = '-mthumb-interwork'
# Raw param [1] = '-msoft-float'
# Raw param [2] = '-mfloat-abi=softfp'
# Raw param [3] = '-mfpu=neon'
# Raw param [4] = '-march=armv7-a'
# FLAG '-mthumb-interwork' became -mthumb-interwork
# FLAG '-msoft-float' became -msoft-float
# FLAG '-mfloat-abi=softfp' became -mfloat-abi=softfp
# FLAG '-mfpu=neon' became -mfpu=neon
# FLAG '-march=armv7-a' became -march=armv7-a
include_directories( 
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include -Ibionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include -Ibionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mthumb-interwork")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msoft-float")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfloat-abi=softfp")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv7-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mthumb-interwork")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msoft-float")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfloat-abi=softfp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv7-a")

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

add_executable(crtend_so ${SOURCE_FILES})
