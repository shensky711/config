# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libbcc)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/BCCContext.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/BCCContextImpl.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/Compiler.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/CompilerConfig.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/FileBase.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/Initialization.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSAddDebugInfoPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSCompilerDriver.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSEmbedInfo.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSGlobalInfoPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSInvariant.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSInvokeHelperPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSIsThreadablePass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSKernelExpand.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSScreenFunctionsPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSScriptGroupFusion.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSStubsWhiteList.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSX86CallConvPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/RSX86TranslateGEPPass.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/Script.cpp
    ${ANDROID_ROOT}/frameworks/compile/libbcc/lib/Source.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/compile/libbcc/include -Iframeworks/rs'
# Raw param [1] = '-Iframeworks/compile/libbcc/lib'
# Raw param [2] = ''
# Raw param [3] = '${config.WindowsCflags} ${config.WindowsX86Cflags}'
# Raw param [4] = '${config.CommonGlobalCflags}'
# Raw param [5] = '${config.HostGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/llvm/include'
# Raw param [8] = '-Iexternal/llvm/host/include'
# Raw param [9] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-attributes/gen'
# Raw param [10] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen'
# Raw param [11] = '-Iframeworks/compile/slang'
# Raw param [12] = '-Isystem/core/libutils/include'
# Raw param [13] = '-Isystem/core/liblog/include'
# Raw param [14] = '-Isystem/core/libsystem/include'
# Raw param [15] = '-Isystem/core/libcutils/include'
# Raw param [16] = '-Iframeworks/compile/libbcc/bcinfo/include'
# variable ${config.WindowsCflags} ${config.WindowsX86Cflags} = '-fno-exceptions -Wno-multichar -DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0600 -DWINVER=0x0600 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -O2 -g -fno-strict-aliasing -m32'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-DUSE_MINGW'
# Raw param [3] = '-DWIN32_LEAN_AND_MEAN'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-D__STDC_FORMAT_MACROS'
# Raw param [6] = '-D__STDC_CONSTANT_MACROS'
# Raw param [7] = '-D__USE_MINGW_ANSI_STDIO=1'
# Raw param [8] = '-D_WIN32_WINNT=0x0600'
# Raw param [9] = '-DWINVER=0x0600'
# Raw param [10] = '-D_FILE_OFFSET_BITS=64'
# Raw param [11] = '--sysroot'
# Raw param [12] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32'
# Raw param [13] = '-O2'
# Raw param [14] = '-g'
# Raw param [15] = '-fno-strict-aliasing'
# Raw param [16] = '-m32'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-DUSE_MINGW' became -DUSE_MINGW
# FLAG '-DWIN32_LEAN_AND_MEAN' became -DWIN32_LEAN_AND_MEAN
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__USE_MINGW_ANSI_STDIO=1' became -D__USE_MINGW_ANSI_STDIO=1
# FLAG '-D_WIN32_WINNT=0x0600' became -D_WIN32_WINNT=0x0600
# FLAG '-DWINVER=0x0600' became -DWINVER=0x0600
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-O2' became -O2
# FLAG '-g' became -g
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-m32' became -m32
# variable ${config.CommonGlobalCflags} = '-DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -DNDEBUG -UDEBUG -fdebug-prefix-map=/proc/self/cwd='
# Raw param [0] = '-DANDROID'
# Raw param [1] = '-fmessage-length=0'
# Raw param [2] = '-W'
# Raw param [3] = '-Wall'
# Raw param [4] = '-Wno-unused'
# Raw param [5] = '-Winit-self'
# Raw param [6] = '-Wpointer-arith'
# Raw param [7] = '-DNDEBUG'
# Raw param [8] = '-UDEBUG'
# Raw param [9] = '-fdebug-prefix-map=/proc/self/cwd='
# FLAG '-DANDROID' became -DANDROID
# FLAG '-fmessage-length=0' became -fmessage-length=0
# FLAG '-W' became -W
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused' became -Wno-unused
# FLAG '-Winit-self' became -Winit-self
# FLAG '-Wpointer-arith' became -Wpointer-arith
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-UDEBUG' became -UDEBUG
# FLAG '-fdebug-prefix-map=/proc/self/cwd=' became -fdebug-prefix-map=/proc/self/cwd=
# variable ${config.HostGlobalCflags} = ''
# Raw param [0] = ''
include_directories( 
    "${ANDROID_ROOT}/frameworks/compile/libbcc/include -Iframeworks/rs"
    "${ANDROID_ROOT}/frameworks/compile/libbcc/lib"
    "${ANDROID_ROOT}/external/llvm/include"
    "${ANDROID_ROOT}/external/llvm/host/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen"
    "${ANDROID_ROOT}/frameworks/compile/slang"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/frameworks/compile/libbcc/bcinfo/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/compile/libbcc/include -Iframeworks/rs/**/*.h"
    "${ANDROID_ROOT}/frameworks/compile/libbcc/lib/**/*.h"
    "${ANDROID_ROOT}/external/llvm/include/**/*.h"
    "${ANDROID_ROOT}/external/llvm/host/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/compile/slang/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/compile/libbcc/bcinfo/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_MINGW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_WIN32_WINNT=0x0600")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWINVER=0x0600")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fmessage-length=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winit-self")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_MINGW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_WIN32_WINNT=0x0600")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWINVER=0x0600")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fmessage-length=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winit-self")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/usr/include")

