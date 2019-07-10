# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(fingerprint.syna)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/synaFpHal.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/synaFpImpl.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/synaFpVfm.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/shared/synaFpExtensions.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu/custFpHal.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu/custFpImpl.cpp
    ${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu/custFpTest.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/shared -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/authenticator/sapAdrHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/common/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_extensions/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/vfmCore/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/external/AOSP'
# Raw param [1] = '-Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Isystem/core/liblog/include'
# Raw param [8] = '-Isystem/core/libcutils/include'
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/shared -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/authenticator/sapAdrHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/common/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_extensions/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/vfmCore/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/external/AOSP"
    "${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/src/custom/meizu -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseWrappers/androidFpHal/shared -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/authenticator/sapAdrHal/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/common/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_extensions/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/niseCore/vfmCore/include -Ivendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/fp_common/external/AOSP/**/*.h"
    "${ANDROID_ROOT}/vendor/qcom/proprietary/securemsm/fingerprint/synaptics/src_ree/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
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
# Raw param [0] = '-llog'
# Raw param [1] = '-Wno-format-security'
# Raw param [2] = '-Wunused-parameter'
# Raw param [3] = '-Wunused'
# Raw param [4] = '-fexceptions'
# Raw param [5] = '-Wno-error=date-time '
# Raw param [6] = '-Wmissing-braces'
# Raw param [7] = ''-DBUILD_WITH_NDK="1"''
# Raw param [8] = '-DVCS_OS_LINUX'
# Raw param [9] = '-DVCS_OS_ANDROID'
# Raw param [10] = '-DSTRICT'
# Raw param [11] = '-D_MBCS'
# Raw param [12] = '-DSYNA_FP_IST'
# Raw param [13] = '-DVCS_OS_TZ_QSEE'
# Raw param [14] = ''-DCUST_H="custnakaanaaa.h"''
# Raw param [15] = '-DVCS_FEATURES_DEFINED=1'
# Raw param [16] = '-DDLOG_PALRUNTIME_DEFFLAGS=0xFFFFFFFF'
# Raw param [17] = '-DDLOG_PALRUNTIME_DEFLEVEL=1'
# Raw param [18] = '-DDLOG_PALCRYPTO_DEFFLAGS=0xFFFFFFFF'
# Raw param [19] = '-DDLOG_PALCRYPTO_DEFLEVEL=1'
# Raw param [20] = '-DDLOG_PALSENSOR_DEFFLAGS=0xFFFFFFFF'
# Raw param [21] = '-DDLOG_PALSENSOR_DEFLEVEL=1'
# Raw param [22] = '-DDLOG_PALUTIL_DEFFLAGS=0xFFFFFFFF'
# Raw param [23] = '-DDLOG_PALUTIL_DEFLEVEL=1'
# Raw param [24] = '-DDLOG_SSI_DEFFLAGS=0xFFFFFFFF'
# Raw param [25] = '-DDLOG_SSI_DEFLEVEL=1'
# Raw param [26] = '-DDLOG_SMI_DEFFLAGS=0xFFFFFFFF'
# Raw param [27] = '-DDLOG_SMI_DEFLEVEL=1'
# Raw param [28] = '-DDLOG_STI_DEFFLAGS=0xFFFFFFFF'
# Raw param [29] = '-DDLOG_STI_DEFLEVEL=1'
# Raw param [30] = '-DDLOG_VFM_DEFFLAGS=0xFFFFFFFF'
# Raw param [31] = '-DDLOG_VFM_DEFLEVEL=1'
# Raw param [32] = '-DDLOG_VTP_DLL_DEFFLAGS=0xFFFFFFFF'
# Raw param [33] = '-DDLOG_VTP_DLL_DEFLEVEL=1'
# Raw param [34] = '-DDLOG_AUTH_DEFFLAGS=0xFFFFFFFF'
# Raw param [35] = '-DDLOG_AUTH_DEFLEVEL=1'
# Raw param [36] = ''-DVFM_TRANSPORT_SECURE_FP_ID="libvfmtztransport.so"''
# Raw param [37] = '-DVFM_AVAILABLE_MEM_FOR_TPL_LIST=0x00200000'
# Raw param [38] = '-DNISE_FEATURE_ADR_HAL_NON_TZ=0'
# Raw param [39] = '-DCHECK_FOR_DUPLICATE_ENROLLMENT=1'
# Raw param [40] = '-DQM_MIN_ENROLL_VIEWS=20'
# Raw param [41] = '-DQM_INVALID_PARAM_VAL=0xFFFFFF'
# Raw param [42] = '-DCHECK_FU_BEFORE_NAV_START=1'
# Raw param [43] = '-DSYNAFP_KEY_EVENT_FINGER_DETECTED=0x230'
# Raw param [44] = '-DSYNAFP_KEY_EVENT_FINGER_REMOVED=0x231'
# Raw param [45] = '-DSYNAFP_KEY_EVENT_FINGER_RESTED=0x232'
# Raw param [46] = '-DSYNAFP_KEY_EVENT_FINGER_LONGPRESS=0x8B'
# Raw param [47] = '-DSYNAFP_KEY_EVENT_DPAD_RIGHT=0x6A'
# Raw param [48] = '-DSYNAFP_KEY_EVENT_DPAD_LEFT=0x69'
# Raw param [49] = '-DSYNAFP_KEY_EVENT_DPAD_DOWN=0x6C'
# Raw param [50] = '-DSYNAFP_KEY_EVENT_DPAD_UP=0x67'
# Raw param [51] = '-DSYNAFP_KEY_EVENT_CLICK=0x1C'
# Raw param [52] = '-DSYNAFP_KEY_EVENT_FINGER_DTAP=0x239'
# Raw param [53] = '-DSYNAFP_NO_STIMULUS_SCRIPT_ID=10101'
# Raw param [54] = '-DSYNAFP_STIMULUS_SCRIPT_ID=10102'
# Raw param [55] = '-DSYNAFP_SHUTDOWN_SCRIPT_ID=6666'
# Raw param [56] = '-DSYNAFP_IDENTIFY_RETRY_COUNT=0xFFFFFFFF'
# Raw param [57] = '-DQM_ENROLL_VIEWS=20'
# Raw param [58] = '-DQM_DYNAMIC_REDUNDANCY_CHECK'
# Raw param [59] = '-DQM_DYNAMIC_REDUNDANCY_CHECK_START=5'
# Raw param [60] = '-DQM_DYNAMIC_REDUNDANCY_CHECK_END=12'
# Raw param [61] = '-DQM_REDUNDANCY_LEVEL=3'
# Raw param [62] = '-DQM_MAX_REDUNDANCY_IMAGES=8'
# Raw param [63] = '-DANDROID_VERSION=8'
# Raw param [64] = '-DFRAMEWORK_BASED_FINGERUP=1'
# Raw param [65] = '-DSYNAFP_CHECK_3GPIO_POLICY=0'
# Raw param [66] = '-DSYNA_USE_ONLY_NOGPIO=1'
# Raw param [67] = '-DUSE_DYN_LOG_LEVEL'
# Raw param [68] = '-target aarch64-linux-android'
# Raw param [69] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [70] = '-DANDROID_STRICT'
# Raw param [71] = '-fPIC'
# Raw param [72] = '-D_USING_LIBCXX'
# FLAG '-llog' became -llog
# FLAG '-Wno-format-security' became -Wno-format-security
# FLAG '-Wunused-parameter' became -Wunused-parameter
# FLAG '-Wunused' became -Wunused
# FLAG '-fexceptions' became -fexceptions
# FLAG '-Wno-error=date-time ' became -Wno-error=date-time 
# FLAG '-Wmissing-braces' became -Wmissing-braces
# FLAG ''-DBUILD_WITH_NDK="1"'' became -DBUILD_WITH_NDK=\\\"1\\\"
# FLAG '-DVCS_OS_LINUX' became -DVCS_OS_LINUX
# FLAG '-DVCS_OS_ANDROID' became -DVCS_OS_ANDROID
# FLAG '-DSTRICT' became -DSTRICT
# FLAG '-D_MBCS' became -D_MBCS
# FLAG '-DSYNA_FP_IST' became -DSYNA_FP_IST
# FLAG '-DVCS_OS_TZ_QSEE' became -DVCS_OS_TZ_QSEE
# FLAG ''-DCUST_H="custnakaanaaa.h"'' became -DCUST_H=\\\"custnakaanaaa.h\\\"
# FLAG '-DVCS_FEATURES_DEFINED=1' became -DVCS_FEATURES_DEFINED=1
# FLAG '-DDLOG_PALRUNTIME_DEFFLAGS=0xFFFFFFFF' became -DDLOG_PALRUNTIME_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_PALRUNTIME_DEFLEVEL=1' became -DDLOG_PALRUNTIME_DEFLEVEL=1
# FLAG '-DDLOG_PALCRYPTO_DEFFLAGS=0xFFFFFFFF' became -DDLOG_PALCRYPTO_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_PALCRYPTO_DEFLEVEL=1' became -DDLOG_PALCRYPTO_DEFLEVEL=1
# FLAG '-DDLOG_PALSENSOR_DEFFLAGS=0xFFFFFFFF' became -DDLOG_PALSENSOR_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_PALSENSOR_DEFLEVEL=1' became -DDLOG_PALSENSOR_DEFLEVEL=1
# FLAG '-DDLOG_PALUTIL_DEFFLAGS=0xFFFFFFFF' became -DDLOG_PALUTIL_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_PALUTIL_DEFLEVEL=1' became -DDLOG_PALUTIL_DEFLEVEL=1
# FLAG '-DDLOG_SSI_DEFFLAGS=0xFFFFFFFF' became -DDLOG_SSI_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_SSI_DEFLEVEL=1' became -DDLOG_SSI_DEFLEVEL=1
# FLAG '-DDLOG_SMI_DEFFLAGS=0xFFFFFFFF' became -DDLOG_SMI_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_SMI_DEFLEVEL=1' became -DDLOG_SMI_DEFLEVEL=1
# FLAG '-DDLOG_STI_DEFFLAGS=0xFFFFFFFF' became -DDLOG_STI_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_STI_DEFLEVEL=1' became -DDLOG_STI_DEFLEVEL=1
# FLAG '-DDLOG_VFM_DEFFLAGS=0xFFFFFFFF' became -DDLOG_VFM_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_VFM_DEFLEVEL=1' became -DDLOG_VFM_DEFLEVEL=1
# FLAG '-DDLOG_VTP_DLL_DEFFLAGS=0xFFFFFFFF' became -DDLOG_VTP_DLL_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_VTP_DLL_DEFLEVEL=1' became -DDLOG_VTP_DLL_DEFLEVEL=1
# FLAG '-DDLOG_AUTH_DEFFLAGS=0xFFFFFFFF' became -DDLOG_AUTH_DEFFLAGS=0xFFFFFFFF
# FLAG '-DDLOG_AUTH_DEFLEVEL=1' became -DDLOG_AUTH_DEFLEVEL=1
# FLAG ''-DVFM_TRANSPORT_SECURE_FP_ID="libvfmtztransport.so"'' became -DVFM_TRANSPORT_SECURE_FP_ID=\\\"libvfmtztransport.so\\\"
# FLAG '-DVFM_AVAILABLE_MEM_FOR_TPL_LIST=0x00200000' became -DVFM_AVAILABLE_MEM_FOR_TPL_LIST=0x00200000
# FLAG '-DNISE_FEATURE_ADR_HAL_NON_TZ=0' became -DNISE_FEATURE_ADR_HAL_NON_TZ=0
# FLAG '-DCHECK_FOR_DUPLICATE_ENROLLMENT=1' became -DCHECK_FOR_DUPLICATE_ENROLLMENT=1
# FLAG '-DQM_MIN_ENROLL_VIEWS=20' became -DQM_MIN_ENROLL_VIEWS=20
# FLAG '-DQM_INVALID_PARAM_VAL=0xFFFFFF' became -DQM_INVALID_PARAM_VAL=0xFFFFFF
# FLAG '-DCHECK_FU_BEFORE_NAV_START=1' became -DCHECK_FU_BEFORE_NAV_START=1
# FLAG '-DSYNAFP_KEY_EVENT_FINGER_DETECTED=0x230' became -DSYNAFP_KEY_EVENT_FINGER_DETECTED=0x230
# FLAG '-DSYNAFP_KEY_EVENT_FINGER_REMOVED=0x231' became -DSYNAFP_KEY_EVENT_FINGER_REMOVED=0x231
# FLAG '-DSYNAFP_KEY_EVENT_FINGER_RESTED=0x232' became -DSYNAFP_KEY_EVENT_FINGER_RESTED=0x232
# FLAG '-DSYNAFP_KEY_EVENT_FINGER_LONGPRESS=0x8B' became -DSYNAFP_KEY_EVENT_FINGER_LONGPRESS=0x8B
# FLAG '-DSYNAFP_KEY_EVENT_DPAD_RIGHT=0x6A' became -DSYNAFP_KEY_EVENT_DPAD_RIGHT=0x6A
# FLAG '-DSYNAFP_KEY_EVENT_DPAD_LEFT=0x69' became -DSYNAFP_KEY_EVENT_DPAD_LEFT=0x69
# FLAG '-DSYNAFP_KEY_EVENT_DPAD_DOWN=0x6C' became -DSYNAFP_KEY_EVENT_DPAD_DOWN=0x6C
# FLAG '-DSYNAFP_KEY_EVENT_DPAD_UP=0x67' became -DSYNAFP_KEY_EVENT_DPAD_UP=0x67
# FLAG '-DSYNAFP_KEY_EVENT_CLICK=0x1C' became -DSYNAFP_KEY_EVENT_CLICK=0x1C
# FLAG '-DSYNAFP_KEY_EVENT_FINGER_DTAP=0x239' became -DSYNAFP_KEY_EVENT_FINGER_DTAP=0x239
# FLAG '-DSYNAFP_NO_STIMULUS_SCRIPT_ID=10101' became -DSYNAFP_NO_STIMULUS_SCRIPT_ID=10101
# FLAG '-DSYNAFP_STIMULUS_SCRIPT_ID=10102' became -DSYNAFP_STIMULUS_SCRIPT_ID=10102
# FLAG '-DSYNAFP_SHUTDOWN_SCRIPT_ID=6666' became -DSYNAFP_SHUTDOWN_SCRIPT_ID=6666
# FLAG '-DSYNAFP_IDENTIFY_RETRY_COUNT=0xFFFFFFFF' became -DSYNAFP_IDENTIFY_RETRY_COUNT=0xFFFFFFFF
# FLAG '-DQM_ENROLL_VIEWS=20' became -DQM_ENROLL_VIEWS=20
# FLAG '-DQM_DYNAMIC_REDUNDANCY_CHECK' became -DQM_DYNAMIC_REDUNDANCY_CHECK
# FLAG '-DQM_DYNAMIC_REDUNDANCY_CHECK_START=5' became -DQM_DYNAMIC_REDUNDANCY_CHECK_START=5
# FLAG '-DQM_DYNAMIC_REDUNDANCY_CHECK_END=12' became -DQM_DYNAMIC_REDUNDANCY_CHECK_END=12
# FLAG '-DQM_REDUNDANCY_LEVEL=3' became -DQM_REDUNDANCY_LEVEL=3
# FLAG '-DQM_MAX_REDUNDANCY_IMAGES=8' became -DQM_MAX_REDUNDANCY_IMAGES=8
# FLAG '-DANDROID_VERSION=8' became -DANDROID_VERSION=8
# FLAG '-DFRAMEWORK_BASED_FINGERUP=1' became -DFRAMEWORK_BASED_FINGERUP=1
# FLAG '-DSYNAFP_CHECK_3GPIO_POLICY=0' became -DSYNAFP_CHECK_3GPIO_POLICY=0
# FLAG '-DSYNA_USE_ONLY_NOGPIO=1' became -DSYNA_USE_ONLY_NOGPIO=1
# FLAG '-DUSE_DYN_LOG_LEVEL' became -DUSE_DYN_LOG_LEVEL
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -llog")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fexceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=date-time ")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-braces")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILD_WITH_NDK=\\\"1\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVCS_OS_LINUX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVCS_OS_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSTRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_MBCS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNA_FP_IST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVCS_OS_TZ_QSEE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCUST_H=\\\"custnakaanaaa.h\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVCS_FEATURES_DEFINED=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALRUNTIME_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALRUNTIME_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALCRYPTO_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALCRYPTO_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALSENSOR_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALSENSOR_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALUTIL_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_PALUTIL_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_SSI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_SSI_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_SMI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_SMI_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_STI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_STI_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_VFM_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_VFM_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_VTP_DLL_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_VTP_DLL_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_AUTH_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDLOG_AUTH_DEFLEVEL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVFM_TRANSPORT_SECURE_FP_ID=\\\"libvfmtztransport.so\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVFM_AVAILABLE_MEM_FOR_TPL_LIST=0x00200000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNISE_FEATURE_ADR_HAL_NON_TZ=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHECK_FOR_DUPLICATE_ENROLLMENT=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_MIN_ENROLL_VIEWS=20")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_INVALID_PARAM_VAL=0xFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHECK_FU_BEFORE_NAV_START=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_DETECTED=0x230")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_REMOVED=0x231")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_RESTED=0x232")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_LONGPRESS=0x8B")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_RIGHT=0x6A")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_LEFT=0x69")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_DOWN=0x6C")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_UP=0x67")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_CLICK=0x1C")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_DTAP=0x239")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_NO_STIMULUS_SCRIPT_ID=10101")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_STIMULUS_SCRIPT_ID=10102")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_SHUTDOWN_SCRIPT_ID=6666")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_IDENTIFY_RETRY_COUNT=0xFFFFFFFF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_ENROLL_VIEWS=20")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK_START=5")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK_END=12")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_REDUNDANCY_LEVEL=3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQM_MAX_REDUNDANCY_IMAGES=8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_VERSION=8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DFRAMEWORK_BASED_FINGERUP=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNAFP_CHECK_3GPIO_POLICY=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYNA_USE_ONLY_NOGPIO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_DYN_LOG_LEVEL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -llog")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=date-time ")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-braces")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILD_WITH_NDK=\\\"1\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVCS_OS_LINUX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVCS_OS_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSTRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_MBCS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNA_FP_IST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVCS_OS_TZ_QSEE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCUST_H=\\\"custnakaanaaa.h\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVCS_FEATURES_DEFINED=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALRUNTIME_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALRUNTIME_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALCRYPTO_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALCRYPTO_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALSENSOR_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALSENSOR_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALUTIL_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_PALUTIL_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_SSI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_SSI_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_SMI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_SMI_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_STI_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_STI_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_VFM_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_VFM_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_VTP_DLL_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_VTP_DLL_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_AUTH_DEFFLAGS=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDLOG_AUTH_DEFLEVEL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVFM_TRANSPORT_SECURE_FP_ID=\\\"libvfmtztransport.so\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVFM_AVAILABLE_MEM_FOR_TPL_LIST=0x00200000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNISE_FEATURE_ADR_HAL_NON_TZ=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHECK_FOR_DUPLICATE_ENROLLMENT=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_MIN_ENROLL_VIEWS=20")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_INVALID_PARAM_VAL=0xFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHECK_FU_BEFORE_NAV_START=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_DETECTED=0x230")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_REMOVED=0x231")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_RESTED=0x232")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_LONGPRESS=0x8B")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_RIGHT=0x6A")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_LEFT=0x69")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_DOWN=0x6C")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_DPAD_UP=0x67")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_CLICK=0x1C")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_KEY_EVENT_FINGER_DTAP=0x239")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_NO_STIMULUS_SCRIPT_ID=10101")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_STIMULUS_SCRIPT_ID=10102")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_SHUTDOWN_SCRIPT_ID=6666")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_IDENTIFY_RETRY_COUNT=0xFFFFFFFF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_ENROLL_VIEWS=20")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK_START=5")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_DYNAMIC_REDUNDANCY_CHECK_END=12")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_REDUNDANCY_LEVEL=3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQM_MAX_REDUNDANCY_IMAGES=8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_VERSION=8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DFRAMEWORK_BASED_FINGERUP=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNAFP_CHECK_3GPIO_POLICY=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYNA_USE_ONLY_NOGPIO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_DYN_LOG_LEVEL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
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
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = '-fvisibility-inlines-hidden'
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


add_executable(fingerprint.syna ${SOURCE_FILES})
