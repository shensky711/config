# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libext2fs)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/ext2_err.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/alloc.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/alloc_sb.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/alloc_stats.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/alloc_tables.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/atexit.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/badblocks.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/bb_inode.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/bitmaps.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/bitops.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/blkmap64_ba.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/blkmap64_rb.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/blknum.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/block.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/bmap.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/check_desc.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/crc16.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/crc32c.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/csum.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/closefs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dblist.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dblist_dir.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/digest_encode.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dirblock.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dirhash.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dir_iterate.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/dupfs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/expanddir.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/ext_attr.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/extent.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/fallocate.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/fileio.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/finddev.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/flushb.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/freefs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/gen_bitmap.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/gen_bitmap64.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/get_num_dirs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/get_pathname.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/getsize.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/getsectsize.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/i_block.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/icount.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/imager.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/ind_block.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/initialize.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/inline.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/inline_data.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/inode.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/io_manager.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/ismounted.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/link.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/llseek.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/lookup.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/mmp.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/mkdir.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/mkjournal.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/namei.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/native.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/newdir.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/openfs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/progress.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/punch.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/qcow2.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/rbtree.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/read_bb.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/read_bb_file.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/res_gdt.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/rw_bitmaps.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/sha256.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/sha512.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/swapfs.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/symlink.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/undo_io.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/unix_io.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/sparse_io.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/unlink.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/valid_blk.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/version.c
    ${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/test_io.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/e2fsprogs/lib/ext2fs'
# Raw param [1] = '-Iexternal/e2fsprogs/include/mingw'
# Raw param [2] = '-Iexternal/e2fsprogs/lib/ext2fs'
# Raw param [3] = ''
# Raw param [4] = '${config.WindowsCflags} ${config.WindowsX86Cflags}'
# Raw param [5] = '${config.CommonGlobalCflags}'
# Raw param [6] = '${config.HostGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/e2fsprogs/lib'
# Raw param [9] = '-Iexternal/e2fsprogs/lib/et'
# Raw param [10] = '-Isystem/core/libsparse/include'
# Raw param [11] = '-Iexternal/zlib'
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
    "${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs"
    "${ANDROID_ROOT}/external/e2fsprogs/include/mingw"
    "${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs"
    "${ANDROID_ROOT}/external/e2fsprogs/lib"
    "${ANDROID_ROOT}/external/e2fsprogs/lib/et"
    "${ANDROID_ROOT}/system/core/libsparse/include"
    "${ANDROID_ROOT}/external/zlib"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/**/*.h"
    "${ANDROID_ROOT}/external/e2fsprogs/include/mingw/**/*.h"
    "${ANDROID_ROOT}/external/e2fsprogs/lib/ext2fs/**/*.h"
    "${ANDROID_ROOT}/external/e2fsprogs/lib/**/*.h"
    "${ANDROID_ROOT}/external/e2fsprogs/lib/et/**/*.h"
    "${ANDROID_ROOT}/system/core/libsparse/include/**/*.h"
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
# Raw param [0] = '-W'
# Raw param [1] = '-Wall'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-Wno-macro-redefined'
# Raw param [4] = '-Wno-format'
# FLAG '-W' became -W
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-macro-redefined' became -Wno-macro-redefined
# FLAG '-Wno-format' became -Wno-format
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-macro-redefined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-macro-redefined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format")

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


add_executable(libext2fs ${SOURCE_FILES})
