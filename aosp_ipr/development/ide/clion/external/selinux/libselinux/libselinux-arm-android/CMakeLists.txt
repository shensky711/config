# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libselinux)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/selinux/libselinux/src/booleans.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/callbacks.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/freecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/label_backends_android.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/label.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/label_support.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/matchpathcon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/setrans_client.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/sha1.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/label_file.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/regex.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/android/android.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/avc.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/avc_internal.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/avc_sidtab.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/canonicalize_context.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/checkAccess.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/check_context.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/compute_av.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/compute_create.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/compute_member.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/context.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/deny_unknown.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/disable.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/enabled.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/fgetfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/fsetfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/getenforce.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/getfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/get_initial_context.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/getpeercon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/init.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/lgetfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/load_policy.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/lsetfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/mapping.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/policyvers.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/procattr.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/sestatus.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/setenforce.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/setfilecon.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/stringrep.c
    ${ANDROID_ROOT}/external/selinux/libselinux/src/android/android_platform.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/selinux/libselinux/include'
# Raw param [1] = '-Iexternal/selinux/libselinux/src -Iexternal/selinux/libselinux/include'
# Raw param [2] = '-Iexternal/selinux/libselinux'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [8] = '-Iexternal/pcre/include'
# Raw param [9] = '-Isystem/core/libpackagelistparser/include'
# Raw param [10] = '-Iexternal/libcxx/include'
# Raw param [11] = '-Iexternal/libcxxabi/include'
# Raw param [12] = '-Iexternal/boringssl/src/include'
# Raw param [13] = '-Isystem/core/liblog/include'
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
include_directories( 
    "${ANDROID_ROOT}/external/selinux/libselinux/include"
    "${ANDROID_ROOT}/external/selinux/libselinux/src -Iexternal/selinux/libselinux/include"
    "${ANDROID_ROOT}/external/selinux/libselinux"
    "${ANDROID_ROOT}/external/pcre/include"
    "${ANDROID_ROOT}/system/core/libpackagelistparser/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/selinux/libselinux/include/**/*.h"
    "${ANDROID_ROOT}/external/selinux/libselinux/src -Iexternal/selinux/libselinux/include/**/*.h"
    "${ANDROID_ROOT}/external/selinux/libselinux/**/*.h"
    "${ANDROID_ROOT}/external/pcre/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libpackagelistparser/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

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
# Raw param [0] = '-DNO_PERSISTENTLY_STORED_PATTERNS'
# Raw param [1] = '-DDISABLE_SETRANS'
# Raw param [2] = '-DDISABLE_BOOL'
# Raw param [3] = '-D_GNU_SOURCE'
# Raw param [4] = '-DNO_MEDIA_BACKEND'
# Raw param [5] = '-DNO_X_BACKEND'
# Raw param [6] = '-DNO_DB_BACKEND'
# Raw param [7] = '-DUSE_PCRE2'
# Raw param [8] = '-DAUDITD_LOG_TAG=1003'
# Raw param [9] = '-DFULL_TREBLE'
# Raw param [10] = '-Wno-pointer-bool-conversion'
# Raw param [11] = '-target arm-linux-androideabi'
# Raw param [12] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [13] = '-fPIC'
# Raw param [14] = '-D_USING_LIBCXX'
# FLAG '-DNO_PERSISTENTLY_STORED_PATTERNS' became -DNO_PERSISTENTLY_STORED_PATTERNS
# FLAG '-DDISABLE_SETRANS' became -DDISABLE_SETRANS
# FLAG '-DDISABLE_BOOL' became -DDISABLE_BOOL
# FLAG '-D_GNU_SOURCE' became -D_GNU_SOURCE
# FLAG '-DNO_MEDIA_BACKEND' became -DNO_MEDIA_BACKEND
# FLAG '-DNO_X_BACKEND' became -DNO_X_BACKEND
# FLAG '-DNO_DB_BACKEND' became -DNO_DB_BACKEND
# FLAG '-DUSE_PCRE2' became -DUSE_PCRE2
# FLAG '-DAUDITD_LOG_TAG=1003' became -DAUDITD_LOG_TAG=1003
# FLAG '-DFULL_TREBLE' became -DFULL_TREBLE
# FLAG '-Wno-pointer-bool-conversion' became -Wno-pointer-bool-conversion
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_PERSISTENTLY_STORED_PATTERNS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_SETRANS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_BOOL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_MEDIA_BACKEND")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_X_BACKEND")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_DB_BACKEND")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_PCRE2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DAUDITD_LOG_TAG=1003")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DFULL_TREBLE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-pointer-bool-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_PERSISTENTLY_STORED_PATTERNS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_SETRANS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_BOOL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_MEDIA_BACKEND")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_X_BACKEND")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_DB_BACKEND")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_PCRE2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DAUDITD_LOG_TAG=1003")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DFULL_TREBLE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-pointer-bool-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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
# Raw param [2] = '-fno-rtti'
# Raw param [3] = '${config.ArmClangCppflags}'
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
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.ArmIncludeFlags}'
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
# variable ${config.ArmIncludeFlags} = '-isystem bionic/libc/arch-arm/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/arch-arm/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/include'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/uapi/asm-arm'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/scsi'
# Raw param [10] = '-isystem'
# Raw param [11] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm/**/*.h"
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


add_executable(libselinux ${SOURCE_FILES})
