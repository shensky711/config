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
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [7] = '-Iexternal/libcxx/include'
# Raw param [8] = '-Iexternal/libcxxabi/include'
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
# Raw param [0] = '-D_REENTRANT'
# Raw param [1] = '-DU_COMMON_IMPLEMENTATION'
# Raw param [2] = '-O3'
# Raw param [3] = '-fvisibility=hidden'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-Wno-missing-field-initializers'
# Raw param [6] = '-Wno-sign-compare'
# Raw param [7] = '-Wno-deprecated-declarations'
# Raw param [8] = '-DPIC'
# Raw param [9] = '-fPIC'
# Raw param [10] = '-target arm-linux-androideabi'
# Raw param [11] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [12] = '-fPIC'
# Raw param [13] = '-D_USING_LIBCXX'
# FLAG '-D_REENTRANT' became -D_REENTRANT
# FLAG '-DU_COMMON_IMPLEMENTATION' became -DU_COMMON_IMPLEMENTATION
# FLAG '-O3' became -O3
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-DPIC' became -DPIC
# FLAG '-fPIC' became -fPIC
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
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
# Raw param [2] = '-frtti'
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
# FLAG '-frtti' became -frtti
# variable ${config.ArmClangCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -frtti")
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


add_executable(libicuuc ${SOURCE_FILES})
