# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcurl)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/curl/lib/rand.c
    ${ANDROID_ROOT}/external/curl/lib/file.c
    ${ANDROID_ROOT}/external/curl/lib/timeval.c
    ${ANDROID_ROOT}/external/curl/lib/base64.c
    ${ANDROID_ROOT}/external/curl/lib/hostip.c
    ${ANDROID_ROOT}/external/curl/lib/progress.c
    ${ANDROID_ROOT}/external/curl/lib/formdata.c
    ${ANDROID_ROOT}/external/curl/lib/cookie.c
    ${ANDROID_ROOT}/external/curl/lib/http.c
    ${ANDROID_ROOT}/external/curl/lib/sendf.c
    ${ANDROID_ROOT}/external/curl/lib/ftp.c
    ${ANDROID_ROOT}/external/curl/lib/url.c
    ${ANDROID_ROOT}/external/curl/lib/dict.c
    ${ANDROID_ROOT}/external/curl/lib/if2ip.c
    ${ANDROID_ROOT}/external/curl/lib/speedcheck.c
    ${ANDROID_ROOT}/external/curl/lib/ldap.c
    ${ANDROID_ROOT}/external/curl/lib/version.c
    ${ANDROID_ROOT}/external/curl/lib/getenv.c
    ${ANDROID_ROOT}/external/curl/lib/escape.c
    ${ANDROID_ROOT}/external/curl/lib/mprintf.c
    ${ANDROID_ROOT}/external/curl/lib/telnet.c
    ${ANDROID_ROOT}/external/curl/lib/netrc.c
    ${ANDROID_ROOT}/external/curl/lib/getinfo.c
    ${ANDROID_ROOT}/external/curl/lib/transfer.c
    ${ANDROID_ROOT}/external/curl/lib/easy.c
    ${ANDROID_ROOT}/external/curl/lib/security.c
    ${ANDROID_ROOT}/external/curl/lib/curl_fnmatch.c
    ${ANDROID_ROOT}/external/curl/lib/fileinfo.c
    ${ANDROID_ROOT}/external/curl/lib/ftplistparser.c
    ${ANDROID_ROOT}/external/curl/lib/wildcard.c
    ${ANDROID_ROOT}/external/curl/lib/krb5.c
    ${ANDROID_ROOT}/external/curl/lib/memdebug.c
    ${ANDROID_ROOT}/external/curl/lib/http_chunks.c
    ${ANDROID_ROOT}/external/curl/lib/strtok.c
    ${ANDROID_ROOT}/external/curl/lib/connect.c
    ${ANDROID_ROOT}/external/curl/lib/llist.c
    ${ANDROID_ROOT}/external/curl/lib/hash.c
    ${ANDROID_ROOT}/external/curl/lib/multi.c
    ${ANDROID_ROOT}/external/curl/lib/content_encoding.c
    ${ANDROID_ROOT}/external/curl/lib/share.c
    ${ANDROID_ROOT}/external/curl/lib/http_digest.c
    ${ANDROID_ROOT}/external/curl/lib/md4.c
    ${ANDROID_ROOT}/external/curl/lib/md5.c
    ${ANDROID_ROOT}/external/curl/lib/http_negotiate.c
    ${ANDROID_ROOT}/external/curl/lib/inet_pton.c
    ${ANDROID_ROOT}/external/curl/lib/strtoofft.c
    ${ANDROID_ROOT}/external/curl/lib/strerror.c
    ${ANDROID_ROOT}/external/curl/lib/amigaos.c
    ${ANDROID_ROOT}/external/curl/lib/hostasyn.c
    ${ANDROID_ROOT}/external/curl/lib/hostip4.c
    ${ANDROID_ROOT}/external/curl/lib/hostip6.c
    ${ANDROID_ROOT}/external/curl/lib/hostsyn.c
    ${ANDROID_ROOT}/external/curl/lib/inet_ntop.c
    ${ANDROID_ROOT}/external/curl/lib/parsedate.c
    ${ANDROID_ROOT}/external/curl/lib/select.c
    ${ANDROID_ROOT}/external/curl/lib/tftp.c
    ${ANDROID_ROOT}/external/curl/lib/splay.c
    ${ANDROID_ROOT}/external/curl/lib/strcase.c
    ${ANDROID_ROOT}/external/curl/lib/strdup.c
    ${ANDROID_ROOT}/external/curl/lib/socks.c
    ${ANDROID_ROOT}/external/curl/lib/ssh.c
    ${ANDROID_ROOT}/external/curl/lib/curl_addrinfo.c
    ${ANDROID_ROOT}/external/curl/lib/socks_gssapi.c
    ${ANDROID_ROOT}/external/curl/lib/socks_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/curl_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/slist.c
    ${ANDROID_ROOT}/external/curl/lib/nonblock.c
    ${ANDROID_ROOT}/external/curl/lib/curl_memrchr.c
    ${ANDROID_ROOT}/external/curl/lib/imap.c
    ${ANDROID_ROOT}/external/curl/lib/pop3.c
    ${ANDROID_ROOT}/external/curl/lib/smtp.c
    ${ANDROID_ROOT}/external/curl/lib/pingpong.c
    ${ANDROID_ROOT}/external/curl/lib/rtsp.c
    ${ANDROID_ROOT}/external/curl/lib/curl_threads.c
    ${ANDROID_ROOT}/external/curl/lib/warnless.c
    ${ANDROID_ROOT}/external/curl/lib/hmac.c
    ${ANDROID_ROOT}/external/curl/lib/curl_rtmp.c
    ${ANDROID_ROOT}/external/curl/lib/openldap.c
    ${ANDROID_ROOT}/external/curl/lib/curl_gethostname.c
    ${ANDROID_ROOT}/external/curl/lib/gopher.c
    ${ANDROID_ROOT}/external/curl/lib/idn_win32.c
    ${ANDROID_ROOT}/external/curl/lib/http_proxy.c
    ${ANDROID_ROOT}/external/curl/lib/non-ascii.c
    ${ANDROID_ROOT}/external/curl/lib/asyn-ares.c
    ${ANDROID_ROOT}/external/curl/lib/asyn-thread.c
    ${ANDROID_ROOT}/external/curl/lib/curl_gssapi.c
    ${ANDROID_ROOT}/external/curl/lib/http_ntlm.c
    ${ANDROID_ROOT}/external/curl/lib/curl_ntlm_wb.c
    ${ANDROID_ROOT}/external/curl/lib/curl_ntlm_core.c
    ${ANDROID_ROOT}/external/curl/lib/curl_sasl.c
    ${ANDROID_ROOT}/external/curl/lib/curl_multibyte.c
    ${ANDROID_ROOT}/external/curl/lib/hostcheck.c
    ${ANDROID_ROOT}/external/curl/lib/conncache.c
    ${ANDROID_ROOT}/external/curl/lib/pipeline.c
    ${ANDROID_ROOT}/external/curl/lib/dotdot.c
    ${ANDROID_ROOT}/external/curl/lib/x509asn1.c
    ${ANDROID_ROOT}/external/curl/lib/http2.c
    ${ANDROID_ROOT}/external/curl/lib/smb.c
    ${ANDROID_ROOT}/external/curl/lib/curl_endian.c
    ${ANDROID_ROOT}/external/curl/lib/curl_des.c
    ${ANDROID_ROOT}/external/curl/lib/system_win32.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/vauth.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/cleartext.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/cram.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/digest.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/digest_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/krb5_gssapi.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/krb5_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/ntlm.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/ntlm_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/oauth2.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/spnego_gssapi.c
    ${ANDROID_ROOT}/external/curl/lib/vauth/spnego_sspi.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/openssl.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/gtls.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/vtls.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/nss.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/polarssl.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/polarssl_threadlock.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/axtls.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/cyassl.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/schannel.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/darwinssl.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/gskit.c
    ${ANDROID_ROOT}/external/curl/lib/vtls/mbedtls.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/curl/include'
