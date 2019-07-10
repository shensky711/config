# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcrypto)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-gcc")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/bin/x86_64-w64-mingw32-g++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/boringssl/err_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_bitstr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_bool.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_d2i_fp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_dup.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_gentm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_i2d_fp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_mbstr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_object.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_octet.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_print.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_strnid.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_time.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_type.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_utctm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_utf8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn1_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn1_par.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn_pack.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_string.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_dec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_enc.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_fre.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_new.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_typ.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_utl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/time_support.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/base64/base64.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/bio.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/bio_mem.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/connect.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/fd.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/file.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/hexdump.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/pair.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/printf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/socket.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/socket_helper.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bn_extra/bn_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bn_extra/convert.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/buf/buf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/asn1_compat.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/ber.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/cbb.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/cbs.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/chacha/chacha.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/cipher_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/derive_key.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_aesctrhmac.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_aesgcmsiv.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_chacha20poly1305.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_null.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_rc2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_rc4.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_ssl3.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_tls.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/tls_cbc.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cmac/cmac.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/conf/conf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-aarch64-linux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-arm-linux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-arm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-intel.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-ppc64le.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/crypto.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/curve25519.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/spake25519.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/x25519-x86_64.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/check.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/dh.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/dh_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/params.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/digest_extra/digest_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dsa/dsa.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dsa/dsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ec_extra/ec_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ecdh/ecdh.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ecdsa_extra/ecdsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/engine/engine.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/err/err.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/digestsign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp_ctx.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_dsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ec_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ed25519.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ed25519_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_rsa.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_rsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/pbkdf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/print.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/scrypt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/sign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ex_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/fipsmodule/bcm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/fipsmodule/is_fips.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/hkdf/hkdf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/lhash/lhash.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/mem.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/obj/obj.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/obj/obj_xref.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_all.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_oth.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_pk8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_pkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_xaux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs7/pkcs7.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs7/pkcs7_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/p5_pbev2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/pkcs8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/pkcs8_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305_arm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305_vec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pool/pool.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/deterministic.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/forkunsafe.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/fuchsia.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/rand_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/windows.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rc4/rc4.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/refcount_c11.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/refcount_lock.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rsa_extra/rsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/stack/stack.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_none.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_pthread.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_win.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_digest.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_sign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_strex.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_verify.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/algorithm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/asn1_gen.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/by_dir.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/by_file.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/i2d_pr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/rsa_pss.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_crl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_x509a.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_att.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_cmp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_d2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_def.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_ext.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_lu.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_obj.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_r2x.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_set.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_trs.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_txt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_v3.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_vfy.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_vpm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509cset.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509name.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509rset.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509spki.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_algor.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_all.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_attrib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_crl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_exten.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_name.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_pkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_pubkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_sig.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_spki.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_val.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_x509a.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_cache.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_map.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_node.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_tree.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_akey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_akeya.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_alt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_bcons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_bitst.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_conf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_cpols.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_crld.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_extku.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_genn.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_ia5.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_ncons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pci.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pcia.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pcons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pku.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pmaps.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_prn.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_purp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_skey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_sxnet.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_utl.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/boringssl/src/include'
# Raw param [1] = '-Iexternal/boringssl/src/include -Iexternal/boringssl/src/crypto'
# Raw param [2] = '-Iexternal/boringssl'
# Raw param [3] = ''
# Raw param [4] = '${config.WindowsCflags} ${config.WindowsX86Cflags}'
# Raw param [5] = '${config.CommonGlobalCflags}'
# Raw param [6] = '${config.HostGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/boringssl/src/include'
# variable ${config.WindowsCflags} ${config.WindowsX86Cflags} = '-fno-exceptions -Wno-multichar -DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0600 -DWINVER=0x0600 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -O2 -g -fno-strict-aliasing -m32'
# Raw param [0] = '-fno-exceptions'
# Raw param [1] = '-Wno-multichar'
# Raw param [2] = '-DUSE_MINGW'
# Raw param [3] = '-DWIN32_LEAN_AND_MEAN'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-D__STDC_FORMAT_MACROS'
# Raw param [6] = '-D__STDC_CONSTANT_MACROS'
# Raw param [7] = '-D__USE_MINGW_ANSI_STDIO=1'
# Raw param [8] = '-D_WIN32_WINNT=0x0600'
# Raw param [9] = '-DWINVER=0x0600'
# Raw param [10] = '-D_FILE_OFFSET_BITS=64'
# Raw param [11] = '--sysroot'
# Raw param [12] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32'
# Raw param [13] = '-O2'
# Raw param [14] = '-g'
# Raw param [15] = '-fno-strict-aliasing'
# Raw param [16] = '-m32'
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-DUSE_MINGW' became -DUSE_MINGW
# FLAG '-DWIN32_LEAN_AND_MEAN' became -DWIN32_LEAN_AND_MEAN
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__USE_MINGW_ANSI_STDIO=1' became -D__USE_MINGW_ANSI_STDIO=1
# FLAG '-D_WIN32_WINNT=0x0600' became -D_WIN32_WINNT=0x0600
# FLAG '-DWINVER=0x0600' became -DWINVER=0x0600
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-O2' became -O2
# FLAG '-g' became -g
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-m32' became -m32
# variable ${config.CommonGlobalCflags} = '-DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -DNDEBUG -UDEBUG -fdebug-prefix-map=/proc/self/cwd='
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
# variable ${config.HostGlobalCflags} = ''
# Raw param [0] = ''
include_directories( 
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto"
    "${ANDROID_ROOT}/external/boringssl"
    "${ANDROID_ROOT}/external/boringssl/src/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_MINGW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_WIN32_WINNT=0x0600")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWINVER=0x0600")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_MINGW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_WIN32_WINNT=0x0600")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWINVER=0x0600")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
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
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/usr/include")

