# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(hwuimacro)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/BitmapFillrate.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/BitmapShaders.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ClippingAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/GlyphStressAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwBitmap565.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwBitmapInCompositeShader.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwLayerAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwLayerSizeAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ListOfFadedTextAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ListViewAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/OpPropAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/OvalAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/PartialDamageAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ReadbackFromHardwareBitmap.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RecentsAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RectGridAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RoundRectClippingAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SaveLayer2Animation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SaveLayerAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowGrid2Animation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowGridAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowShaderAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShapeAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SimpleColorMatrixAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SimpleGradientAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/TextAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/TvApp.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/LeakChecker.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestListViewSceneBase.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestContext.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestScene.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/macrobench/TestSceneRunner.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/macrobench/main.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu'
# Raw param [1] = '-Iframeworks/base/libs/hwui'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iframeworks/base/libs/hwui'
# Raw param [8] = '-Iexternal/protobuf/src'
# Raw param [9] = '-Iframeworks/rs/cpp'
# Raw param [10] = '-Iframeworks/rs'
# Raw param [11] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base/libs/hwui'
# Raw param [12] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto'
# Raw param [13] = '-Iout/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base'
# Raw param [14] = '-Iout/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto'
# Raw param [15] = '-Iexternal/google-benchmark/include'
# Raw param [16] = '-Isystem/core/liblog/include'
# Raw param [17] = '-Isystem/core/libcutils/include'
# Raw param [18] = '-Isystem/core/libutils/include'
# Raw param [19] = '-Isystem/core/libbacktrace/include'
# Raw param [20] = '-Isystem/core/libsystem/include'
# Raw param [21] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [22] = '-Iframeworks/native/opengl/include'
# Raw param [23] = '-Iframeworks/native/vulkan/include'
# Raw param [24] = '-Ihardware/libhardware/include'
# Raw param [25] = '-Isystem/media/audio/include'
# Raw param [26] = '-Iexternal/skia/include/android'
# Raw param [27] = '-Iexternal/skia/include/c'
# Raw param [28] = '-Iexternal/skia/include/codec'
# Raw param [29] = '-Iexternal/skia/include/config'
# Raw param [30] = '-Iexternal/skia/include/core'
# Raw param [31] = '-Iexternal/skia/include/effects'
# Raw param [32] = '-Iexternal/skia/include/encode'
# Raw param [33] = '-Iexternal/skia/include/gpu'
# Raw param [34] = '-Iexternal/skia/include/gpu/gl'
# Raw param [35] = '-Iexternal/skia/include/gpu/vk'
# Raw param [36] = '-Iexternal/skia/include/pathops'
# Raw param [37] = '-Iexternal/skia/include/ports'
# Raw param [38] = '-Iexternal/skia/include/svg'
# Raw param [39] = '-Iexternal/skia/include/utils'
# Raw param [40] = '-Iexternal/skia/include/utils/mac'
# Raw param [41] = '-Iframeworks/native/libs/ui/include'
# Raw param [42] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [43] = '-Iframeworks/native/libs/arect/include'
# Raw param [44] = '-Iframeworks/native/libs/math/include'
# Raw param [45] = '-Iframeworks/native/libs/gui/include'
# Raw param [46] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_static_core/gen/aidl'
# Raw param [47] = '-Iframeworks/native/libs/binder/include'
# Raw param [48] = '-Isystem/core/base/include'
# Raw param [49] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_shared_core/gen/aidl'
# Raw param [50] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [51] = '-Isystem/libhidl/transport/token/1.0/utils/include'
# Raw param [52] = '-Isystem/libhidl/base/include'
# Raw param [53] = '-Isystem/libhidl/transport/include'
# Raw param [54] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [55] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [56] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [57] = '-Isystem/libhwbinder/include'
# Raw param [58] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [59] = '-Iout/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen'
# Raw param [60] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen'
# Raw param [61] = '-Iexternal/harfbuzz_ng/src'
# Raw param [62] = '-Iexternal/freetype/include'
# Raw param [63] = '-Iframeworks/minikin/include'
# Raw param [64] = '-Iexternal/googletest/googletest/include'
# Raw param [65] = '-Iexternal/icu/icu4c/source/common'
# Raw param [66] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [67] = '-Isystem/core/libmemunreachable/include'
# Raw param [68] = '-Iexternal/libcxx/include'
# Raw param [69] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/frameworks/rs/cpp"
    "${ANDROID_ROOT}/frameworks/rs"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto"
    "${ANDROID_ROOT}/external/google-benchmark/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/external/skia/include/android"
    "${ANDROID_ROOT}/external/skia/include/c"
    "${ANDROID_ROOT}/external/skia/include/codec"
    "${ANDROID_ROOT}/external/skia/include/config"
    "${ANDROID_ROOT}/external/skia/include/core"
    "${ANDROID_ROOT}/external/skia/include/effects"
    "${ANDROID_ROOT}/external/skia/include/encode"
    "${ANDROID_ROOT}/external/skia/include/gpu"
    "${ANDROID_ROOT}/external/skia/include/gpu/gl"
    "${ANDROID_ROOT}/external/skia/include/gpu/vk"
    "${ANDROID_ROOT}/external/skia/include/pathops"
    "${ANDROID_ROOT}/external/skia/include/ports"
    "${ANDROID_ROOT}/external/skia/include/svg"
    "${ANDROID_ROOT}/external/skia/include/utils"
    "${ANDROID_ROOT}/external/skia/include/utils/mac"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_static_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_shared_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src"
    "${ANDROID_ROOT}/external/freetype/include"
    "${ANDROID_ROOT}/frameworks/minikin/include"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/frameworks/rs/cpp/**/*.h"
    "${ANDROID_ROOT}/frameworks/rs/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo300_static_core/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto/frameworks/base/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm64_armv8-a_kryo300_static_core/gen/proto/**/*.h"
    "${ANDROID_ROOT}/external/google-benchmark/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/vulkan/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/android/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/c/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/codec/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/core/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/effects/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/encode/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/gl/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/vk/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/pathops/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/ports/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/svg/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/mac/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_static_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo300_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src/**/*.h"
    "${ANDROID_ROOT}/external/freetype/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/minikin/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include/**/*.h"
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
# Raw param [0] = '-DEGL_EGLEXT_PROTOTYPES'
# Raw param [1] = '-DGL_GLEXT_PROTOTYPES'
# Raw param [2] = '-DATRACE_TAG=ATRACE_TAG_VIEW'
# Raw param [3] = ''-DLOG_TAG="OpenGLRenderer"''
# Raw param [4] = '-Wall'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-Wunreachable-code'
# Raw param [7] = '-Werror'
# Raw param [8] = '-fvisibility=hidden'
# Raw param [9] = '-Wno-missing-braces'
# Raw param [10] = '-DUSE_HWC2'
# Raw param [11] = '-target aarch64-linux-android'
# Raw param [12] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [13] = '-DANDROID_STRICT'
# Raw param [14] = '-fPIE'
# Raw param [15] = '-D_USING_LIBCXX'
# FLAG '-DEGL_EGLEXT_PROTOTYPES' became -DEGL_EGLEXT_PROTOTYPES
# FLAG '-DGL_GLEXT_PROTOTYPES' became -DGL_GLEXT_PROTOTYPES
# FLAG '-DATRACE_TAG=ATRACE_TAG_VIEW' became -DATRACE_TAG=ATRACE_TAG_VIEW
# FLAG ''-DLOG_TAG="OpenGLRenderer"'' became -DLOG_TAG=\\\"OpenGLRenderer\\\"
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wunreachable-code' became -Wunreachable-code
# FLAG '-Werror' became -Werror
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-missing-braces' became -Wno-missing-braces
# FLAG '-DUSE_HWC2' became -DUSE_HWC2
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIE' became -fPIE
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_TAG=\\\"OpenGLRenderer\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-braces")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_HWC2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_TAG=\\\"OpenGLRenderer\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-braces")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_HWC2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
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


add_executable(hwuimacro ${SOURCE_FILES})