# CFLAGS:
# Raw param [0] = '-DRS_VERSION=24'
# Raw param [1] = '-D_GNU_SOURCE'
# Raw param [2] = '-D__STDC_LIMIT_MACROS'
# Raw param [3] = '-D__STDC_CONSTANT_MACROS'
# Raw param [4] = '-D__STDC_FORMAT_MACROS'
# Raw param [5] = '-fomit-frame-pointer'
# Raw param [6] = '-Wall'
# Raw param [7] = '-W'
# Raw param [8] = '-Wno-sign-compare'
# Raw param [9] = '-Wno-unused-parameter'
# Raw param [10] = '-Wno-maybe-uninitialized'
# Raw param [11] = '-Wno-missing-field-initializers'
# Raw param [12] = '-Wwrite-strings'
# Raw param [13] = '-Werror'
# Raw param [14] = '-Dsprintf=sprintf'
# Raw param [15] = '-Wall'
# Raw param [16] = '-Wno-unused-parameter'
# Raw param [17] = '-Werror'
# Raw param [18] = '-D__DISABLE_ASSERTS'
# Raw param [19] = '-D__HOST__'
# Raw param [20] = '-Wno-array-bounds'
# Raw param [21] = '-Wno-comment'
# Raw param [22] = '-UWIN32_LEAN_AND_MEAN'
# Raw param [23] = '-DANDROID_STRICT'
# FLAG '-DRS_VERSION=24' became -DRS_VERSION=24
# FLAG '-D_GNU_SOURCE' became -D_GNU_SOURCE
# FLAG '-D__STDC_LIMIT_MACROS' became -D__STDC_LIMIT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-Wall' became -Wall
# FLAG '-W' became -W
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-maybe-uninitialized' became -Wno-maybe-uninitialized
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wwrite-strings' became -Wwrite-strings
# FLAG '-Werror' became -Werror
# FLAG '-Dsprintf=sprintf' became -Dsprintf=sprintf
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Werror' became -Werror
# FLAG '-D__DISABLE_ASSERTS' became -D__DISABLE_ASSERTS
# FLAG '-D__HOST__' became -D__HOST__
# FLAG '-Wno-array-bounds' became -Wno-array-bounds
# FLAG '-Wno-comment' became -Wno-comment
# FLAG '-UWIN32_LEAN_AND_MEAN' became -UWIN32_LEAN_AND_MEAN
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DRS_VERSION=24")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wwrite-strings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Dsprintf=sprintf")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__DISABLE_ASSERTS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__HOST__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-array-bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-comment")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DRS_VERSION=24")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wwrite-strings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Dsprintf=sprintf")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__DISABLE_ASSERTS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__HOST__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-array-bounds")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-comment")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++11'
# Raw param [1] = '${config.CommonGlobalCppflags}'
# Raw param [2] = '-Wno-sign-promo'
# Raw param [3] = '-std=c++11'
# Raw param [4] = '-fno-rtti'
# Raw param [5] = '-fno-exceptions'
# Raw param [6] = ''
# FLAG '-std=gnu++11' became -std=gnu++11
# variable ${config.CommonGlobalCppflags} = '-Wsign-promo'
# Raw param [0] = '-Wsign-promo'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-std=c++11' became -std=c++11
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-fno-exceptions' became -fno-exceptions
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.WindowsIncludeFlags}'
# Raw param [2] = '${config.CommonNativehelperInclude}'
# variable ${config.CommonGlobalIncludes} = '-Isystem/core/include -Isystem/media/audio/include -Ihardware/libhardware/include -Ihardware/libhardware_legacy/include -Ihardware/ril/include -Ilibnativehelper/include -Iframeworks/native/include -Iframeworks/native/opengl/include -Iframeworks/av/include'
# Raw param [0] = '-Isystem/core/include'
# Raw param [1] = '-Isystem/media/audio/include'
# Raw param [2] = '-Ihardware/libhardware/include'
# Raw param [3] = '-Ihardware/libhardware_legacy/include'
# Raw param [4] = '-Ihardware/ril/include'
# Raw param [5] = '-Ilibnativehelper/include'
# Raw param [6] = '-Iframeworks/native/include'
# Raw param [7] = '-Iframeworks/native/opengl/include'
# Raw param [8] = '-Iframeworks/av/include'
# variable ${config.WindowsIncludeFlags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include -isystem prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/system/core/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include"
    "${ANDROID_ROOT}/hardware/ril/include"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/frameworks/native/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/av/include"
    "${ANDROID_ROOT}/libnativehelper/include_deprecated"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/core/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include/**/*.h"
    "${ANDROID_ROOT}/hardware/ril/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include_deprecated/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(libbcc ${SOURCE_FILES})
