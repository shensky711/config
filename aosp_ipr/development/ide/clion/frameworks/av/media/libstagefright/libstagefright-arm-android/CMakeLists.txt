# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libstagefright)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/ACodec.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/ACodecBufferChannel.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AACExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AACWriter.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AMRExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AMRWriter.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AudioPlayer.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/AudioSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/BufferImpl.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/CodecBase.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/CallbackDataSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/CameraSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/CameraSourceTimeLapse.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/DataConverter.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/DataSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/DataURISource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/ESDS.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/FileSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/FLACExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/FrameRenderTracker.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/HTTPBase.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/HevcUtils.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/ItemTable.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/JPEGSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MP3Extractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MPEG2TSWriter.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MPEG4Extractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MPEG4Writer.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaAdapter.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaClock.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaCodec.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaCodecList.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaCodecListOverrides.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaCodecSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaSync.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MidiExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/http/MediaHTTP.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaMuxer.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MediaSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/NuCachedSource2.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/NuMediaExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/OMXClient.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/OmxInfoBuilder.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/OggExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SampleIterator.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SampleTable.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SimpleDecodingSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SkipCutBuffer.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/StagefrightMediaScanner.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/StagefrightMetadataRetriever.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SurfaceMediaSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/SurfaceUtils.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/ThrottledSource.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/Utils.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/VBRISeeker.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/VideoFrameScheduler.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/WAVExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/XINGSeeker.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/avc_utils.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/mzExtExtractor.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/FFMPEGSoftCodec.cpp
    ${ANDROID_ROOT}/frameworks/av/media/libstagefright/MP3Writer.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/av/media/libstagefright/include'
