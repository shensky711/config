# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libblasV8)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/cblas/src/cblas_caxpy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ccopy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cdotc_sub.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cdotu_sub.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cgbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cgemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cgemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cgerc.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cgeru.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cher.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cher2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cher2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cherk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chpr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_chpr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_csscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_cswap.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_csymm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_csyr2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_csyrk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctbsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctpsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctrmm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctrmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctrsm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ctrsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dasum.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_daxpy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dcopy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ddot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dgbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dgemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dgemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dger.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dnrm2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_drot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_drotg.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_drotm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_drotmg.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsdot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dspmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dspr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dspr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dswap.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsymm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsymv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsyr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsyr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsyr2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dsyrk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtbsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtpsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtrmm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtrmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtrsm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dtrsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dzasum.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_dznrm2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_globals.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_icamax.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_idamax.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_isamax.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_izamax.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sasum.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_saxpy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_scasum.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_scnrm2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_scopy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sdot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sdsdot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sgbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sgemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sgemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sger.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_snrm2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_srot.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_srotg.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_srotm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_srotmg.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sspmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sspr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sspr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_sswap.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssymm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssymv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssyr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssyr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssyr2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ssyrk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_stbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_stbsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_stpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_stpsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_strmm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_strmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_strsm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_strsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_xerbla.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zaxpy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zcopy.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zdotc_sub.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zdotu_sub.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zdscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zgbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zgemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zgemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zgerc.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zgeru.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhemm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhemv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zher.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zher2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zher2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zherk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhpr.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zhpr2.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zscal.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zswap.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zsymm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zsyr2k.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_zsyrk.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztbmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztbsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztpmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztpsv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztrmm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztrmv.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztrsm.c
    ${ANDROID_ROOT}/external/cblas/src/cblas_ztrsv.c
    ${ANDROID_ROOT}/external/cblas/src/xerbla.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/cblas/include'
# Raw param [1] = '-Iexternal/cblas'
# Raw param [2] = '-D__ANDROID_API__=9'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [8] = '-Iexternal/eigen/blas'
# Raw param [9] = '-isystemprebuilts/ndk/current/sources/cxx-stl/llvm-libc++/include'
# Raw param [10] = '-isystemprebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include'
# Raw param [11] = '-isystemprebuilts/ndk/current/sources/android/support/include'
# FLAG '-D__ANDROID_API__=9' became -D__ANDROID_API__=9
# variable ${config.ArmClangThumbCflags} = '-mthumb -Os -fomit-frame-pointer -fno-strict-aliasing'
# Raw param [0] = '-mthumb'
# Raw param [1] = '-Os'
# Raw param [2] = '-fomit-frame-pointer'
# Raw param [3] = '-fno-strict-aliasing'
# FLAG '-mthumb' became -mthumb
# FLAG '-Os' became -Os
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# variable ${config.ArmClangCflags} = '-fno-exceptions -Wno-multichar -ffunction-sections -fdata-sections -funwind-tables -fstack-protector-strong -Wa,--noexecstack -Werror=format-security -D_FORTIFY_SOURCE=2 -fno-short-enums -no-canonical-prefixes -DNDEBUG -g -Wstrict-aliasing=2'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-ffunction-sections'
# Raw param [3] = '-fdata-sections'
# Raw param [4] = '-funwind-tables'
# Raw param [5] = '-fstack-protector-strong'
# Raw param [6] = '-Wa,--noexecstack'
# Raw param [7] = '-Werror=format-security'
# Raw param [8] = '-D_FORTIFY_SOURCE=2'
# Raw param [9] = '-fno-short-enums'
# Raw param [10] = '-no-canonical-prefixes'
# Raw param [11] = '-DNDEBUG'
# Raw param [12] = '-g'
# Raw param [13] = '-Wstrict-aliasing=2'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-g' became -g
# FLAG '-Wstrict-aliasing=2' became -Wstrict-aliasing=2
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
# variable ${config.DeviceClangGlobalCflags} = '-Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Werror=date-time -nostdlibinc'
# Raw param [0] = '-Werror=return-type'
# Raw param [1] = '-Werror=non-virtual-dtor'
# Raw param [2] = '-Werror=address'
# Raw param [3] = '-Werror=sequence-point'
# Raw param [4] = '-Werror=date-time'
# Raw param [5] = '-nostdlibinc'
# FLAG '-Werror=return-type' became -Werror=return-type
# FLAG '-Werror=non-virtual-dtor' became -Werror=non-virtual-dtor
# FLAG '-Werror=address' became -Werror=address
# FLAG '-Werror=sequence-point' became -Werror=sequence-point
# FLAG '-Werror=date-time' became -Werror=date-time
# FLAG '-nostdlibinc' became -nostdlibinc
# variable ${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags} = '-msoft-float -mfloat-abi=softfp -mfpu=neon -march=armv7-a'
# Raw param [0] = '-msoft-float'
# Raw param [1] = '-mfloat-abi=softfp'
# Raw param [2] = '-mfpu=neon'
# Raw param [3] = '-march=armv7-a'
# FLAG '-msoft-float' became -msoft-float
# FLAG '-mfloat-abi=softfp' became -mfloat-abi=softfp
# FLAG '-mfpu=neon' became -mfpu=neon
# FLAG '-march=armv7-a' became -march=armv7-a
# Found a header search path marker with no pathinclude_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystemprebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystemprebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/external/cblas/include"
    "${ANDROID_ROOT}/external/cblas"
    "${ANDROID_ROOT}/external/eigen/blas"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/cblas/include/**/*.h"
    "${ANDROID_ROOT}/external/cblas/**/*.h"
    "${ANDROID_ROOT}/external/eigen/blas/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=9")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mthumb")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wstrict-aliasing=2")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=return-type")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=address")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=sequence-point")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=date-time")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -nostdlibinc")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msoft-float")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfloat-abi=softfp")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv7-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=9")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mthumb")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wstrict-aliasing=2")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=address")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=sequence-point")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=date-time")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdlibinc")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msoft-float")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfloat-abi=softfp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv7-a")

# CFLAGS:
# Raw param [0] = '-target arm-linux-androideabi'
# Raw param [1] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [2] = '-fPIC'
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

# C ONLY FLAGS:
# Raw param [0] = '${config.CommonGlobalConlyflags}'
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''

# CPP FLAGS:
# Raw param [0] = '${config.CommonClangGlobalCppflags}'
# Raw param [1] = '-fno-rtti'
# Raw param [2] = '${config.ArmClangCppflags}'
# Raw param [3] = '-std=c++11'
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
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
# FLAG '-std=c++11' became -std=c++11
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '-isystem out/soong/ndk/sysroot/usr/include'
# Raw param [1] = '-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi'
# Raw param [2] = '-isystem prebuilts/ndk/current/platforms/android-9/arch-arm/usr/include'
# Found a header search path marker with no pathinclude_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(libblasV8 ${SOURCE_FILES})
