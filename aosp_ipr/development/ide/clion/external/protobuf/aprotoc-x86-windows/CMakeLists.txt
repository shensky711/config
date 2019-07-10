# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(aprotoc)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/any.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/arena.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/arenastring.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor.pb.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor_database.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/dynamic_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/extension_set.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/extension_set_heavy.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/generated_message_reflection.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/generated_message_util.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/message_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/reflection_ops.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/repeated_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/text_format.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/unknown_field_set.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/wire_format.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/wire_format_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/code_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/command_line_interface.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_string_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_doc_comment.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_field_base.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_reflection_class.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_source_generator_base.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_wrapper_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/importer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_context.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_doc_comment.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_extension_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_generator_factory.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_lazy_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_lazy_message_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_map_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_builder.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_builder_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_name_resolver.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_primitive_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_shared_code_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_string_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_string_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/js/js_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/main.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_oneof.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/parser.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/plugin.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/plugin.pb.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/python/python_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/ruby/ruby_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/subprocess.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/zip_writer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/coded_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/gzip_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/printer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/strtod.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/tokenizer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream_impl.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream_impl_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/atomicops_internals_x86_gcc.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/atomicops_internals_x86_msvc.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/common.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/int128.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/once.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/status.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/stringpiece.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/structurally_valid.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/strutil.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/substitute.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/stringprintf.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/protobuf/android -Iexternal/protobuf/src'
# Raw param [1] = '-Iexternal/protobuf'
# Raw param [2] = ''
# Raw param [3] = '${config.WindowsCflags} ${config.WindowsX86Cflags}'
# Raw param [4] = '${config.CommonGlobalCflags}'
# Raw param [5] = '${config.HostGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/zlib'
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
    "${ANDROID_ROOT}/external/protobuf/android -Iexternal/protobuf/src"
    "${ANDROID_ROOT}/external/protobuf"
    "${ANDROID_ROOT}/external/zlib"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/protobuf/android -Iexternal/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
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
# Raw param [0] = '-Wno-sign-compare'
# Raw param [1] = '-Wno-unused-parameter'
# Raw param [2] = '-Wno-sign-promo'
# Raw param [3] = '-Wno-error=return-type'
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-Wno-error=return-type' became -Wno-error=return-type
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-promo")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=return-type")

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
# Raw param [2] = ''
# FLAG '-std=gnu++11' became -std=gnu++11
# variable ${config.CommonGlobalCppflags} = '-Wsign-promo'
# Raw param [0] = '-Wsign-promo'
# FLAG '-Wsign-promo' became -Wsign-promo
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")

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


add_executable(aprotoc ${SOURCE_FILES})
