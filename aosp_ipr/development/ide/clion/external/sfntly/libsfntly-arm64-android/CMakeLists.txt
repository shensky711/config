# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libsfntly)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_output_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/growable_memory_byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/memory_byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/readable_font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/writable_font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/font.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/font_factory.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/file_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/lock.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/memory_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/memory_output_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/big_glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_glyph_info.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_size_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/composite_bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/ebdt_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/eblc_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/ebsc_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format1.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format2.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format3.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format4.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format5.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/simple_bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/small_glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/byte_array_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/cmap_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/font_header_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_device_metrics_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_header_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_metrics_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/maximum_profile_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/name_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/os2_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/font_data_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/generic_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/header.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/subtable.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/table_based_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/truetype/glyph_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/truetype/loca_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/tag.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sample/chromium/font_subsetter.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sample/chromium/subsetter_impl.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/sfntly/cpp/src'
# Raw param [1] = '-Iexternal/sfntly'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/libcxx/include'
# Raw param [8] = '-Iexternal/libcxxabi/include'
# Raw param [9] = '-Iexternal/icu/icu4c/source/common'
# Raw param [10] = '-Iexternal/icu/icu4c/source/i18n'
# variable ${config.Arm64ClangCflags} = '-fno-exceptions -Wno-multichar -fno-strict-aliasing -fstack-protector-strong -ffunction-sections -fdata-sections -funwind-tables -Wa,--noexecstack -Werror=format-security -D_FORTIFY_SOURCE=2 -fno-short-enums -no-canonical-prefixes -Werror=pointer-to-int-cast -Werror=int-to-pointer-cast -Werror=implicit-function-declaration -DNDEBUG -O2 -g -Wstrict-aliasing=2'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-fno-strict-aliasing'
# Raw param [3] = '-fstack-protector-strong'
# Raw param [4] = '-ffunction-sections'
# Raw param [5] = '-fdata-sections'
# Raw param [6] = '-funwind-tables'
# Raw param [7] = '-Wa,--noexecstack'
# Raw param [8] = '-Werror=format-security'
# Raw param [9] = '-D_FORTIFY_SOURCE=2'
# Raw param [10] = '-fno-short-enums'
# Raw param [11] = '-no-canonical-prefixes'
# Raw param [12] = '-Werror=pointer-to-int-cast'
# Raw param [13] = '-Werror=int-to-pointer-cast'
# Raw param [14] = '-Werror=implicit-function-declaration'
# Raw param [15] = '-DNDEBUG'
# Raw param [16] = '-O2'
# Raw param [17] = '-g'
# Raw param [18] = '-Wstrict-aliasing=2'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-Werror=pointer-to-int-cast' became -Werror=pointer-to-int-cast
# FLAG '-Werror=int-to-pointer-cast' became -Werror=int-to-pointer-cast
# FLAG '-Werror=implicit-function-declaration' became -Werror=implicit-function-declaration
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-O2' became -O2
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
include_directories( 
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/sfntly"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
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

# CFLAGS:
# Raw param [0] = '-fstack-protector'
# Raw param [1] = '--param=ssp-buffer-size=4'
# Raw param [2] = '-Werror'
# Raw param [3] = '-fno-exceptions'
# Raw param [4] = '-fno-strict-aliasing'
# Raw param [5] = '-Wall'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-Wno-missing-field-initializers'
# Raw param [8] = '-fvisibility=hidden'
# Raw param [9] = '-fPIC'
# Raw param [10] = '-ffunction-sections'
# Raw param [11] = '-funwind-tables'
# Raw param [12] = '-g'
# Raw param [13] = '-fstack-protector'
# Raw param [14] = '-fno-short-enums'
# Raw param [15] = '-Wa,--noexecstack'
# Raw param [16] = '-U_FORTIFY_SOURCE'
# Raw param [17] = '-Wno-extra'
# Raw param [18] = '-Wno-ignored-qualifiers'
# Raw param [19] = '-Wno-type-limits'
# Raw param [20] = '-Os'
# Raw param [21] = '-fno-ident'
# Raw param [22] = '-fdata-sections'
# Raw param [23] = '-ffunction-sections'
# Raw param [24] = '-fomit-frame-pointer'
# Raw param [25] = '-DANGLE_DX11'
# Raw param [26] = '-D_FILE_OFFSET_BITS=64'
# Raw param [27] = '-DNO_TCMALLOC'
# Raw param [28] = '-DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY'
# Raw param [29] = '-DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE'
# Raw param [30] = '-DDISABLE_NACL'
# Raw param [31] = '-DCHROMIUM_BUILD'
# Raw param [32] = '-DUSE_LIBJPEG_TURBO=1'
# Raw param [33] = '-DUSE_PROPRIETARY_CODECS'
# Raw param [34] = '-DENABLE_CONFIGURATION_POLICY'
# Raw param [35] = '-DENABLE_GPU=1'
# Raw param [36] = '-DUSE_OPENSSL=1'
# Raw param [37] = '-DENABLE_EGLIMAGE=1'
# Raw param [38] = '-DSFNTLY_NO_EXCEPTION'
# Raw param [39] = '-DU_USING_ICU_NAMESPACE=0'
# Raw param [40] = '-D__STDC_CONSTANT_MACROS'
# Raw param [41] = '-D__STDC_FORMAT_MACROS'
# Raw param [42] = '-DANDROID'
# Raw param [43] = '-D__GNU_SOURCE=1'
# Raw param [44] = '-D_STLP_USE_PTR_SPECIALIZATIONS=1'
# Raw param [45] = ''-DCHROME_BUILD_ID='\''""'\''''
# Raw param [46] = '-DNDEBUG'
# Raw param [47] = '-DNVALGRIND'
# Raw param [48] = '-DDYNAMIC_ANNOTATIONS_ENABLED=0'
# Raw param [49] = '-D_FORTIFY_SOURCE=2'
# Raw param [50] = '-target aarch64-linux-android'
# Raw param [51] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [52] = '-fPIC'
# Raw param [53] = '-D_USING_LIBCXX'
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '--param=ssp-buffer-size=4' became --param=ssp-buffer-size=4
# FLAG '-Werror' became -Werror
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-fPIC' became -fPIC
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-g' became -g
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-Wno-extra' became -Wno-extra
# FLAG '-Wno-ignored-qualifiers' became -Wno-ignored-qualifiers
# FLAG '-Wno-type-limits' became -Wno-type-limits
# FLAG '-Os' became -Os
# FLAG '-fno-ident' became -fno-ident
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-DANGLE_DX11' became -DANGLE_DX11
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-DNO_TCMALLOC' became -DNO_TCMALLOC
# FLAG '-DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY' became -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY
# FLAG '-DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE' became -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE
# FLAG '-DDISABLE_NACL' became -DDISABLE_NACL
# FLAG '-DCHROMIUM_BUILD' became -DCHROMIUM_BUILD
# FLAG '-DUSE_LIBJPEG_TURBO=1' became -DUSE_LIBJPEG_TURBO=1
# FLAG '-DUSE_PROPRIETARY_CODECS' became -DUSE_PROPRIETARY_CODECS
# FLAG '-DENABLE_CONFIGURATION_POLICY' became -DENABLE_CONFIGURATION_POLICY
# FLAG '-DENABLE_GPU=1' became -DENABLE_GPU=1
# FLAG '-DUSE_OPENSSL=1' became -DUSE_OPENSSL=1
# FLAG '-DENABLE_EGLIMAGE=1' became -DENABLE_EGLIMAGE=1
# FLAG '-DSFNTLY_NO_EXCEPTION' became -DSFNTLY_NO_EXCEPTION
# FLAG '-DU_USING_ICU_NAMESPACE=0' became -DU_USING_ICU_NAMESPACE=0
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-DANDROID' became -DANDROID
# FLAG '-D__GNU_SOURCE=1' became -D__GNU_SOURCE=1
# FLAG '-D_STLP_USE_PTR_SPECIALIZATIONS=1' became -D_STLP_USE_PTR_SPECIALIZATIONS=1
# FLAG ''-DCHROME_BUILD_ID='\''""'\'''' became -DCHROME_BUILD_ID='\\\"\\\"'
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-DNVALGRIND' became -DNVALGRIND
# FLAG '-DDYNAMIC_ANNOTATIONS_ENABLED=0' became -DDYNAMIC_ANNOTATIONS_ENABLED=0
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} --param=ssp-buffer-size=4")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-extra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-type-limits")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-ident")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANGLE_DX11")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_TCMALLOC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_NACL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHROMIUM_BUILD")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_LIBJPEG_TURBO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_PROPRIETARY_CODECS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_CONFIGURATION_POLICY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_GPU=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_OPENSSL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_EGLIMAGE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSFNTLY_NO_EXCEPTION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__GNU_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_STLP_USE_PTR_SPECIALIZATIONS=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHROME_BUILD_ID='\\\"\\\"'")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNVALGRIND")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --param=ssp-buffer-size=4")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-extra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-type-limits")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-ident")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANGLE_DX11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_TCMALLOC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_NACL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHROMIUM_BUILD")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_LIBJPEG_TURBO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_PROPRIETARY_CODECS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_CONFIGURATION_POLICY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_GPU=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_OPENSSL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_EGLIMAGE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSFNTLY_NO_EXCEPTION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__GNU_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_STLP_USE_PTR_SPECIALIZATIONS=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHROME_BUILD_ID='\\\"\\\"'")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNVALGRIND")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

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
# Raw param [2] = '-fno-threadsafe-statics'
# Raw param [3] = '-fvisibility-inlines-hidden'
# Raw param [4] = '-Wsign-compare'
# Raw param [5] = '-Wno-abi'
# Raw param [6] = '-Wno-error=c++0x-compat'
# Raw param [7] = '-Wno-non-virtual-dtor'
# Raw param [8] = '-Wno-sign-promo'
# Raw param [9] = '-Wno-error=user-defined-warnings'
# Raw param [10] = '-fno-rtti'
# Raw param [11] = '${config.Arm64ClangCppflags}'
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
# FLAG '-fno-threadsafe-statics' became -fno-threadsafe-statics
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
# FLAG '-Wsign-compare' became -Wsign-compare
# FLAG '-Wno-abi' became -Wno-abi
# FLAG '-Wno-error=c++0x-compat' became -Wno-error=c++0x-compat
# FLAG '-Wno-non-virtual-dtor' became -Wno-non-virtual-dtor
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-Wno-error=user-defined-warnings' became -Wno-error=user-defined-warnings
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-threadsafe-statics")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-abi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=c++0x-compat")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=user-defined-warnings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.Arm64IncludeFlags}'
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
# variable ${config.Arm64IncludeFlags} = '-isystem bionic/libc/arch-arm64/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm64 -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/arch-arm64/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/include'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/uapi/asm-arm64'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/scsi'
# Raw param [10] = '-isystem'
# Raw param [11] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi/**/*.h"
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


add_executable(libsfntly ${SOURCE_FILES})
