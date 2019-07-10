# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libhevcdec)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_quant_tables.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_inter_pred_filters.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_weighted_pred.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_padding.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_deblk_edge_filter.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_deblk_tables.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_cabac_tables.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_common_tables.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_intra_pred_filters.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_intra_pred_filters.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_mem_fns.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_sao.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_trans_tables.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_itrans.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_itrans_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_iquant_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_iquant_itrans_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_itrans_recon_32x32.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_itrans_recon_16x16.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_itrans_recon_8x8.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_itrans_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_iquant_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_iquant_itrans_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_recon.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_itrans_recon_16x16.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_chroma_itrans_recon_8x8.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_buf_mgr.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_disp_mgr.c
    ${ANDROID_ROOT}/external/libhevc/common/ihevc_dpb_mgr.c
    ${ANDROID_ROOT}/external/libhevc/common/ithread.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_version.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_api.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_decode.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_nal.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_bitstream.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_parse_headers.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_parse_slice_header.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_parse_slice.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_parse_residual.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_cabac.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_intra_pred_mode_prediction.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_process_slice.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_utils.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_job_queue.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_ref_list.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_get_mv.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_mv_pred.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_mv_merge.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_iquant_itrans_recon_ctb.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_itrans_recon_dc.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_common_tables.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_boundary_strength.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_deblk.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_inter_pred.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_sao.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_ilf_padding.c
    ${ANDROID_ROOT}/external/libhevc/decoder/ihevcd_fmt_conv.c
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_function_selector.c
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_function_selector_noneon.c
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_function_selector_a9q.c
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_ref_substitution_a9q.c
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_filters_neon_intr.c
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_weighted_pred_neon_intr.c
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_mem_fns.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_itrans_recon_32x32.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_weighted_pred_bi_default.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_weighted_pred_bi.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_weighted_pred_uni.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_deblk_luma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_deblk_luma_vert.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_deblk_chroma_vert.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_deblk_chroma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_band_offset_luma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_band_offset_chroma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class0.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class0_chroma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class1.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class1_chroma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class2.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class2_chroma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class3.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_sao_edge_offset_class3_chroma.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_luma_horz_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_filters_luma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_filters_luma_vert.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_horz_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_vert.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_vert_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_vert_w16inp.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_vert_w16inp_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_filters_luma_vert_w16inp.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_luma_vert_w16inp_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_luma_copy_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_luma_copy.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_copy.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_inter_pred_chroma_copy_w16out.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_itrans_recon_4x4_ttype1.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_itrans_recon_4x4.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_itrans_recon_8x8.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_itrans_recon_16x16.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_planar.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_dc.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_ver.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_mode2.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_mode_18_34.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_filters_chroma_mode_11_to_17.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_filters_chroma_mode_19_to_25.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_mode_3_to_9.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_chroma_mode_27_to_33.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_planar.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_horz.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_mode2.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_mode_27_to_33.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_mode_18_34.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_vert.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_dc.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_filters_luma_mode_11_to_17.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_filters_luma_mode_19_to_25.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_intra_pred_luma_mode_3_to_9.s
    ${ANDROID_ROOT}/external/libhevc/common/arm/ihevc_padding.s
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_itrans_recon_dc_luma.s
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_itrans_recon_dc_chroma.s
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_fmt_conv_420sp_to_420p.s
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_fmt_conv_420sp_to_420sp.s
    ${ANDROID_ROOT}/external/libhevc/decoder/arm/ihevcd_fmt_conv_420sp_to_rgba8888.s
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/libhevc/decoder -Iexternal/libhevc/common'
# Raw param [1] = '-Iexternal/libhevc/decoder/arm -Iexternal/libhevc/common/arm'
# Raw param [2] = '-Iexternal/libhevc'
# Raw param [3] = '${config.ArmClangArmCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
# variable ${config.ArmClangArmCflags} = '-O2 -fomit-frame-pointer -fstrict-aliasing'
# Raw param [0] = '-O2'
# Raw param [1] = '-fomit-frame-pointer'
# Raw param [2] = '-fstrict-aliasing'
# FLAG '-O2' became -O2
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-fstrict-aliasing' became -fstrict-aliasing
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
    "${ANDROID_ROOT}/external/libhevc/decoder -Iexternal/libhevc/common"
    "${ANDROID_ROOT}/external/libhevc/decoder/arm -Iexternal/libhevc/common/arm"
    "${ANDROID_ROOT}/external/libhevc"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libhevc/decoder -Iexternal/libhevc/common/**/*.h"
    "${ANDROID_ROOT}/external/libhevc/decoder/arm -Iexternal/libhevc/common/arm/**/*.h"
    "${ANDROID_ROOT}/external/libhevc/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstrict-aliasing")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstrict-aliasing")
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
# Raw param [0] = '-D_LIB'
# Raw param [1] = '-DMULTICORE'
# Raw param [2] = '-fPIC'
# Raw param [3] = '-marm'
# Raw param [4] = '-O3'
# Raw param [5] = '-DANDROID'
# Raw param [6] = '-DDISABLE_NEONINTR'
# Raw param [7] = '-DARM'
# Raw param [8] = '-DARMGCC'
# Raw param [9] = '-fno-tree-vectorize'
# Raw param [10] = '-DDISABLE_NEON'
# Raw param [11] = '-DDEFAULT_ARCH=D_ARCH_ARM_NONEON'
# Raw param [12] = '-UDISABLE_NEON'
# Raw param [13] = '-UDEFAULT_ARCH'
# Raw param [14] = '-DDEFAULT_ARCH=D_ARCH_ARM_A9Q'
# Raw param [15] = '-target arm-linux-androideabi'
# Raw param [16] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [17] = '-fPIC'
# Raw param [18] = '-D_USING_LIBCXX'
# FLAG '-D_LIB' became -D_LIB
# FLAG '-DMULTICORE' became -DMULTICORE
# FLAG '-fPIC' became -fPIC
# FLAG '-marm' became -marm
# FLAG '-O3' became -O3
# FLAG '-DANDROID' became -DANDROID
# FLAG '-DDISABLE_NEONINTR' became -DDISABLE_NEONINTR
# FLAG '-DARM' became -DARM
# FLAG '-DARMGCC' became -DARMGCC
# FLAG '-fno-tree-vectorize' became -fno-tree-vectorize
# FLAG '-DDISABLE_NEON' became -DDISABLE_NEON
# FLAG '-DDEFAULT_ARCH=D_ARCH_ARM_NONEON' became -DDEFAULT_ARCH=D_ARCH_ARM_NONEON
# FLAG '-UDISABLE_NEON' became -UDISABLE_NEON
# FLAG '-UDEFAULT_ARCH' became -UDEFAULT_ARCH
# FLAG '-DDEFAULT_ARCH=D_ARCH_ARM_A9Q' became -DDEFAULT_ARCH=D_ARCH_ARM_A9Q
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LIB")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DMULTICORE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -marm")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_NEONINTR")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DARM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DARMGCC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-tree-vectorize")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_NEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEFAULT_ARCH=D_ARCH_ARM_NONEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UDISABLE_NEON")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UDEFAULT_ARCH")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEFAULT_ARCH=D_ARCH_ARM_A9Q")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIB")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DMULTICORE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -marm")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_NEONINTR")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DARM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DARMGCC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-tree-vectorize")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_NEON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEFAULT_ARCH=D_ARCH_ARM_NONEON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDISABLE_NEON")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDEFAULT_ARCH")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEFAULT_ARCH=D_ARCH_ARM_A9Q")
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


add_executable(libhevcdec ${SOURCE_FILES})
