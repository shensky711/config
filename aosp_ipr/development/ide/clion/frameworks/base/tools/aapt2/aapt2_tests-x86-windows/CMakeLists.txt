# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(aapt2_tests)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/test/Builders.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/test/Common.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ConfigDescription_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/DominatorTree_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Locale_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/NameMangler_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceParser_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceTable_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceUtils_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceValues_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Resource_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/SdkConstants_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/StringPool_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ValueVisitor_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Util_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/IdAssigner_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/InlineXmlFormatParser_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/NinePatch_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PseudolocaleGenerator_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/Pseudolocalizer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/XmlIdCollector_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/configuration/ConfigurationParser_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/AbiFilter_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/ConfigFilter_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/Filter_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/flatten/TableFlattener_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/flatten/XmlFlattener_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/FileInputStream_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/StringInputStream_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/AnnotationProcessor_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/JavaClassGenerator_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ManifestClassGenerator_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ProguardRules_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/AutoVersioner_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ManifestFixer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/PrivateAttributeMover_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ProductFilter_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ReferenceLinker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/TableMerger_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlCompatVersioner_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlNamespaceRemover_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlReferenceLinker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/ResourceDeduper_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/VersionCollapser_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/process/SymbolTable_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/proto/TableProtoSerializer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/split/TableSplitter_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Unicode_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Utf8Iterator_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/BigBuffer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Files_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Maybe_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Util_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlActionExecutor_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlDom_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlPullParser_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlUtil_test.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Compile.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Diff.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Dump.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Link.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Optimize.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/cmd/Util.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/base/tools/aapt2'
# Raw param [1] = ''
# Raw param [2] = '${config.WindowsCflags} ${config.WindowsX86Cflags}'
# Raw param [3] = '${config.CommonGlobalCflags}'
# Raw param [4] = '${config.HostGlobalCflags}'
# Raw param [5] = ''
# Raw param [6] = '-Iexternal/googletest/googletest/include'
# Raw param [7] = '-Iexternal/zlib'
# Raw param [8] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [9] = '-Isystem/core/libutils/include'
# Raw param [10] = '-Isystem/core/liblog/include'
# Raw param [11] = '-Isystem/core/libsystem/include'
# Raw param [12] = '-Isystem/core/libcutils/include'
# Raw param [13] = '-Iexternal/expat/lib'
# Raw param [14] = '-Isystem/core/libziparchive/include'
# Raw param [15] = '-Iexternal/libpng'
# Raw param [16] = '-Isystem/core/base/include'
# Raw param [17] = '-Iexternal/protobuf/src'
# Raw param [18] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto/frameworks/base/tools/aapt2'
# Raw param [19] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto'
# Raw param [20] = '-Iexternal/googletest/googlemock/include'
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
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/system/core/libziparchive/include"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/system/core/libziparchive/include/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-Wno-maybe-uninitialized'
# Raw param [4] = '-DANDROID_STRICT'
# Raw param [5] = '-DGTEST_HAS_STD_STRING'
# Raw param [6] = '-O0'
# Raw param [7] = '-g'
# Raw param [8] = '-DGTEST_OS_WINDOWS'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-maybe-uninitialized' became -Wno-maybe-uninitialized
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-O0' became -O0
# FLAG '-g' became -g
# FLAG '-DGTEST_OS_WINDOWS' became -DGTEST_OS_WINDOWS
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_WINDOWS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_WINDOWS")

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
# Raw param [2] = '-Wno-missing-field-initializers'
# Raw param [3] = '-fno-exceptions'
# Raw param [4] = '-fno-rtti'
# Raw param [5] = ''
# FLAG '-std=gnu++11' became -std=gnu++11
# variable ${config.CommonGlobalCppflags} = '-Wsign-promo'
# Raw param [0] = '-Wsign-promo'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-fno-rtti' became -fno-rtti
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")

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


add_executable(aapt2_tests ${SOURCE_FILES})
