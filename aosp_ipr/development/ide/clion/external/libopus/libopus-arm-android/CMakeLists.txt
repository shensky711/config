# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libopus)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libopus/celt/bands.c
    ${ANDROID_ROOT}/external/libopus/celt/celt.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_encoder.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_decoder.c
    ${ANDROID_ROOT}/external/libopus/celt/cwrs.c
    ${ANDROID_ROOT}/external/libopus/celt/entcode.c
    ${ANDROID_ROOT}/external/libopus/celt/entdec.c
    ${ANDROID_ROOT}/external/libopus/celt/entenc.c
    ${ANDROID_ROOT}/external/libopus/celt/kiss_fft.c
    ${ANDROID_ROOT}/external/libopus/celt/laplace.c
    ${ANDROID_ROOT}/external/libopus/celt/mathops.c
    ${ANDROID_ROOT}/external/libopus/celt/mdct.c
    ${ANDROID_ROOT}/external/libopus/celt/modes.c
    ${ANDROID_ROOT}/external/libopus/celt/pitch.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_lpc.c
    ${ANDROID_ROOT}/external/libopus/celt/quant_bands.c
    ${ANDROID_ROOT}/external/libopus/celt/rate.c
    ${ANDROID_ROOT}/external/libopus/celt/vq.c
    ${ANDROID_ROOT}/external/libopus/silk/CNG.c
    ${ANDROID_ROOT}/external/libopus/silk/code_signs.c
    ${ANDROID_ROOT}/external/libopus/silk/init_decoder.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_core.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_frame.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_parameters.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_indices.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_pulses.c
    ${ANDROID_ROOT}/external/libopus/silk/decoder_set_fs.c
    ${ANDROID_ROOT}/external/libopus/silk/dec_API.c
    ${ANDROID_ROOT}/external/libopus/silk/enc_API.c
    ${ANDROID_ROOT}/external/libopus/silk/encode_indices.c
    ${ANDROID_ROOT}/external/libopus/silk/encode_pulses.c
    ${ANDROID_ROOT}/external/libopus/silk/gain_quant.c
    ${ANDROID_ROOT}/external/libopus/silk/interpolate.c
    ${ANDROID_ROOT}/external/libopus/silk/LP_variable_cutoff.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_decode.c
    ${ANDROID_ROOT}/external/libopus/silk/NSQ.c
    ${ANDROID_ROOT}/external/libopus/silk/NSQ_del_dec.c
    ${ANDROID_ROOT}/external/libopus/silk/PLC.c
    ${ANDROID_ROOT}/external/libopus/silk/shell_coder.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_gain.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_LTP.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_NLSF_CB_NB_MB.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_NLSF_CB_WB.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_other.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_pitch_lag.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_pulses_per_block.c
    ${ANDROID_ROOT}/external/libopus/silk/VAD.c
    ${ANDROID_ROOT}/external/libopus/silk/control_audio_bandwidth.c
    ${ANDROID_ROOT}/external/libopus/silk/quant_LTP_gains.c
    ${ANDROID_ROOT}/external/libopus/silk/VQ_WMat_EC.c
    ${ANDROID_ROOT}/external/libopus/silk/HP_variable_cutoff.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_encode.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_VQ.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_unpack.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_del_dec_quant.c
    ${ANDROID_ROOT}/external/libopus/silk/process_NLSFs.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_LR_to_MS.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_MS_to_LR.c
    ${ANDROID_ROOT}/external/libopus/silk/check_control_input.c
    ${ANDROID_ROOT}/external/libopus/silk/control_SNR.c
    ${ANDROID_ROOT}/external/libopus/silk/init_encoder.c
    ${ANDROID_ROOT}/external/libopus/silk/control_codec.c
    ${ANDROID_ROOT}/external/libopus/silk/A2NLSF.c
    ${ANDROID_ROOT}/external/libopus/silk/ana_filt_bank_1.c
    ${ANDROID_ROOT}/external/libopus/silk/biquad_alt.c
    ${ANDROID_ROOT}/external/libopus/silk/bwexpander_32.c
    ${ANDROID_ROOT}/external/libopus/silk/bwexpander.c
    ${ANDROID_ROOT}/external/libopus/silk/debug.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_pitch.c
    ${ANDROID_ROOT}/external/libopus/silk/inner_prod_aligned.c
    ${ANDROID_ROOT}/external/libopus/silk/lin2log.c
    ${ANDROID_ROOT}/external/libopus/silk/log2lin.c
    ${ANDROID_ROOT}/external/libopus/silk/LPC_analysis_filter.c
    ${ANDROID_ROOT}/external/libopus/silk/LPC_inv_pred_gain.c
    ${ANDROID_ROOT}/external/libopus/silk/table_LSF_cos.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF2A.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_stabilize.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_VQ_weights_laroia.c
    ${ANDROID_ROOT}/external/libopus/silk/pitch_est_tables.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_down2_3.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_down2.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_AR2.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_down_FIR.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_IIR_FIR.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_up2_HQ.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_rom.c
    ${ANDROID_ROOT}/external/libopus/silk/sigm_Q15.c
    ${ANDROID_ROOT}/external/libopus/silk/sort.c
    ${ANDROID_ROOT}/external/libopus/silk/sum_sqr_shift.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_decode_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_encode_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_find_predictor.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_quant_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/LTP_analysis_filter_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/LTP_scale_ctrl_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/corrMatrix_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/encode_frame_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_LPC_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_LTP_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_pitch_lags_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_pred_coefs_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/noise_shape_analysis_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/prefilter_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/process_gains_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/regularize_correlations_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/residual_energy16_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/residual_energy_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/solve_LS_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/warped_autocorrelation_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/apply_sine_window_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/autocorr_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/burg_modified_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/k2a_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/k2a_Q16_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/pitch_analysis_core_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/vector_ops_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/schur64_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/schur_FIX.c
    ${ANDROID_ROOT}/external/libopus/src/opus.c
    ${ANDROID_ROOT}/external/libopus/src/opus_decoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_encoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream_encoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream_decoder.c
    ${ANDROID_ROOT}/external/libopus/src/repacketizer.c
    ${ANDROID_ROOT}/external/libopus/src/analysis.c
    ${ANDROID_ROOT}/external/libopus/src/mlp.c
    ${ANDROID_ROOT}/external/libopus/src/mlp_data.c
    ${ANDROID_ROOT}/external/libopus/src/repacketizer_demo.c
    ${ANDROID_ROOT}/external/libopus/celt/arm/armcpu.c
    ${ANDROID_ROOT}/external/libopus/celt/arm/arm_celt_map.c
    ${ANDROID_ROOT}/external/libopus/celt/arm/celt_pitch_xcorr_arm_gnu.s
    ${ANDROID_ROOT}/external/libopus/celt/arm/celt_neon_intr.c
    ${ANDROID_ROOT}/external/libopus/silk/arm/arm_silk_map.c
    ${ANDROID_ROOT}/external/libopus/silk/arm/NSQ_neon.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/libopus/include'
