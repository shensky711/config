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
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/icu/icu4c/source/common'
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
# variable ${config.Arm64ClangCflags} = '-fno-exceptions -Wno-multichar -fno-strict-aliasing -fstack-protector-strong -ffunction-sections -fdata-sections -funwind-tables -Wa,--noexecstack -Werror=format-security -D_FORTIFY_SOURCE=2 -fno-short-enums -no-canonical-prefixes -Werror=pointer-to-int-cast -Werror=int-to-pointer-cast -Werror=implicit-function-declaration -DNDEBUG -O2 -g -Wstrict-aliasing=2'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-fno-strict-aliasing'
# Raw param [3] = '-fstack-protector-strong'
# Raw param [4] = '-ffunction-sections'
# Raw param [5] = '-fdata-sections'
# Raw param [6] = '-funwind-tables'
# Raw param [7] = '-Wa,--noexecstack'
# Raw param [8] = '-Werror=format-security'
# Raw param [9] = '-D_FORTIFY_SOURCE=2'
# Raw param [10] = '-fno-short-enums'
# Raw param [11] = '-no-canonical-prefixes'
# Raw param [12] = '-Werror=pointer-to-int-cast'
# Raw param [13] = '-Werror=int-to-pointer-cast'
# Raw param [14] = '-Werror=implicit-function-declaration'
# Raw param [15] = '-DNDEBUG'
# Raw param [16] = '-O2'
# Raw param [17] = '-g'
# Raw param [18] = '-Wstrict-aliasing=2'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-Werror=pointer-to-int-cast' became -Werror=pointer-to-int-cast
# FLAG '-Werror=int-to-pointer-cast' became -Werror=int-to-pointer-cast
# FLAG '-Werror=implicit-function-declaration' became -Werror=implicit-function-declaration
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-O2' became -O2
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=implicit-function-declaration")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
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

# CFLAGS:
# Raw param [0] = '-D_REENTRANT'
# Raw param [1] = '-DU_I18N_IMPLEMENTATION'
# Raw param [2] = '-O3'
# Raw param [3] = '-fvisibility=hidden'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-DPIC'
# Raw param [6] = '-fPIC'
# Raw param [7] = '-target aarch64-linux-android'
# Raw param [8] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [9] = '-fPIC'
# Raw param [10] = '-D_USING_LIBCXX'
# FLAG '-D_REENTRANT' became -D_REENTRANT
# FLAG '-DU_I18N_IMPLEMENTATION' became -DU_I18N_IMPLEMENTATION
# FLAG '-O3' became -O3
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DPIC' became -DPIC
# FLAG '-fPIC' became -fPIC
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_REENTRANT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_I18N_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_REENTRANT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_I18N_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
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
# Raw param [3] = '${config.Arm64ClangCppflags}'
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
# variable ${config.Arm64ClangCppflags} = '-fvisibility-inlines-hidden'
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
# Raw param [1] = '${config.Arm64IncludeFlags}'
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
# variable ${config.Arm64IncludeFlags} = '-isystem bionic/libc/arch-arm64/include -isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm64 -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/arch-arm64/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/include'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/uapi/asm-arm64'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/scsi'
# Raw param [10] = '-isystem'
# Raw param [11] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/arch-arm64/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64/**/*.h"
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


add_executable(libicui18n ${SOURCE_FILES})
