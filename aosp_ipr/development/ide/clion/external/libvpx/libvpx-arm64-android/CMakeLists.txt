# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libvpx)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/alloccommon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/loopfilter_arm.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/bilinearpredict_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/copymem_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/dc_only_idct_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/dequant_idct_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/dequantizeb_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/idct_blk_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/idct_dequant_0_2x_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/idct_dequant_full_2x_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/iwalsh_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/loopfiltersimplehorizontaledge_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/loopfiltersimpleverticaledge_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/mbloopfilter_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/shortidct4x4llm_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/sixtappredict_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/arm/neon/vp8_loopfilter_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/blockd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/copy_c.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/dequantize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/entropy.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/entropymode.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/entropymv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/extend.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/filter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/findnearmv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/generic/systemdependent.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/idct_blk.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/idctllm.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/loopfilter_filters.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/mbpitch.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/modecont.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/quant_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/reconinter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/reconintra.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/reconintra4x4.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/rtcd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/setupintrarecon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/swapyv12buffer.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/treecoder.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/common/vp8_loopfilter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/dboolhuff.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/decodeframe.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/decodemv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/detokenize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/onyxd_if.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/decoder/threading.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/arm/neon/denoising_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/arm/neon/fastquantizeb_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/arm/neon/shortfdct_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/arm/neon/vp8_shortwalsh4x4_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/bitstream.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/boolhuff.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/dct.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/denoising.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/encodeframe.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/encodeintra.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/encodemb.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/encodemv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/ethreading.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/lookahead.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/mcomp.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/modecosts.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/onyx_if.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/pickinter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/picklpf.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/ratectrl.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/rdopt.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/segmentation.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/tokenize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/treewriter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/encoder/vp8_quantize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/vp8_cx_iface.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp8/vp8_dx_iface.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/arm/neon/vp9_iht4x4_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/arm/neon/vp9_iht8x8_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_alloccommon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_blockd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_common_data.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_entropy.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_entropymode.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_entropymv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_filter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_frame_buffers.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_idct.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_loopfilter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_mvref_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_pred_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_quant_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_reconinter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_reconintra.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_rtcd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_scale.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_scan.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_seg_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_thread_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/common/vp9_tile_common.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_decodeframe.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_decodemv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_decoder.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_detokenize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_dsubexp.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/decoder/vp9_dthread.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/arm/neon/vp9_dct_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/arm/neon/vp9_error_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/arm/neon/vp9_quantize_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_alt_ref_aq.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_aq_360.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_aq_complexity.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_aq_cyclicrefresh.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_aq_variance.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_bitstream.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_context_tree.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_cost.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_dct.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_encodeframe.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_encodemb.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_encodemv.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_encoder.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_ethread.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_extend.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_firstpass.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_frame_scale.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_lookahead.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_mbgraph.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_mcomp.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_multi_thread.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_noise_estimate.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_picklpf.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_pickmode.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_quantize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_ratectrl.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_rd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_rdopt.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_resize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_segmentation.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_skin_detection.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_speed_features.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_subexp.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_svc_layercontext.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_temporal_filter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_tokenize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/encoder/vp9_treewriter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/vp9_cx_iface.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vp9/vp9_dx_iface.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx/src/vpx_codec.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx/src/vpx_decoder.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx/src/vpx_encoder.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx/src/vpx_image.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/avg_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/fdct_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/fwd_txfm_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/hadamard_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct16x16_1_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct16x16_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct32x32_135_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct32x32_1_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct32x32_34_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct32x32_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct4x4_1_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct4x4_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct8x8_1_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/idct8x8_add_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/intrapred_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/loopfilter_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/sad4d_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/sad_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/subpel_variance_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/subtract_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/variance_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/vpx_convolve8_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/vpx_convolve_avg_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/vpx_convolve_copy_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/arm/vpx_convolve_neon.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/avg.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/bitreader.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/bitreader_buffer.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/bitwriter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/bitwriter_buffer.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/fwd_txfm.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/intrapred.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/inv_txfm.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/loopfilter.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/prob.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/psnr.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/quantize.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/sad.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/subtract.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/sum_squares.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/variance.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/vpx_convolve.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_dsp/vpx_dsp_rtcd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_mem/vpx_mem.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_ports/arm_cpudetect.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_scale/generic/gen_scalers.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_scale/generic/vpx_scale.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_scale/generic/yv12config.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_scale/generic/yv12extend.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_scale/vpx_scale_rtcd.c
    ${ANDROID_ROOT}/external/libvpx/libvpx/vpx_util/vpx_thread.c
    ${ANDROID_ROOT}/external/libvpx/config/arm64/vpx_config.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/libvpx/libvpx'
