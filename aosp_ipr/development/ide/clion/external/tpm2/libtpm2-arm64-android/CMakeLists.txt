# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libtpm2)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/tpm2/ActivateCredential.c
    ${ANDROID_ROOT}/external/tpm2/AlgorithmCap.c
    ${ANDROID_ROOT}/external/tpm2/Attest_spt.c
    ${ANDROID_ROOT}/external/tpm2/Bits.c
    ${ANDROID_ROOT}/external/tpm2/Cancel.c
    ${ANDROID_ROOT}/external/tpm2/Certify.c
    ${ANDROID_ROOT}/external/tpm2/CertifyCreation.c
    ${ANDROID_ROOT}/external/tpm2/ChangeEPS.c
    ${ANDROID_ROOT}/external/tpm2/ChangePPS.c
    ${ANDROID_ROOT}/external/tpm2/Clear.c
    ${ANDROID_ROOT}/external/tpm2/ClearControl.c
    ${ANDROID_ROOT}/external/tpm2/Clock.c
    ${ANDROID_ROOT}/external/tpm2/ClockRateAdjust.c
    ${ANDROID_ROOT}/external/tpm2/ClockSet.c
    ${ANDROID_ROOT}/external/tpm2/CommandAudit.c
    ${ANDROID_ROOT}/external/tpm2/CommandCodeAttributes.c
    ${ANDROID_ROOT}/external/tpm2/CommandDispatcher.c
    ${ANDROID_ROOT}/external/tpm2/Commit.c
    ${ANDROID_ROOT}/external/tpm2/ContextLoad.c
    ${ANDROID_ROOT}/external/tpm2/ContextSave.c
    ${ANDROID_ROOT}/external/tpm2/Context_spt.c
    ${ANDROID_ROOT}/external/tpm2/CpriCryptPri.c
    ${ANDROID_ROOT}/external/tpm2/CpriECC.c
    ${ANDROID_ROOT}/external/tpm2/CpriHash.c
    ${ANDROID_ROOT}/external/tpm2/CpriMisc.c
    ${ANDROID_ROOT}/external/tpm2/CpriRNG.c
    ${ANDROID_ROOT}/external/tpm2/CpriRSA.c
    ${ANDROID_ROOT}/external/tpm2/CpriSym.c
    ${ANDROID_ROOT}/external/tpm2/Create.c
    ${ANDROID_ROOT}/external/tpm2/CreatePrimary.c
    ${ANDROID_ROOT}/external/tpm2/CryptSelfTest.c
    ${ANDROID_ROOT}/external/tpm2/CryptUtil.c
    ${ANDROID_ROOT}/external/tpm2/DA.c
    ${ANDROID_ROOT}/external/tpm2/DRTM.c
    ${ANDROID_ROOT}/external/tpm2/DictionaryAttackLockReset.c
    ${ANDROID_ROOT}/external/tpm2/DictionaryAttackParameters.c
    ${ANDROID_ROOT}/external/tpm2/Duplicate.c
    ${ANDROID_ROOT}/external/tpm2/ECC_Parameters.c
    ${ANDROID_ROOT}/external/tpm2/ECDH_KeyGen.c
    ${ANDROID_ROOT}/external/tpm2/ECDH_ZGen.c
    ${ANDROID_ROOT}/external/tpm2/EC_Ephemeral.c
    ${ANDROID_ROOT}/external/tpm2/EncryptDecrypt.c
    ${ANDROID_ROOT}/external/tpm2/Entity.c
    ${ANDROID_ROOT}/external/tpm2/Entropy.c
    ${ANDROID_ROOT}/external/tpm2/EventSequenceComplete.c
    ${ANDROID_ROOT}/external/tpm2/EvictControl.c
    ${ANDROID_ROOT}/external/tpm2/ExecCommand.c
    ${ANDROID_ROOT}/external/tpm2/FieldUpgradeData.c
    ${ANDROID_ROOT}/external/tpm2/FieldUpgradeStart.c
    ${ANDROID_ROOT}/external/tpm2/FirmwareRead.c
    ${ANDROID_ROOT}/external/tpm2/FlushContext.c
    ${ANDROID_ROOT}/external/tpm2/GetCapability.c
    ${ANDROID_ROOT}/external/tpm2/GetCommandAuditDigest.c
    ${ANDROID_ROOT}/external/tpm2/GetCommandCodeString.c
    ${ANDROID_ROOT}/external/tpm2/GetRandom.c
    ${ANDROID_ROOT}/external/tpm2/GetSessionAuditDigest.c
    ${ANDROID_ROOT}/external/tpm2/GetTestResult.c
    ${ANDROID_ROOT}/external/tpm2/GetTime.c
    ${ANDROID_ROOT}/external/tpm2/Global.c
    ${ANDROID_ROOT}/external/tpm2/HMAC.c
    ${ANDROID_ROOT}/external/tpm2/HMAC_Start.c
    ${ANDROID_ROOT}/external/tpm2/Handle.c
    ${ANDROID_ROOT}/external/tpm2/HandleProcess.c
    ${ANDROID_ROOT}/external/tpm2/Hash.c
    ${ANDROID_ROOT}/external/tpm2/HashSequenceStart.c
    ${ANDROID_ROOT}/external/tpm2/Hierarchy.c
    ${ANDROID_ROOT}/external/tpm2/HierarchyChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/HierarchyControl.c
    ${ANDROID_ROOT}/external/tpm2/Import.c
    ${ANDROID_ROOT}/external/tpm2/IncrementalSelfTest.c
    ${ANDROID_ROOT}/external/tpm2/Load.c
    ${ANDROID_ROOT}/external/tpm2/LoadExternal.c
    ${ANDROID_ROOT}/external/tpm2/Locality.c
    ${ANDROID_ROOT}/external/tpm2/LocalityPlat.c
    ${ANDROID_ROOT}/external/tpm2/MakeCredential.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ActivateCredential.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Certify.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_CertifyCreation.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ChangeEPS.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ChangePPS.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Clear.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ClearControl.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ClockRateAdjust.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ClockSet.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Commit.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ContextLoad.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ContextSave.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Create.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_CreatePrimary.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_DictionaryAttackLockReset.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_DictionaryAttackParameters.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Duplicate.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ECC_Parameters.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ECDH_KeyGen.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ECDH_ZGen.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_EC_Ephemeral.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_EncryptDecrypt.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_EventSequenceComplete.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_EvictControl.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_FirmwareRead.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_FlushContext.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetCapability.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetCommandAuditDigest.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetRandom.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetSessionAuditDigest.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetTestResult.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_GetTime.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_HMAC.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_HMAC_Start.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Hash.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_HashSequenceStart.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_HierarchyChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_HierarchyControl.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Import.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_IncrementalSelfTest.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Load.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_LoadExternal.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_MakeCredential.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_Certify.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_ChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_DefineSpace.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_Extend.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_GlobalWriteLock.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_Increment.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_Read.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_ReadLock.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_ReadPublic.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_SetBits.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_UndefineSpace.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_UndefineSpaceSpecial.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_Write.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_NV_WriteLock.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ObjectChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_Allocate.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_Event.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_Extend.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_Read.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_Reset.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_SetAuthPolicy.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PCR_SetAuthValue.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PP_Commands.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyAuthValue.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyAuthorize.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyCommandCode.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyCounterTimer.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyCpHash.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyDuplicationSelect.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyGetDigest.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyLocality.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyNV.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyNameHash.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyNvWritten.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyOR.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyPCR.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyPassword.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyPhysicalPresence.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyRestart.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicySecret.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicySigned.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_PolicyTicket.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Quote.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_RSA_Decrypt.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_RSA_Encrypt.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ReadClock.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ReadPublic.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Rewrap.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SelfTest.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SequenceComplete.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SequenceUpdate.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SetAlgorithmSet.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SetCommandCodeAuditStatus.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_SetPrimaryPolicy.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Shutdown.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Sign.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_StartAuthSession.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Startup.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_StirRandom.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_TestParms.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_Unseal.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_VerifySignature.c
    ${ANDROID_ROOT}/external/tpm2/Marshal_ZGen_2Phase.c
    ${ANDROID_ROOT}/external/tpm2/Manufacture.c
    ${ANDROID_ROOT}/external/tpm2/MathFunctions.c
    ${ANDROID_ROOT}/external/tpm2/MemoryLib.c
    ${ANDROID_ROOT}/external/tpm2/NV.c
    ${ANDROID_ROOT}/external/tpm2/NVMem.c
    ${ANDROID_ROOT}/external/tpm2/NV_Certify.c
    ${ANDROID_ROOT}/external/tpm2/NV_ChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/NV_DefineSpace.c
    ${ANDROID_ROOT}/external/tpm2/NV_Extend.c
    ${ANDROID_ROOT}/external/tpm2/NV_GlobalWriteLock.c
    ${ANDROID_ROOT}/external/tpm2/NV_Increment.c
    ${ANDROID_ROOT}/external/tpm2/NV_Read.c
    ${ANDROID_ROOT}/external/tpm2/NV_ReadLock.c
    ${ANDROID_ROOT}/external/tpm2/NV_ReadPublic.c
    ${ANDROID_ROOT}/external/tpm2/NV_SetBits.c
    ${ANDROID_ROOT}/external/tpm2/NV_UndefineSpace.c
    ${ANDROID_ROOT}/external/tpm2/NV_UndefineSpaceSpecial.c
    ${ANDROID_ROOT}/external/tpm2/NV_Write.c
    ${ANDROID_ROOT}/external/tpm2/NV_WriteLock.c
    ${ANDROID_ROOT}/external/tpm2/NV_spt.c
    ${ANDROID_ROOT}/external/tpm2/Object.c
    ${ANDROID_ROOT}/external/tpm2/ObjectChangeAuth.c
    ${ANDROID_ROOT}/external/tpm2/Object_spt.c
    ${ANDROID_ROOT}/external/tpm2/PCR.c
    ${ANDROID_ROOT}/external/tpm2/PCR_Allocate.c
    ${ANDROID_ROOT}/external/tpm2/PCR_Event.c
    ${ANDROID_ROOT}/external/tpm2/PCR_Extend.c
    ${ANDROID_ROOT}/external/tpm2/PCR_Read.c
    ${ANDROID_ROOT}/external/tpm2/PCR_Reset.c
    ${ANDROID_ROOT}/external/tpm2/PCR_SetAuthPolicy.c
    ${ANDROID_ROOT}/external/tpm2/PCR_SetAuthValue.c
    ${ANDROID_ROOT}/external/tpm2/PP.c
    ${ANDROID_ROOT}/external/tpm2/PPPlat.c
    ${ANDROID_ROOT}/external/tpm2/PP_Commands.c
    ${ANDROID_ROOT}/external/tpm2/PlatformData.c
    ${ANDROID_ROOT}/external/tpm2/PolicyAuthValue.c
    ${ANDROID_ROOT}/external/tpm2/PolicyAuthorize.c
    ${ANDROID_ROOT}/external/tpm2/PolicyCommandCode.c
    ${ANDROID_ROOT}/external/tpm2/PolicyCounterTimer.c
    ${ANDROID_ROOT}/external/tpm2/PolicyCpHash.c
    ${ANDROID_ROOT}/external/tpm2/PolicyDuplicationSelect.c
    ${ANDROID_ROOT}/external/tpm2/PolicyGetDigest.c
    ${ANDROID_ROOT}/external/tpm2/PolicyLocality.c
    ${ANDROID_ROOT}/external/tpm2/PolicyNV.c
    ${ANDROID_ROOT}/external/tpm2/PolicyNameHash.c
    ${ANDROID_ROOT}/external/tpm2/PolicyNvWritten.c
    ${ANDROID_ROOT}/external/tpm2/PolicyOR.c
    ${ANDROID_ROOT}/external/tpm2/PolicyPCR.c
    ${ANDROID_ROOT}/external/tpm2/PolicyPassword.c
    ${ANDROID_ROOT}/external/tpm2/PolicyPhysicalPresence.c
    ${ANDROID_ROOT}/external/tpm2/PolicyRestart.c
    ${ANDROID_ROOT}/external/tpm2/PolicySecret.c
    ${ANDROID_ROOT}/external/tpm2/PolicySigned.c
    ${ANDROID_ROOT}/external/tpm2/PolicyTicket.c
    ${ANDROID_ROOT}/external/tpm2/Policy_spt.c
    ${ANDROID_ROOT}/external/tpm2/Power.c
    ${ANDROID_ROOT}/external/tpm2/PowerPlat.c
    ${ANDROID_ROOT}/external/tpm2/PropertyCap.c
    ${ANDROID_ROOT}/external/tpm2/Quote.c
    ${ANDROID_ROOT}/external/tpm2/RSAData.c
    ${ANDROID_ROOT}/external/tpm2/RSAKeySieve.c
    ${ANDROID_ROOT}/external/tpm2/RSA_Decrypt.c
    ${ANDROID_ROOT}/external/tpm2/RSA_Encrypt.c
    ${ANDROID_ROOT}/external/tpm2/ReadClock.c
    ${ANDROID_ROOT}/external/tpm2/ReadPublic.c
    ${ANDROID_ROOT}/external/tpm2/Rewrap.c
    ${ANDROID_ROOT}/external/tpm2/SelfTest.c
    ${ANDROID_ROOT}/external/tpm2/SequenceComplete.c
    ${ANDROID_ROOT}/external/tpm2/SequenceUpdate.c
    ${ANDROID_ROOT}/external/tpm2/Session.c
    ${ANDROID_ROOT}/external/tpm2/SessionProcess.c
    ${ANDROID_ROOT}/external/tpm2/SetAlgorithmSet.c
    ${ANDROID_ROOT}/external/tpm2/SetCommandCodeAuditStatus.c
    ${ANDROID_ROOT}/external/tpm2/SetPrimaryPolicy.c
    ${ANDROID_ROOT}/external/tpm2/Shutdown.c
    ${ANDROID_ROOT}/external/tpm2/Sign.c
    ${ANDROID_ROOT}/external/tpm2/StartAuthSession.c
    ${ANDROID_ROOT}/external/tpm2/Startup.c
    ${ANDROID_ROOT}/external/tpm2/StirRandom.c
    ${ANDROID_ROOT}/external/tpm2/TestParms.c
    ${ANDROID_ROOT}/external/tpm2/Ticket.c
    ${ANDROID_ROOT}/external/tpm2/Time.c
    ${ANDROID_ROOT}/external/tpm2/TpmFail.c
    ${ANDROID_ROOT}/external/tpm2/Unique.c
    ${ANDROID_ROOT}/external/tpm2/Unseal.c
    ${ANDROID_ROOT}/external/tpm2/VerifySignature.c
    ${ANDROID_ROOT}/external/tpm2/ZGen_2Phase.c
    ${ANDROID_ROOT}/external/tpm2/_TPM_Hash_Data.c
    ${ANDROID_ROOT}/external/tpm2/_TPM_Hash_End.c
    ${ANDROID_ROOT}/external/tpm2/_TPM_Hash_Start.c
    ${ANDROID_ROOT}/external/tpm2/_TPM_Init.c
    ${ANDROID_ROOT}/external/tpm2/tpm_generated.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/tpm2/include'
# Raw param [1] = '-Iexternal/tpm2/include/tpm2'
# Raw param [2] = '-Iexternal/tpm2'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/boringssl/src/include'
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
    "${ANDROID_ROOT}/external/tpm2/include"
    "${ANDROID_ROOT}/external/tpm2/include/tpm2"
    "${ANDROID_ROOT}/external/tpm2"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/tpm2/include/**/*.h"
    "${ANDROID_ROOT}/external/tpm2/include/tpm2/**/*.h"
    "${ANDROID_ROOT}/external/tpm2/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Wextra'
# Raw param [2] = '-Werror'
# Raw param [3] = '-Wno-typedef-redefinition'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-Wno-missing-field-initializers'
# Raw param [6] = '-Wno-tautological-compare'
# Raw param [7] = '-Wno-sign-compare'
# Raw param [8] = '-target aarch64-linux-android'
# Raw param [9] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [10] = '-fPIC'
# Raw param [11] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-Wno-typedef-redefinition' became -Wno-typedef-redefinition
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-tautological-compare' became -Wno-tautological-compare
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-tautological-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-tautological-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
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


add_executable(libtpm2 ${SOURCE_FILES})
