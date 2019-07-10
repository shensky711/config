# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libclangCodeGen)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/BackendUtil.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGAtomic.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGBlocks.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGBuiltin.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCUDABuiltin.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCUDANV.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCUDARuntime.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCXX.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCXXABI.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCall.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGClass.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGCleanup.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGDebugInfo.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGDecl.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGDeclCXX.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGException.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExpr.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExprAgg.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExprCXX.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExprComplex.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExprConstant.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGExprScalar.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGLoopInfo.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGObjC.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGObjCGNU.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGObjCMac.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGObjCRuntime.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGOpenCLRuntime.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGOpenMPRuntime.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGOpenMPRuntimeNVPTX.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGRecordLayoutBuilder.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGStmt.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGStmtOpenMP.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGVTT.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CGVTables.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenABITypes.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenAction.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenFunction.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenModule.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenPGO.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenTBAA.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CodeGenTypes.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/CoverageMappingGen.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/ItaniumCXXABI.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/MicrosoftCXXABI.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/ModuleBuilder.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/ObjectFilePCHContainerOperations.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/SanitizerMetadata.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/SwiftCallingConv.cpp
    ${ANDROID_ROOT}/external/clang/lib/CodeGen/TargetInfo.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/clang/include -Iexternal/clang/lib/CodeGen'
# Raw param [1] = '-Iexternal/clang/lib/CodeGen'
# Raw param [2] = ''
# Raw param [3] = '${config.WindowsCflags} ${config.WindowsX8664Cflags}'
# Raw param [4] = '${config.CommonGlobalCflags}'
# Raw param [5] = '${config.HostGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/llvm/include'
# Raw param [8] = '-Iexternal/llvm/host/include'
# Raw param [9] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-attributes/gen'
# Raw param [10] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen'
# Raw param [11] = '-Iexternal/clang/include'
# Raw param [12] = '-Iout/soong/.intermediates/external/clang/clang-gen-options/gen'
# Raw param [13] = '-Iout/soong/.intermediates/external/clang/clang-gen-attributes/gen'
# Raw param [14] = '-Iout/soong/.intermediates/external/clang/clang-gen-checkers/gen'
# Raw param [15] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-commands/gen'
# Raw param [16] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen'
# Raw param [17] = '-Iout/soong/.intermediates/external/clang/clang-gen-html-tags/gen'
# Raw param [18] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen'
# Raw param [19] = '-Iout/soong/.intermediates/external/clang/clang-gen-diagnostics/gen'
# Raw param [20] = '-Iout/soong/.intermediates/external/clang/clang-gen-declnodes/gen'
# Raw param [21] = '-Iout/soong/.intermediates/external/clang/clang-gen-statnodes/gen'
# Raw param [22] = '-Iout/soong/.intermediates/external/clang/clang-gen-arm-neon/gen'
# Raw param [23] = '-Iout/soong/.intermediates/external/clang/clang-version/gen'
# variable ${config.WindowsCflags} ${config.WindowsX8664Cflags} = '-fno-exceptions -Wno-multichar -DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0600 -DWINVER=0x0600 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -O2 -g -fno-strict-aliasing -m64'
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
# Raw param [16] = '-m64'
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
# FLAG '-m64' became -m64
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
    "${ANDROID_ROOT}/external/clang/include -Iexternal/clang/lib/CodeGen"
    "${ANDROID_ROOT}/external/clang/lib/CodeGen"
    "${ANDROID_ROOT}/external/llvm/include"
    "${ANDROID_ROOT}/external/llvm/host/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen"
    "${ANDROID_ROOT}/external/clang/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-options/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-checkers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-commands/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-html-tags/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-diagnostics/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-declnodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-statnodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-arm-neon/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-version/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/clang/include -Iexternal/clang/lib/CodeGen/**/*.h"
    "${ANDROID_ROOT}/external/clang/lib/CodeGen/**/*.h"
    "${ANDROID_ROOT}/external/llvm/include/**/*.h"
    "${ANDROID_ROOT}/external/llvm/host/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen/**/*.h"
    "${ANDROID_ROOT}/external/clang/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-options/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-checkers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-commands/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-html-tags/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-diagnostics/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-declnodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-statnodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-arm-neon/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-version/gen/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m64")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m64")
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
# Raw param [0] = '-D_GNU_SOURCE'
# Raw param [1] = '-D__STDC_LIMIT_MACROS'
# Raw param [2] = '-D__STDC_CONSTANT_MACROS'
# Raw param [3] = '-D__STDC_FORMAT_MACROS'
# Raw param [4] = '-fomit-frame-pointer'
# Raw param [5] = '-Wall'
# Raw param [6] = '-W'
# Raw param [7] = '-Wno-sign-compare'
# Raw param [8] = '-Wno-unused-parameter'
# Raw param [9] = '-Wno-maybe-uninitialized'
# Raw param [10] = '-Wno-missing-field-initializers'
# Raw param [11] = '-Wwrite-strings'
# Raw param [12] = '-Werror'
# Raw param [13] = '-Dsprintf=sprintf'
# Raw param [14] = '-pedantic'
# Raw param [15] = '-Wcast-qual'
# Raw param [16] = '-Wno-long-long'
# Raw param [17] = '-Wno-array-bounds'
# Raw param [18] = '-Wno-comment'
# Raw param [19] = '-UWIN32_LEAN_AND_MEAN'
# Raw param [20] = '-Wno-error=uninitialized'
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
# FLAG '-pedantic' became -pedantic
# FLAG '-Wcast-qual' became -Wcast-qual
# FLAG '-Wno-long-long' became -Wno-long-long
# FLAG '-Wno-array-bounds' became -Wno-array-bounds
# FLAG '-Wno-comment' became -Wno-comment
# FLAG '-UWIN32_LEAN_AND_MEAN' became -UWIN32_LEAN_AND_MEAN
# FLAG '-Wno-error=uninitialized' became -Wno-error=uninitialized
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wcast-qual")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-long-long")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-array-bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-comment")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=uninitialized")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wcast-qual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-long-long")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-array-bounds")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-comment")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=uninitialized")

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


add_executable(libclangCodeGen ${SOURCE_FILES})
