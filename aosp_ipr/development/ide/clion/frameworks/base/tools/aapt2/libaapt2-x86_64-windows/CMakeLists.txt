# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libaapt2)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/IdAssigner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/InlineXmlFormatParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/NinePatch.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/Png.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PngChunkFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PngCrunch.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PseudolocaleGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/Pseudolocalizer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/XmlIdCollector.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/configuration/ConfigurationParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/AbiFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/ConfigFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/flatten/Archive.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/flatten/TableFlattener.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/flatten/XmlFlattener.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/BigBufferStreams.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/File.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/FileInputStream.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/FileSystem.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/StringInputStream.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/Util.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/ZipArchive.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/AutoVersioner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ManifestFixer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ProductFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/PrivateAttributeMover.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ReferenceLinker.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/TableMerger.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlCompatVersioner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlNamespaceRemover.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlReferenceLinker.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/ResourceDeduper.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/VersionCollapser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/process/SymbolTable.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/proto/ProtoHelpers.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/proto/TableProtoDeserializer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/proto/TableProtoSerializer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/split/TableSplitter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Unicode.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Utf8Iterator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/unflatten/BinaryResourceParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/unflatten/ResChunkPullParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/BigBuffer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Files.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Util.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ConfigDescription.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Debug.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/DominatorTree.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Flags.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/AnnotationProcessor.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ClassDefinition.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/JavaClassGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ManifestClassGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ProguardRules.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/LoadedApk.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Locale.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Resource.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceTable.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceValues.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/SdkConstants.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/StringPool.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlActionExecutor.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlDom.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlPullParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlUtil.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/frameworks/base/tools/aapt2/Resources.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/frameworks/base/tools/aapt2/ResourcesInternal.pb.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/base/tools/aapt2'
# Raw param [1] = ''
# Raw param [2] = '${config.WindowsCflags} ${config.WindowsX8664Cflags}'
# Raw param [3] = '${config.CommonGlobalCflags}'
# Raw param [4] = '${config.HostGlobalCflags}'
# Raw param [5] = ''
# Raw param [6] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/frameworks/base/tools/aapt2'
# Raw param [7] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto'
# Raw param [8] = '-Iexternal/zlib'
# Raw param [9] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [10] = '-Isystem/core/libutils/include'
# Raw param [11] = '-Isystem/core/liblog/include'
# Raw param [12] = '-Isystem/core/libsystem/include'
# Raw param [13] = '-Isystem/core/libcutils/include'
# Raw param [14] = '-Iexternal/expat/lib'
# Raw param [15] = '-Isystem/core/libziparchive/include'
# Raw param [16] = '-Iexternal/libpng'
# Raw param [17] = '-Isystem/core/base/include'
# Raw param [18] = '-Iexternal/protobuf/src'
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
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto"
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
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/windows_x86_64_static/gen/proto/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-Wno-maybe-uninitialized'
# Raw param [4] = '-DANDROID_STRICT'
# Raw param [5] = '-DGOOGLE_PROTOBUF_NO_RTTI'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-maybe-uninitialized' became -Wno-maybe-uninitialized
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-DGOOGLE_PROTOBUF_NO_RTTI' became -DGOOGLE_PROTOBUF_NO_RTTI
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-maybe-uninitialized")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")

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


add_executable(libaapt2 ${SOURCE_FILES})