# Raw param [1] = '-Iframeworks/native/include/media/openmax -Iframeworks/av/media/libavextensions -Iframeworks/av/media/libstagefright/mpeg2ts -Iframeworks/native/include/media/hardware -Iflyme/frameworks/av/common/include'
# Raw param [2] = '-Iframeworks/av/media/libstagefright'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [8] = '-Iexternal/libyuv/files/include'
# Raw param [9] = '-Iexternal/libvpx/libvpx'
# Raw param [10] = '-Iexternal/libvpx/libwebm'
# Raw param [11] = '-Iexternal/flac/include'
# Raw param [12] = '-Isystem/media/audio_utils/include'
# Raw param [13] = '-Isystem/media/audio/include'
# Raw param [14] = '-Isystem/core/libcutils/include'
# Raw param [15] = '-Isystem/core/libutils/include'
# Raw param [16] = '-Isystem/core/libbacktrace/include'
# Raw param [17] = '-Isystem/core/liblog/include'
# Raw param [18] = '-Isystem/core/libsystem/include'
# Raw param [19] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl'
# Raw param [20] = '-Iframeworks/native/libs/binder/include'
# Raw param [21] = '-Isystem/core/base/include'
# Raw param [22] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl'
# Raw param [23] = '-Iframeworks/av/camera/include'
# Raw param [24] = '-Iframeworks/av/camera/include/camera'
# Raw param [25] = '-Isystem/media/camera/include'
# Raw param [26] = '-Iout/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl'
# Raw param [27] = '-Iexternal/boringssl/src/include'
# Raw param [28] = '-Iframeworks/av/drm/libdrmframework/include'
# Raw param [29] = '-Iframeworks/av/drm/common/include'
# Raw param [30] = '-Iexternal/expat/lib'
# Raw param [31] = '-Iframeworks/native/libs/gui/include'
# Raw param [32] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [33] = '-Iframeworks/native/opengl/include'
# Raw param [34] = '-Iframeworks/native/libs/ui/include'
# Raw param [35] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [36] = '-Ihardware/libhardware/include'
# Raw param [37] = '-Iframeworks/native/libs/arect/include'
# Raw param [38] = '-Iframeworks/native/libs/math/include'
# Raw param [39] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [40] = '-Isystem/libhidl/transport/token/1.0/utils/include'
# Raw param [41] = '-Isystem/libhidl/base/include'
# Raw param [42] = '-Isystem/libhidl/transport/include'
# Raw param [43] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [44] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [45] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [46] = '-Isystem/libhwbinder/include'
# Raw param [47] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [48] = '-Iout/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen'
# Raw param [49] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen'
# Raw param [50] = '-Iframeworks/av/media/libmedia/aidl'
# Raw param [51] = '-Iframeworks/av/media/libmedia/include'
# Raw param [52] = '-Iframeworks/av/media/libstagefright/include'
# Raw param [53] = '-Iframeworks/native/headers/media_plugin'
# Raw param [54] = '-Iframeworks/native/headers/media_plugin/media/openmax'
# Raw param [55] = '-Iframeworks/av/media/libstagefright/foundation/include'
# Raw param [56] = '-Iout/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen'
# Raw param [57] = '-Iexternal/sonivox/arm-wt-22k/include'
# Raw param [58] = '-Iexternal/icu/icu4c/source/common'
# Raw param [59] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [60] = '-Iexternal/protobuf/src'
# Raw param [61] = '-Isystem/libhidl/libhidlmemory/include'
# Raw param [62] = '-Iout/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen'
# Raw param [63] = '-Iout/soong/.intermediates/frameworks/av/media/libmedia/libmedia/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl'
# Raw param [64] = '-Iframeworks/av/media/libaudioclient/include'
# Raw param [65] = '-Iframeworks/av/media/libmediametrics/include'
# Raw param [66] = '-Iframeworks/av/media/utils/include'
# Raw param [67] = '-Isystem/netd/include'
# Raw param [68] = '-Iexternal/tremolo'
# Raw param [69] = '-Iframeworks/av/media/libstagefright/omx/include'
# Raw param [70] = '-Iout/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl'
# Raw param [71] = '-Iframeworks/av/media/libstagefright/xmlparser/include'
# Raw param [72] = '-Iframeworks/rs/cpp'
# Raw param [73] = '-Iframeworks/rs'
# Raw param [74] = '-Iout/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen'
# Raw param [75] = '-Iout/soong/.intermediates/hardware/interfaces/cas/1.0/android.hardware.cas@1.0_genc++_headers/gen'
# Raw param [76] = '-Iout/soong/.intermediates/hardware/interfaces/cas/native/1.0/android.hardware.cas.native@1.0_genc++_headers/gen'
# Raw param [77] = '-Iexternal/libcxx/include'
# Raw param [78] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include"
    "${ANDROID_ROOT}/frameworks/native/include/media/openmax -Iframeworks/av/media/libavextensions -Iframeworks/av/media/libstagefright/mpeg2ts -Iframeworks/native/include/media/hardware -Iflyme/frameworks/av/common/include"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright"
    "${ANDROID_ROOT}/external/libyuv/files/include"
    "${ANDROID_ROOT}/external/libvpx/libvpx"
    "${ANDROID_ROOT}/external/libvpx/libwebm"
    "${ANDROID_ROOT}/external/flac/include"
    "${ANDROID_ROOT}/system/media/audio_utils/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/camera/include"
    "${ANDROID_ROOT}/frameworks/av/camera/include/camera"
    "${ANDROID_ROOT}/system/media/camera/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/frameworks/av/drm/libdrmframework/include"
    "${ANDROID_ROOT}/frameworks/av/drm/common/include"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
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
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include"
    "${ANDROID_ROOT}/frameworks/av/media/libmediametrics/include"
    "${ANDROID_ROOT}/frameworks/av/media/utils/include"
    "${ANDROID_ROOT}/system/netd/include"
    "${ANDROID_ROOT}/external/tremolo"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/omx/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/xmlparser/include"
    "${ANDROID_ROOT}/frameworks/rs/cpp"
    "${ANDROID_ROOT}/frameworks/rs"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/cas/1.0/android.hardware.cas@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/cas/native/1.0/android.hardware.cas.native@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/include/media/openmax -Iframeworks/av/media/libavextensions -Iframeworks/av/media/libstagefright/mpeg2ts -Iframeworks/native/include/media/hardware -Iflyme/frameworks/av/common/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/**/*.h"
    "${ANDROID_ROOT}/external/libyuv/files/include/**/*.h"
    "${ANDROID_ROOT}/external/libvpx/libvpx/**/*.h"
    "${ANDROID_ROOT}/external/libvpx/libwebm/**/*.h"
    "${ANDROID_ROOT}/external/flac/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio_utils/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_static_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/camera/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/camera/include/camera/**/*.h"
    "${ANDROID_ROOT}/system/media/camera/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/drm/libdrmframework/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/drm/common/include/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
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
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmediametrics/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/netd/include/**/*.h"
    "${ANDROID_ROOT}/external/tremolo/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/omx/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv7-a-neon_cortex-a9_shared_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/xmlparser/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/rs/cpp/**/*.h"
    "${ANDROID_ROOT}/frameworks/rs/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/cas/1.0/android.hardware.cas@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/cas/native/1.0/android.hardware.cas.native@1.0_genc++_headers/gen/**/*.h"
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
# Raw param [0] = '-Wno-multichar'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-error=deprecated-declarations'
# Raw param [3] = '-Wall'
# Raw param [4] = '-DENABLE_STAGEFRIGHT_EXPERIMENTS'
# Raw param [5] = '-target arm-linux-androideabi'
# Raw param [6] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [7] = '-DANDROID_STRICT'
# Raw param [8] = '-fPIC'
# Raw param [9] = '-D_USING_LIBCXX'
# Raw param [10] = '-fsanitize=unsigned-integer-overflow,signed-integer-overflow'
# Raw param [11] = '-fsanitize-trap=all'
# Raw param [12] = '-ftrap-function=abort'
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-Werror' became -Werror
# FLAG '-Wno-error=deprecated-declarations' became -Wno-error=deprecated-declarations
# FLAG '-Wall' became -Wall
# FLAG '-DENABLE_STAGEFRIGHT_EXPERIMENTS' became -DENABLE_STAGEFRIGHT_EXPERIMENTS
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-fsanitize=unsigned-integer-overflow,signed-integer-overflow' became -fsanitize=unsigned-integer-overflow,signed-integer-overflow
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_STAGEFRIGHT_EXPERIMENTS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=unsigned-integer-overflow,signed-integer-overflow")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_STAGEFRIGHT_EXPERIMENTS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=unsigned-integer-overflow,signed-integer-overflow")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-trap=all")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ftrap-function=abort")

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


add_executable(libstagefright ${SOURCE_FILES})
