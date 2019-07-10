# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libicuuc)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cmemory.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cstring.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cstr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cwchar.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/filteredbrk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/icuplug.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/loadednormalizer2impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locdspnm.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locmap.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/pluralmap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/propsvec.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/punycode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/putil.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resource.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/sharedobject.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/simpleformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uarrsort.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidi.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidiln.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidi_props.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubiditransform.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidiwrt.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucase.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucasemap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucat.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uchar.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucln_cmn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucmndata.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv2022.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_bld.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvbocu.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_cb.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_cnv.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_ct.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvdisp.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_err.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_ext.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvhz.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_io.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvisci.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvlat1.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_lmb.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvmbcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvscsu.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_set.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u16.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u32.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u7.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u8.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucurr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udatamem.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udataswp.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uenum.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uhash.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uinit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uinvchar.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ulist.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ulistformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc_keytype.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc_tag.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umapfile.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umath.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umutex.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uresbund.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ures_cnv.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uresdata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usc_impl.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uscript.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uscript_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ushape.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrcase.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrfmt.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustring.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrtrns.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_wcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utf_impl.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrace.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie2_builder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utypes.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/wintz.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/appendable.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bmpset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/brkeng.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestream.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestrieiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/caniter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/chariter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/charstr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dictbe.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dictionarydata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dtintrv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/errorcode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/filterednormalizer2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/listformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locavailable.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locbased.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locdispnames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locid.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/loclikely.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locresdata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locutil.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/messagepattern.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normalizer2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normalizer2impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normlzr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/parsepos.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/patternprops.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/propname.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbi.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbidata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbinode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbirb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbiscan.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbisetb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbistbl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbitblb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resbund_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resbund.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ruleiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/schriter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/serv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servlk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servlkf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servls.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servnotf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servrbf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servslkf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/stringpiece.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/stringtriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubrk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucasemap_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstrieiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uchriter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvsel.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucol_swp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uhash_us.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uidna.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifiedcache.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifilt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifunct.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset_closure.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unisetspan.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_case.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_case_locale.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unormcmp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unorm.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uobject.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uprops.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usetiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uset_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usprep.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustack.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrcase_locale.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrenum.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utext.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/util.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/util_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uts46.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvector.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvectr32.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvectr64.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/icu/icu4c/source/common'
# Raw param [1] = '-Iexternal/icu/icu4c/source/common'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/libcxx/include'
# Raw param [8] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
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
# Raw param [0] = '-D_REENTRANT'
# Raw param [1] = '-DU_COMMON_IMPLEMENTATION'
# Raw param [2] = '-O3'
# Raw param [3] = '-fvisibility=hidden'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-Wno-missing-field-initializers'
# Raw param [6] = '-Wno-sign-compare'
# Raw param [7] = '-Wno-deprecated-declarations'
# Raw param [8] = '-target i686-linux-gnu'
# Raw param [9] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [10] = '-fPIC'
# Raw param [11] = '-D_USING_LIBCXX'
# FLAG '-D_REENTRANT' became -D_REENTRANT
# FLAG '-DU_COMMON_IMPLEMENTATION' became -DU_COMMON_IMPLEMENTATION
# FLAG '-O3' became -O3
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_REENTRANT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_COMMON_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_REENTRANT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_COMMON_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
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


add_executable(libicuuc ${SOURCE_FILES})