# Raw param [1] = '-Iexternal/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed'
# Raw param [2] = '-Iexternal/libopus'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/libopus/include"
    "${ANDROID_ROOT}/external/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed"
    "${ANDROID_ROOT}/external/libopus"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libopus/include/**/*.h"
    "${ANDROID_ROOT}/external/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed/**/*.h"
    "${ANDROID_ROOT}/external/libopus/**/*.h"
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
# Raw param [0] = '-DNULL=0'
# Raw param [1] = '-DSOCKLEN_T=socklen_t'
# Raw param [2] = '-DLOCALE_NOT_USED'
# Raw param [3] = '-D_LARGEFILE_SOURCE=1'
# Raw param [4] = '-D_FILE_OFFSET_BITS=64'
# Raw param [5] = '-Drestrict='
# Raw param [6] = '-D__EMX__'
# Raw param [7] = '-DOPUS_BUILD'
# Raw param [8] = '-DFIXED_POINT'
# Raw param [9] = '-DUSE_ALLOCA'
# Raw param [10] = '-DHAVE_LRINT'
# Raw param [11] = '-DHAVE_LRINTF'
# Raw param [12] = '-O2'
# Raw param [13] = '-fno-math-errno'
# Raw param [14] = '-DOPUS_ARM_ASM'
# Raw param [15] = '-DOPUS_ARM_INLINE_ASM'
# Raw param [16] = '-DOPUS_ARM_MAY_HAVE_EDSP'
# Raw param [17] = '-DOPUS_ARM_INLINE_EDSP'
# Raw param [18] = '-DOPUS_ARM_MAY_HAVE_MEDIA'
# Raw param [19] = '-DOPUS_ARM_INLINE_MEDIA'
# Raw param [20] = '-DOPUS_HAVE_RTCD'
# Raw param [21] = '-DOPUS_ARM_MAY_HAVE_NEON'
# Raw param [22] = '-DOPUS_ARM_MAY_HAVE_NEON_INTR'
# Raw param [23] = '-DOPUS_ARM_PRESUME_NEON'
# Raw param [24] = '-DOPUS_ARM_INLINE_NEON'
# Raw param [25] = '-target arm-linux-androideabi'
# Raw param [26] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [27] = '-fPIC'
# Raw param [28] = '-D_USING_LIBCXX'
# FLAG '-DNULL=0' became -DNULL=0
# FLAG '-DSOCKLEN_T=socklen_t' became -DSOCKLEN_T=socklen_t
# FLAG '-DLOCALE_NOT_USED' became -DLOCALE_NOT_USED
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-Drestrict=' became -Drestrict=
# FLAG '-D__EMX__' became -D__EMX__
# FLAG '-DOPUS_BUILD' became -DOPUS_BUILD
# FLAG '-DFIXED_POINT' became -DFIXED_POINT
# FLAG '-DUSE_ALLOCA' became -DUSE_ALLOCA
# FLAG '-DHAVE_LRINT' became -DHAVE_LRINT
# FLAG '-DHAVE_LRINTF' became -DHAVE_LRINTF
# FLAG '-O2' became -O2
# FLAG '-fno-math-errno' became -fno-math-errno
# FLAG '-DOPUS_ARM_ASM' became -DOPUS_ARM_ASM
# FLAG '-DOPUS_ARM_INLINE_ASM' became -DOPUS_ARM_INLINE_ASM
# FLAG '-DOPUS_ARM_MAY_HAVE_EDSP' became -DOPUS_ARM_MAY_HAVE_EDSP
# FLAG '-DOPUS_ARM_INLINE_EDSP' became -DOPUS_ARM_INLINE_EDSP
# FLAG '-DOPUS_ARM_MAY_HAVE_MEDIA' became -DOPUS_ARM_MAY_HAVE_MEDIA
# FLAG '-DOPUS_ARM_INLINE_MEDIA' became -DOPUS_ARM_INLINE_MEDIA
# FLAG '-DOPUS_HAVE_RTCD' became -DOPUS_HAVE_RTCD
# FLAG '-DOPUS_ARM_MAY_HAVE_NEON' became -DOPUS_ARM_MAY_HAVE_NEON
# FLAG '-DOPUS_ARM_MAY_HAVE_NEON_INTR' became -DOPUS_ARM_MAY_HAVE_NEON_INTR
# FLAG '-DOPUS_ARM_PRESUME_NEON' became -DOPUS_ARM_PRESUME_NEON
# FLAG '-DOPUS_ARM_INLINE_NEON' became -DOPUS_ARM_INLINE_NEON
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNULL=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSOCKLEN_T=socklen_t")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOCALE_NOT_USED")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Drestrict=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__EMX__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_BUILD")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DFIXED_POINT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_ALLOCA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_LRINT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_LRINTF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-math-errno")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_ASM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_INLINE_ASM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_MAY_HAVE_EDSP")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_INLINE_EDSP")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_MAY_HAVE_MEDIA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_INLINE_MEDIA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_HAVE_RTCD")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_MAY_HAVE_NEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_MAY_HAVE_NEON_INTR")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_PRESUME_NEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_ARM_INLINE_NEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNULL=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSOCKLEN_T=socklen_t")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOCALE_NOT_USED")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Drestrict=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__EMX__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_BUILD")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DFIXED_POINT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_ALLOCA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_LRINT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_LRINTF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-math-errno")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_ASM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_INLINE_ASM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_MAY_HAVE_EDSP")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_INLINE_EDSP")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_MAY_HAVE_MEDIA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_INLINE_MEDIA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_HAVE_RTCD")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_MAY_HAVE_NEON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_MAY_HAVE_NEON_INTR")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_PRESUME_NEON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_ARM_INLINE_NEON")
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
# Raw param [2] = '-DBSD=1'
# Raw param [3] = '-ffast-math'
# Raw param [4] = '-O2'
# Raw param [5] = '-funroll-loops'
# Raw param [6] = '-fno-rtti'
# Raw param [7] = '${config.ArmClangCppflags}'
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
# FLAG '-DBSD=1' became -DBSD=1
# FLAG '-ffast-math' became -ffast-math
# FLAG '-O2' became -O2
# FLAG '-funroll-loops' became -funroll-loops
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBSD=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffast-math")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funroll-loops")
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


add_executable(libopus ${SOURCE_FILES})
