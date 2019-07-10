# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcompiler_rt)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/enable_execute_stack.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/adddf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashldi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashlti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashrdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashrti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clear_cache.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/cmpdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/cmpti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparedf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparesf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparetf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divmoddi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divmodsi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divxc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/eprintf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extenddftf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendhfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendsfdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendsftf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ffsdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ffsti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixxfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixxfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsitf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsitf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/gcc_personality_v0.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/int_util.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/lshrdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/lshrti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/moddi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/modsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/modti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulodi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulosi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muloti4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulsc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/multf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/multi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulxc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/paritydi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/paritysi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/parityti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powidf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powisf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powitf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powixf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subdf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trampoline_setup.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncdfhf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncdfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncsfhf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trunctfdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trunctfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ucmpdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ucmpti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmoddi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmodsi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmodti4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umoddi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umodsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umodti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundixf.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundisf.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundidf.S
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/compiler-rt'
# Raw param [1] = ''
# Raw param [2] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [3] = '${config.CommonClangGlobalCflags}'
# Raw param [4] = '${config.HostClangGlobalCflags}'
# Raw param [5] = ''
# Raw param [6] = '-Iexternal/libunwind/include'
# Raw param [7] = '-Iexternal/lzma/C'
# variable ${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags} = '-fno-exceptions -Wno-multichar -Wa,--noexecstack -fPIC -no-canonical-prefixes -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -O2 -g -fno-strict-aliasing --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot -fstack-protector-strong -m64'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-Wa,--noexecstack'
# Raw param [3] = '-fPIC'
# Raw param [4] = '-no-canonical-prefixes'
# Raw param [5] = '-U_FORTIFY_SOURCE'
# Raw param [6] = '-D_FORTIFY_SOURCE=2'
# Raw param [7] = '-fstack-protector'
# Raw param [8] = '-D__STDC_FORMAT_MACROS'
# Raw param [9] = '-D__STDC_CONSTANT_MACROS'
# Raw param [10] = '-O2'
# Raw param [11] = '-g'
# Raw param [12] = '-fno-strict-aliasing'
# Raw param [13] = '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8'
# Raw param [14] = '--sysroot'
# Raw param [15] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot'
# Raw param [16] = '-fstack-protector-strong'
# Raw param [17] = '-m64'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-fPIC' became -fPIC
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-O2' became -O2
# FLAG '-g' became -g
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8' became --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-m64' became -m64
# variable ${config.CommonClangGlobalCflags} = '-DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -DNDEBUG -UDEBUG -fdebug-prefix-map=/proc/self/cwd= -D__compiler_offsetof=__builtin_offsetof -Werror=int-conversion -Wno-reserved-id-macro -Wno-format-pedantic -Wno-unused-command-line-argument -fcolor-diagnostics -Wno-expansion-to-defined -fdebug-prefix-map=$$PWD/='
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
# Raw param [10] = '-D__compiler_offsetof=__builtin_offsetof'
# Raw param [11] = '-Werror=int-conversion'
# Raw param [12] = '-Wno-reserved-id-macro'
# Raw param [13] = '-Wno-format-pedantic'
# Raw param [14] = '-Wno-unused-command-line-argument'
# Raw param [15] = '-fcolor-diagnostics'
# Raw param [16] = '-Wno-expansion-to-defined'
# Raw param [17] = '-fdebug-prefix-map=$$PWD/='
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
# FLAG '-D__compiler_offsetof=__builtin_offsetof' became -D__compiler_offsetof=__builtin_offsetof
# FLAG '-Werror=int-conversion' became -Werror=int-conversion
# FLAG '-Wno-reserved-id-macro' became -Wno-reserved-id-macro
# FLAG '-Wno-format-pedantic' became -Wno-format-pedantic
# FLAG '-Wno-unused-command-line-argument' became -Wno-unused-command-line-argument
# FLAG '-fcolor-diagnostics' became -fcolor-diagnostics
# FLAG '-Wno-expansion-to-defined' became -Wno-expansion-to-defined
# FLAG '-fdebug-prefix-map=$$PWD/=' became -fdebug-prefix-map=$$PWD/=
# variable ${config.HostClangGlobalCflags} = ''
# Raw param [0] = ''
include_directories( 
    "${ANDROID_ROOT}/external/compiler-rt"
    "${ANDROID_ROOT}/external/libunwind/include"
    "${ANDROID_ROOT}/external/lzma/C"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/compiler-rt/**/*.h"
    "${ANDROID_ROOT}/external/libunwind/include/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fcolor-diagnostics")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-expansion-to-defined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdebug-prefix-map=$$PWD/=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fcolor-diagnostics")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-expansion-to-defined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdebug-prefix-map=$$PWD/=")
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot/usr/include")

# CFLAGS:
# Raw param [0] = '-Wno-unused-parameter'
# Raw param [1] = '-Werror'
# Raw param [2] = '-target x86_64-linux-gnu'
# Raw param [3] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [4] = '-fPIC'
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Werror' became -Werror
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++14'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.LinuxClangCppflags} ${config.LinuxX8664ClangCppflags}'
# Raw param [3] = '-nostdinc++'
# FLAG '-std=gnu++14' became -std=gnu++14
# variable ${config.CommonClangGlobalCppflags} = '-Wsign-promo -Wno-inconsistent-missing-override -Wno-null-dereference -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS -Wno-thread-safety-negative'
# Raw param [0] = '-Wsign-promo'
# Raw param [1] = '-Wno-inconsistent-missing-override'
# Raw param [2] = '-Wno-null-dereference'
# Raw param [3] = '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS'
# Raw param [4] = '-Wno-thread-safety-negative'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-Wno-inconsistent-missing-override' became -Wno-inconsistent-missing-override
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS' became -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS
# FLAG '-Wno-thread-safety-negative' became -Wno-thread-safety-negative
# variable ${config.LinuxClangCppflags} ${config.LinuxX8664ClangCppflags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8 -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward'
# Raw param [4] = '-isystem'
# Raw param [5] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux'
# FLAG '-nostdinc++' became -nostdinc++
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdinc++")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = ''
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
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
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


add_executable(libcompiler_rt ${SOURCE_FILES})