# CFLAGS:
# Raw param [0] = '-fvisibility=hidden'
# Raw param [1] = '-DBORINGSSL_SHARED_LIBRARY'
# Raw param [2] = '-DBORINGSSL_IMPLEMENTATION'
# Raw param [3] = '-DOPENSSL_SMALL'
# Raw param [4] = '-D_XOPEN_SOURCE=700'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-DBORINGSSL_ANDROID_SYSTEM'
# Raw param [7] = '-DOPENSSL_NO_ASM'
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DBORINGSSL_SHARED_LIBRARY' became -DBORINGSSL_SHARED_LIBRARY
# FLAG '-DBORINGSSL_IMPLEMENTATION' became -DBORINGSSL_IMPLEMENTATION
# FLAG '-DOPENSSL_SMALL' became -DOPENSSL_SMALL
# FLAG '-D_XOPEN_SOURCE=700' became -D_XOPEN_SOURCE=700
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DBORINGSSL_ANDROID_SYSTEM' became -DBORINGSSL_ANDROID_SYSTEM
# FLAG '-DOPENSSL_NO_ASM' became -DOPENSSL_NO_ASM
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPENSSL_NO_ASM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPENSSL_NO_ASM")

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
# Raw param [0] = '-std=gnu++11'
# Raw param [1] = '${config.CommonGlobalCppflags}'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Werror'
# Raw param [4] = ''
# FLAG '-std=gnu++11' became -std=gnu++11
# variable ${config.CommonGlobalCppflags} = '-Wsign-promo'
# Raw param [0] = '-Wsign-promo'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.WindowsIncludeFlags}'
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
# variable ${config.WindowsIncludeFlags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include -isystem prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_deprecated'
# Raw param [0] = '-Ilibnativehelper/include_deprecated'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/lib/gcc/x86_64-w64-mingw32/4.8.3/include/**/*.h"
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


add_executable(libcrypto ${SOURCE_FILES})
