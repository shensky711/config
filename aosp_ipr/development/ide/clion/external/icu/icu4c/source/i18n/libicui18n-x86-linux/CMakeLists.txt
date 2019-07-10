# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libicui18n)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decContext.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decNumber.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucln_in.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ulocdata.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/utmscale.c
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/affixpatternparser.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/alphaindex.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/anytrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/astro.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/basictz.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/bocsu.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/brktrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/buddhcal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/calendar.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/casetrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/cecal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/chnsecal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/choicfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/coleitr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationbuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationcompare.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collation.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationdatabuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationdata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationdatareader.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationdatawriter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationfastlatinbuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationfastlatin.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationfcd.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationkeys.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationroot.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationrootelements.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationruleparser.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationsets.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationsettings.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationtailoring.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/collationweights.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/coll.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/compactdecimalformat.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/coptccal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/cpdtrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csdetect.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csmatch.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csr2022.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csrecog.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csrmbcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csrsbcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csrucode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/csrutf8.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/curramt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/currfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/currpinf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/currunit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dangical.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/datefmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dayperiodrules.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dcfmtsym.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decfmtst.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decimalformatpattern.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decimfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/decimfmtimpl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitaffix.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitaffixesandpadding.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitgrouping.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitinterval.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/digitlst.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dtfmtsym.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dtitvfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dtitvinf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dtptngen.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/dtrule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/esctrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ethpccal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/fmtable_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/fmtable.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/format.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/fphdlimp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/fpositer.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/funcrepl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/gender.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/gregocal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/gregoimp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/hebrwcal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/indiancal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/inputext.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/islamcal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/japancal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/measfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/measunit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/measure.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/msgfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/name2uni.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/nfrs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/nfrule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/nfsubs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/nortrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/nultrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/numfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/numsys.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/olsontz.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/persncal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/pluralaffix.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/plurfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/plurrule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/precision.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/quant.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/quantityformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbnf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbt_data.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbt_pars.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbt_rule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbt_set.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rbtz.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/regexcmp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/regeximp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/regexst.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/regextxt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/region.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/reldatefmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/reldtfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rematch.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/remtrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/repattrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/rulebasedcollator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/scientificnumberformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/scriptset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/search.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/selfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/sharedbreakiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/simpletz.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/smallintformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/smpdtfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/smpdtfst.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/sortkey.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/standardplural.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/strmatch.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/strrepl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/stsearch.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/taiwncal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/timezone.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/titletrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tmunit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tmutamt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tmutfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tolowtrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/toupptrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/translit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/transreg.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tridpars.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tzfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tzgnames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tznames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tznames_impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tzrule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/tztrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucal.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucol.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucoleitr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucol_res.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucol_sit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ucsdet.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/udat.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/udateintervalformat.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/udatpg.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ufieldpositer.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uitercollationiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/umsg.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/unesctrn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uni2name.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/unum.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/upluralrules.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uregexc.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uregex.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/usearch.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uspoof_build.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uspoof_conf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uspoof.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/uspoof_impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/utf16collationiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/utf8collationiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/utrans.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/valueformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/windtfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/winnmfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/wintzimpl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/visibledigits.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/vtzone.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/vzone.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/zonemeta.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/zrule.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/i18n/ztrans.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [1] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/icu/icu4c/source/common'
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
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
# Raw param [1] = '-DU_I18N_IMPLEMENTATION'
# Raw param [2] = '-O3'
# Raw param [3] = '-fvisibility=hidden'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-target i686-linux-gnu'
# Raw param [6] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [7] = '-fPIC'
# Raw param [8] = '-D_USING_LIBCXX'
# FLAG '-D_REENTRANT' became -D_REENTRANT
# FLAG '-DU_I18N_IMPLEMENTATION' became -DU_I18N_IMPLEMENTATION
# FLAG '-O3' became -O3
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_REENTRANT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_I18N_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_REENTRANT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_I18N_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
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


add_executable(libicui18n ${SOURCE_FILES})