# Raw param [1] = '-Iexternal/curl/include -Iexternal/curl/lib'
# Raw param [2] = '-Iexternal/curl'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/boringssl/src/include'
# Raw param [9] = '-Iexternal/zlib'
# Raw param [10] = '-Iexternal/libcxx/include'
# Raw param [11] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX86ClangCflags} = '-fno-exceptions -Wno-multichar -Wa,--noexecstack -fPIC -no-canonical-prefixes -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -O2 -g -fno-strict-aliasing --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot -fstack-protector-strong -msse3 -m32 -march=prescott -D_FILE_OFFSET_BITS=64 -D_LARGEFILE_SOURCE=1'
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
# Raw param [17] = '-msse3'
# Raw param [18] = '-m32'
# Raw param [19] = '-march=prescott'
# Raw param [20] = '-D_FILE_OFFSET_BITS=64'
# Raw param [21] = '-D_LARGEFILE_SOURCE=1'
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
# FLAG '-msse3' became -msse3
# FLAG '-m32' became -m32
# FLAG '-march=prescott' became -march=prescott
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
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
    "${ANDROID_ROOT}/external/curl/include"
    "${ANDROID_ROOT}/external/curl/include -Iexternal/curl/lib"
    "${ANDROID_ROOT}/external/curl"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/curl/include/**/*.h"
    "${ANDROID_ROOT}/external/curl/include -Iexternal/curl/lib/**/*.h"
    "${ANDROID_ROOT}/external/curl/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=prescott")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=prescott")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
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
# Raw param [0] = '-Wpointer-arith'
# Raw param [1] = '-Wwrite-strings'
# Raw param [2] = '-Wunused'
# Raw param [3] = '-Winline'
# Raw param [4] = '-Wnested-externs'
# Raw param [5] = '-Wmissing-declarations'
# Raw param [6] = '-Wmissing-prototypes'
# Raw param [7] = '-Wno-long-long'
# Raw param [8] = '-Wfloat-equal'
# Raw param [9] = '-Wno-multichar'
# Raw param [10] = '-Wno-sign-compare'
# Raw param [11] = '-Wno-format-nonliteral'
# Raw param [12] = '-Wendif-labels'
# Raw param [13] = '-Wstrict-prototypes'
# Raw param [14] = '-Wdeclaration-after-statement'
# Raw param [15] = '-Wno-system-headers'
# Raw param [16] = '-DHAVE_CONFIG_H'
# Raw param [17] = ''-DOS="Android"''
# Raw param [18] = '-Werror'
# Raw param [19] = '-Wno-varargs'
# Raw param [20] = '-DBUILDING_LIBCURL'
# Raw param [21] = '-D_GNU_SOURCE=1'
# Raw param [22] = '-target i686-linux-gnu'
# Raw param [23] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [24] = '-fPIC'
# Raw param [25] = '-D_USING_LIBCXX'
# FLAG '-Wpointer-arith' became -Wpointer-arith
# FLAG '-Wwrite-strings' became -Wwrite-strings
# FLAG '-Wunused' became -Wunused
# FLAG '-Winline' became -Winline
# FLAG '-Wnested-externs' became -Wnested-externs
# FLAG '-Wmissing-declarations' became -Wmissing-declarations
# FLAG '-Wmissing-prototypes' became -Wmissing-prototypes
# FLAG '-Wno-long-long' became -Wno-long-long
# FLAG '-Wfloat-equal' became -Wfloat-equal
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-format-nonliteral' became -Wno-format-nonliteral
# FLAG '-Wendif-labels' became -Wendif-labels
# FLAG '-Wstrict-prototypes' became -Wstrict-prototypes
# FLAG '-Wdeclaration-after-statement' became -Wdeclaration-after-statement
# FLAG '-Wno-system-headers' became -Wno-system-headers
# FLAG '-DHAVE_CONFIG_H' became -DHAVE_CONFIG_H
# FLAG ''-DOS="Android"'' became -DOS=\\\"Android\\\"
# FLAG '-Werror' became -Werror
# FLAG '-Wno-varargs' became -Wno-varargs
# FLAG '-DBUILDING_LIBCURL' became -DBUILDING_LIBCURL
# FLAG '-D_GNU_SOURCE=1' became -D_GNU_SOURCE=1
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wwrite-strings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winline")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wnested-externs")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-prototypes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-long-long")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wfloat-equal")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-nonliteral")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wendif-labels")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wstrict-prototypes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wdeclaration-after-statement")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-system-headers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_CONFIG_H")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOS=\\\"Android\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-varargs")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILDING_LIBCURL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wwrite-strings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winline")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wnested-externs")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-prototypes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-long-long")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wfloat-equal")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-nonliteral")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wendif-labels")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wstrict-prototypes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wdeclaration-after-statement")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-system-headers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_CONFIG_H")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOS=\\\"Android\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-varargs")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILDING_LIBCURL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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
# Raw param [2] = '${config.LinuxClangCppflags} ${config.LinuxX86ClangCppflags}'
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
# variable ${config.LinuxClangCppflags} ${config.LinuxX86ClangCppflags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8 -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward'
# Raw param [4] = '-isystem'
# Raw param [5] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32'
# FLAG '-nostdinc++' became -nostdinc++
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32/**/*.h"
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


add_executable(libcurl ${SOURCE_FILES})
