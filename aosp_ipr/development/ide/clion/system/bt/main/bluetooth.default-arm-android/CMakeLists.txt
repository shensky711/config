# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(bluetooth.default)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/system/bt/main/bte_conf.cc
    ${ANDROID_ROOT}/system/bt/main/bte_init.cc
    ${ANDROID_ROOT}/system/bt/main/bte_init_cpp_logging.cc
    ${ANDROID_ROOT}/system/bt/main/bte_logmsg.cc
    ${ANDROID_ROOT}/system/bt/main/bte_main.cc
    ${ANDROID_ROOT}/system/bt/main/stack_config.cc
    ${ANDROID_ROOT}/system/bt/main/wipower.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Idevice/qcom/common -Idevice/qcom/common -Isystem/bt -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/bta/dm -Isystem/bt/btcore/include -Isystem/bt/include -Isystem/bt/stack/include -Isystem/bt/stack/l2cap -Isystem/bt/stack/a2dp -Isystem/bt/stack/btm -Isystem/bt/stack/avdt -Isystem/bt/udrv/include -Isystem/bt/btif/include -Isystem/bt/btif/co -Isystem/bt/hci/include -Isystem/bt/vnd/include -Isystem/bt/embdrv/sbc/encoder/include -Isystem/bt/embdrv/sbc/decoder/include -Isystem/bt/utils/include -Ivendor/qcom/opensource/bluetooth/hal/include -Ivendor/qcom/opensource/bluetooth_ext/vhal/include -Ivendor/qcom/opensource/bluetooth_ext/system_bt_ext'