# Raw param [1] = '-Iexternal/libvpx/config/arm64'
# Raw param [2] = '-Iexternal/libvpx'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = ''
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
    "${ANDROID_ROOT}/external/libvpx/libvpx"
    "${ANDROID_ROOT}/external/libvpx/config/arm64"
    "${ANDROID_ROOT}/external/libvpx"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libvpx/libvpx/**/*.h"
    "${ANDROID_ROOT}/external/libvpx/config/arm64/**/*.h"
    "${ANDROID_ROOT}/external/libvpx/**/*.h"
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
# Raw param [0] = '-O3'
# Raw param [1] = '-Wno-unused-parameter'
# Raw param [2] = '-target aarch64-linux-android'
# Raw param [3] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [4] = '-fPIC'
# Raw param [5] = '-D_USING_LIBCXX'
# Raw param [6] = '-flto'
# Raw param [7] = '-fsanitize-cfi-cross-dso'
# Raw param [8] = '-fvisibility=default'
# Raw param [9] = '-fsanitize-blacklist=external/compiler-rt/lib/cfi/cfi_blacklist.txt'
# Raw param [10] = '-fuse-ld=qcld'
# Raw param [11] = '-fsanitize=cfi'
# Raw param [12] = '-fsanitize-trap=all'
# Raw param [13] = '-ftrap-function=abort'
# Raw param [14] = '-fno-sanitize-trap=cfi'
# Raw param [15] = '-fsanitize-blacklist=external/libvpx/cfi_blacklist.txt'
# FLAG '-O3' became -O3
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-flto' became -flto
# FLAG '-fsanitize-cfi-cross-dso' became -fsanitize-cfi-cross-dso
# FLAG '-fvisibility=default' became -fvisibility=default
# FLAG '-fsanitize-blacklist=external/compiler-rt/lib/cfi/cfi_blacklist.txt' became -fsanitize-blacklist=external/compiler-rt/lib/cfi/cfi_blacklist.txt
# FLAG '-fuse-ld=qcld' became -fuse-ld=qcld
# FLAG '-fsanitize=cfi' became -fsanitize=cfi
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
# FLAG '-fno-sanitize-trap=cfi' became -fno-sanitize-trap=cfi
# FLAG '-fsanitize-blacklist=external/libvpx/cfi_blacklist.txt' became -fsanitize-blacklist=external/libvpx/cfi_blacklist.txt
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -flto")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-cfi-cross-dso")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=default")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-blacklist=external/compiler-rt/lib/cfi/cfi_blacklist.txt")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fuse-ld=qcld")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=cfi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-sanitize-trap=cfi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-blacklist=external/libvpx/cfi_blacklist.txt")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -flto")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-cfi-cross-dso")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=default")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-blacklist=external/compiler-rt/lib/cfi/cfi_blacklist.txt")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fuse-ld=qcld")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=cfi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-trap=all")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ftrap-function=abort")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-sanitize-trap=cfi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-blacklist=external/libvpx/cfi_blacklist.txt")

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


add_executable(libvpx ${SOURCE_FILES})
