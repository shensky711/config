# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libc_openbsd_ndk)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/compat-43/killpg.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/alarm.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/ctype_.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/daemon.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/err.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/errx.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/fnmatch.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/ftok.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/getprogname.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/isctype.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/setprogname.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/time.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/tolower_.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/toupper_.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/verr.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/verrx.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/vwarn.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/vwarnx.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/warn.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/gen/warnx.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/btowc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/mbrlen.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/mbstowcs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/mbtowc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcscoll.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstoimax.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstol.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstoll.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstombs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstoul.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstoull.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcstoumax.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wcsxfrm.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wctob.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/locale/wctomb.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/base64.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/htonl.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/htons.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_lnaof.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_makeaddr.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_netof.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_ntoa.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_ntop.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/inet_pton.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/ntohl.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/ntohs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/net/res_random.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fflush.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fgetln.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fgets.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fgetwc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fgetws.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/flags.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fmemopen.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fpurge.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fputs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fputwc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fputws.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fvwrite.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fwalk.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fwide.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/fwrite.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/getdelim.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/gets.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/makebuf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/mktemp.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/open_memstream.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/open_wmemstream.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/perror.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/puts.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/rget.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/setvbuf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/tempnam.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/tmpnam.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/ungetc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/ungetwc.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/vasprintf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/vdprintf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/vsscanf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/vswprintf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/vswscanf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/wbuf.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdio/wsetup.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/abs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/atoi.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/atol.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/atoll.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/getenv.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/getsubopt.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/insque.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/imaxabs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/imaxdiv.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/labs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/llabs.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/lsearch.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/reallocarray.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/remque.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/setenv.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtoimax.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtol.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtoll.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtoul.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtoull.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/strtoumax.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/system.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/tfind.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/stdlib/tsearch.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strcasecmp.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strcspn.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strdup.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strndup.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strpbrk.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strsep.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strspn.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strstr.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/strtok.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/wmemcpy.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/wcslcpy.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/wcsstr.c
    ${ANDROID_ROOT}/bionic/libc/upstream-openbsd/lib/libc/string/wcswidth.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ibionic/libc/private -Ibionic/libc/stdio -Ibionic/libc/upstream-openbsd/android/include -Ibionic/libc/upstream-openbsd/lib/libc/include -Ibionic/libc/upstream-openbsd/lib/libc/gdtoa'
# Raw param [1] = '-Ibionic/libc/async_safe/include -Iexternal/jemalloc/include'
# Raw param [2] = '-Ibionic/libc'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
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
    "${ANDROID_ROOT}/bionic/libc/private -Ibionic/libc/stdio -Ibionic/libc/upstream-openbsd/android/include -Ibionic/libc/upstream-openbsd/lib/libc/include -Ibionic/libc/upstream-openbsd/lib/libc/gdtoa"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include -Iexternal/jemalloc/include"
    "${ANDROID_ROOT}/bionic/libc"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/private -Ibionic/libc/stdio -Ibionic/libc/upstream-openbsd/android/include -Ibionic/libc/upstream-openbsd/lib/libc/include -Ibionic/libc/upstream-openbsd/lib/libc/gdtoa/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include -Iexternal/jemalloc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/**/*.h"
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
# Raw param [0] = '-D_LIBC=1'
# Raw param [1] = '-Wall'
# Raw param [2] = '-Wextra'
# Raw param [3] = '-Wunused'
# Raw param [4] = '-Wno-deprecated-declarations'
# Raw param [5] = '-Wframe-larger-than=2048'
# Raw param [6] = '-Werror=pointer-to-int-cast'
# Raw param [7] = '-Werror=int-to-pointer-cast'
# Raw param [8] = '-Werror=type-limits'
# Raw param [9] = '-Werror'
# Raw param [10] = '-Wno-sign-compare'
# Raw param [11] = '-Wno-uninitialized'
# Raw param [12] = '-Wno-unused-parameter'
# Raw param [13] = '-include openbsd-compat.h'
# Raw param [14] = '-target arm-linux-androideabi'
# Raw param [15] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [16] = '-DANDROID_STRICT'
# Raw param [17] = '-fPIC'
# FLAG '-D_LIBC=1' became -D_LIBC=1
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Wunused' became -Wunused
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wframe-larger-than=2048' became -Wframe-larger-than=2048
# FLAG '-Werror=pointer-to-int-cast' became -Werror=pointer-to-int-cast
# FLAG '-Werror=int-to-pointer-cast' became -Werror=int-to-pointer-cast
# FLAG '-Werror=type-limits' became -Werror=type-limits
# FLAG '-Werror' became -Werror
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-uninitialized' became -Wno-uninitialized
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-include openbsd-compat.h' became -include openbsd-compat.h
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LIBC=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=2048")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=type-limits")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-uninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -include openbsd-compat.h")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBC=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=2048")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=type-limits")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-uninitialized")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -include openbsd-compat.h")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# Raw param [2] = '-std=gnu99'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
# FLAG '-std=gnu99' became -std=gnu99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")
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


add_executable(libc_openbsd_ndk ${SOURCE_FILES})