# Raw param [1] = '-Isystem/bt/main'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [7] = '-Iexternal/protobuf/src'
# Raw param [8] = '-Iout/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto/system/bt/osi'
# Raw param [9] = '-Iout/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto'
# Raw param [10] = '-Isystem/bt/types'
# Raw param [11] = '-Iexternal/aac/libAACdec/include'
# Raw param [12] = '-Iexternal/aac/libAACenc/include'
# Raw param [13] = '-Iexternal/aac/libPCMutils/include'
# Raw param [14] = '-Iexternal/aac/libFDK/include'
# Raw param [15] = '-Iexternal/aac/libSYS/include'
# Raw param [16] = '-Iexternal/aac/libMpegTPDec/include'
# Raw param [17] = '-Iexternal/aac/libMpegTPEnc/include'
# Raw param [18] = '-Iexternal/aac/libSBRdec/include'
# Raw param [19] = '-Iexternal/aac/libSBRenc/include'
# Raw param [20] = '-Iexternal/libchrome'
# Raw param [21] = '-Iexternal/googletest/googletest/include'
# Raw param [22] = '-Isystem/core/base/include'
# Raw param [23] = '-Isystem/libhidl/base/include'
# Raw param [24] = '-Isystem/core/libcutils/include'
# Raw param [25] = '-Isystem/core/libutils/include'
# Raw param [26] = '-Isystem/core/libbacktrace/include'
# Raw param [27] = '-Isystem/core/liblog/include'
# Raw param [28] = '-Isystem/core/libsystem/include'
# Raw param [29] = '-Isystem/libhidl/transport/include'
# Raw param [30] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [31] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [32] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [33] = '-Isystem/libhwbinder/include'
# Raw param [34] = '-Iout/soong/.intermediates/hardware/interfaces/bluetooth/1.0/android.hardware.bluetooth@1.0_genc++_headers/gen'
# Raw param [35] = '-Iout/soong/.intermediates/vendor/qcom/proprietary/interfaces/bluetooth_audio/1.0/com.qualcomm.qti.bluetooth_audio@1.0_genc++_headers/gen'
# Raw param [36] = '-Iframeworks/av/media/libaudioclient/include'
# Raw param [37] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl'
# Raw param [38] = '-Iframeworks/native/libs/binder/include'
# Raw param [39] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl'
# Raw param [40] = '-Iexternal/tinyxml2'
# Raw param [41] = '-Iexternal/zlib'
# Raw param [42] = '-Iexternal/libcxx/include'
# Raw param [43] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/device/qcom/common -Idevice/qcom/common -Isystem/bt -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/bta/dm -Isystem/bt/btcore/include -Isystem/bt/include -Isystem/bt/stack/include -Isystem/bt/stack/l2cap -Isystem/bt/stack/a2dp -Isystem/bt/stack/btm -Isystem/bt/stack/avdt -Isystem/bt/udrv/include -Isystem/bt/btif/include -Isystem/bt/btif/co -Isystem/bt/hci/include -Isystem/bt/vnd/include -Isystem/bt/embdrv/sbc/encoder/include -Isystem/bt/embdrv/sbc/decoder/include -Isystem/bt/utils/include -Ivendor/qcom/opensource/bluetooth/hal/include -Ivendor/qcom/opensource/bluetooth_ext/vhal/include -Ivendor/qcom/opensource/bluetooth_ext/system_bt_ext"
    "${ANDROID_ROOT}/system/bt/main"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto/system/bt/osi"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/external/aac/libAACdec/include"
    "${ANDROID_ROOT}/external/aac/libAACenc/include"
    "${ANDROID_ROOT}/external/aac/libPCMutils/include"
    "${ANDROID_ROOT}/external/aac/libFDK/include"
    "${ANDROID_ROOT}/external/aac/libSYS/include"
    "${ANDROID_ROOT}/external/aac/libMpegTPDec/include"
    "${ANDROID_ROOT}/external/aac/libMpegTPEnc/include"
    "${ANDROID_ROOT}/external/aac/libSBRdec/include"
    "${ANDROID_ROOT}/external/aac/libSBRenc/include"
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/bluetooth/1.0/android.hardware.bluetooth@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/vendor/qcom/proprietary/interfaces/bluetooth_audio/1.0/com.qualcomm.qti.bluetooth_audio@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl"
    "${ANDROID_ROOT}/external/tinyxml2"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/device/qcom/common -Idevice/qcom/common -Isystem/bt -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/bta/dm -Isystem/bt/btcore/include -Isystem/bt/include -Isystem/bt/stack/include -Isystem/bt/stack/l2cap -Isystem/bt/stack/a2dp -Isystem/bt/stack/btm -Isystem/bt/stack/avdt -Isystem/bt/udrv/include -Isystem/bt/btif/include -Isystem/bt/btif/co -Isystem/bt/hci/include -Isystem/bt/vnd/include -Isystem/bt/embdrv/sbc/encoder/include -Isystem/bt/embdrv/sbc/decoder/include -Isystem/bt/utils/include -Ivendor/qcom/opensource/bluetooth/hal/include -Ivendor/qcom/opensource/bluetooth_ext/vhal/include -Ivendor/qcom/opensource/bluetooth_ext/system_bt_ext/**/*.h"
    "${ANDROID_ROOT}/system/bt/main/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto/system/bt/osi/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/osi/libbt-protos/android_arm_armv7-a-neon_cortex-a9_static_core/gen/proto/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/external/aac/libAACdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libAACenc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libPCMutils/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libFDK/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSYS/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libMpegTPDec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libMpegTPEnc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSBRdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSBRenc/include/**/*.h"
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/bluetooth/1.0/android.hardware.bluetooth@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/vendor/qcom/proprietary/interfaces/bluetooth_audio/1.0/com.qualcomm.qti.bluetooth_audio@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/external/tinyxml2/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
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
# Raw param [0] = ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))''
# Raw param [1] = '-fvisibility=hidden'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Wextra'
# Raw param [4] = '-Werror'
# Raw param [5] = '-Wno-gnu-variable-sized-type-not-at-end'
# Raw param [6] = '-Wno-typedef-redefinition'
# Raw param [7] = '-Wno-unused-parameter'
# Raw param [8] = '-DLOG_NDEBUG=1'
# Raw param [9] = '-DHAS_BDROID_BUILDCFG'
# Raw param [10] = '-DMEIZU_BLACKLIST'
# Raw param [11] = '-DMEIZU_LDAC_ENABLE'
# Raw param [12] = '-DHAS_BDROID_BUILDCFG'
# Raw param [13] = '-DMEIZU_BLACKLIST'
# Raw param [14] = '-DMEIZU_LDAC_ENABLE'
# Raw param [15] = '-DBUILDCFG'
# Raw param [16] = '-DBLUEDROID_DEBUG'
# Raw param [17] = '-DDCHECK_ALWAYS_ON'
# Raw param [18] = '-target arm-linux-androideabi'
# Raw param [19] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [20] = '-DANDROID_STRICT'
# Raw param [21] = '-fPIC'
# Raw param [22] = '-D_USING_LIBCXX'
# FLAG ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))'' became -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-Wno-gnu-variable-sized-type-not-at-end' became -Wno-gnu-variable-sized-type-not-at-end
# FLAG '-Wno-typedef-redefinition' became -Wno-typedef-redefinition
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DLOG_NDEBUG=1' became -DLOG_NDEBUG=1
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-DMEIZU_BLACKLIST' became -DMEIZU_BLACKLIST
# FLAG '-DMEIZU_LDAC_ENABLE' became -DMEIZU_LDAC_ENABLE
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-DMEIZU_BLACKLIST' became -DMEIZU_BLACKLIST
# FLAG '-DMEIZU_LDAC_ENABLE' became -DMEIZU_LDAC_ENABLE
# FLAG '-DBUILDCFG' became -DBUILDCFG
# FLAG '-DBLUEDROID_DEBUG' became -DBLUEDROID_DEBUG
# FLAG '-DDCHECK_ALWAYS_ON' became -DDCHECK_ALWAYS_ON
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMEIZU_BLACKLIST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMEIZU_LDAC_ENABLE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMEIZU_BLACKLIST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMEIZU_LDAC_ENABLE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDCHECK_ALWAYS_ON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DMEIZU_BLACKLIST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DMEIZU_LDAC_ENABLE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DMEIZU_BLACKLIST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DMEIZU_LDAC_ENABLE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDCHECK_ALWAYS_ON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# Raw param [2] = '-std=c99'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
# FLAG '-std=c99' became -std=c99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

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


add_executable(bluetooth.default ${SOURCE_FILES})
