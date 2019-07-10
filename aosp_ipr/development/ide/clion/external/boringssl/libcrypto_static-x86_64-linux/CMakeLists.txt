# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcrypto_static)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
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
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/chacha/chacha-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/cipher_extra/aes128gcmsiv-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/cipher_extra/chacha20_poly1305_x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/aes-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/aesni-gcm-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/aesni-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/bsaes-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/ghash-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/md5-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/p256-x86_64-asm.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/rdrand-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/rsaz-avx2.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/sha1-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/sha256-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/sha512-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/vpaes-x86_64.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/x86_64-mont.S
    ${ANDROID_ROOT}/external/boringssl/linux-x86_64/crypto/fipsmodule/x86_64-mont5.S
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/asm/x25519-asm-x86_64.S
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/boringssl/src/include'
# Raw param [1] = '-Iexternal/boringssl/src/include -Iexternal/boringssl/src/crypto'
# Raw param [2] = '-Iexternal/boringssl'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/boringssl/src/include'
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags} = '-fno-exceptions -Wno-multichar -Wa,--noexecstack -fPIC -no-canonical-prefixes -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -O2 -g -fno-strict-aliasing --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot -fstack-protector-strong -m64'
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
# Raw param [17] = '-m64'
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
# FLAG '-m64' became -m64
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
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto"
    "${ANDROID_ROOT}/external/boringssl"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m64")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m64")
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
# Raw param [0] = '-fvisibility=hidden'
# Raw param [1] = '-DBORINGSSL_SHARED_LIBRARY'
# Raw param [2] = '-DBORINGSSL_IMPLEMENTATION'
# Raw param [3] = '-DOPENSSL_SMALL'
# Raw param [4] = '-D_XOPEN_SOURCE=700'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-DBORINGSSL_ANDROID_SYSTEM'
# Raw param [7] = '-DOPENSSL_NO_CXX'
# Raw param [8] = '-target x86_64-linux-gnu'
# Raw param [9] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [10] = '-fPIC'
# Raw param [11] = '-D_USING_LIBCXX'
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DBORINGSSL_SHARED_LIBRARY' became -DBORINGSSL_SHARED_LIBRARY
# FLAG '-DBORINGSSL_IMPLEMENTATION' became -DBORINGSSL_IMPLEMENTATION
# FLAG '-DOPENSSL_SMALL' became -DOPENSSL_SMALL
# FLAG '-D_XOPEN_SOURCE=700' became -D_XOPEN_SOURCE=700
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DBORINGSSL_ANDROID_SYSTEM' became -DBORINGSSL_ANDROID_SYSTEM
# FLAG '-DOPENSSL_NO_CXX' became -DOPENSSL_NO_CXX
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPENSSL_NO_CXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPENSSL_NO_CXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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
# Raw param [2] = '-Wall'
# Raw param [3] = '-Werror'
# Raw param [4] = '${config.LinuxClangCppflags} ${config.LinuxX8664ClangCppflags}'
# Raw param [5] = '-nostdinc++'
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
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# variable ${config.LinuxClangCppflags} ${config.LinuxX8664ClangCppflags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8 -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward'
# Raw param [4] = '-isystem'
# Raw param [5] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux'
# FLAG '-nostdinc++' became -nostdinc++
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
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


add_executable(libcrypto_static ${SOURCE_FILES})
