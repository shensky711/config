# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libchrome_test)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libchrome/base/at_exit_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/atomicops_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64url_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/bind_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/bits_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/build_time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_helpers_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_list_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/cancelable_callback_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/command_line_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/cpu_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/debugger_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/leak_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/task_annotator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/environment_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/file_version_info_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/dir_reader_posix_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_watcher_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/important_file_writer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/scoped_temp_dir_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/gmock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/guid_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/id_map_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_parser_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_reader_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_value_converter_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_value_serializer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_writer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/string_escape_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/lazy_instance_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/logging_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/md5_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/aligned_memory_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/linked_ptr_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted_memory_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/scoped_vector_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/singleton_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/weak_ptr_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_test.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_task_runner_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/bucket_ranges_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/field_trial_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/metrics_hashes_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_base_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_macros_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_snapshot_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_histogram_allocator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_memory_allocator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_sample_map_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_map_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_vector_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sparse_histogram_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/statistics_recorder_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/numerics/safe_numerics_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/observer_list_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/optional_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/pickle_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/file_descriptor_shuffle_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/unix_domain_socket_linux_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_metrics_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/profiler/tracked_time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/rand_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/scoped_clear_errno_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/scoped_generic_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/security_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sequence_checker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sha1_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/stl_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/pattern_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string16_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_number_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_piece_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/stringprintf_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_split_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/sys_string_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/utf_string_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/cancellation_flag_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/condition_variable_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/lock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/waitable_event_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sync_socket_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sys_info_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task/cancelable_task_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_runner_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/scheduler_lock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence_sort_key_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/task_traits.cc
    ${ANDROID_ROOT}/external/libchrome/base/template_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/multiprocess_test.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/multiprocess_test_android.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/opaque_ref_counted.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/scoped_locale.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/sequenced_worker_pool_owner.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_io_thread.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_pending_task.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_simple_task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_switches.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_timeouts.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/trace_event_analyzer.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/non_thread_safe_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/platform_thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/simple_thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_checker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_collision_warner_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_id_name_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_storage_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/worker_pool_posix_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/worker_pool_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/pr_time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/hi_res_timer_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/timer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_allocation_context_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_stack_frame_deduplicator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_type_name_deduplicator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_allocator_dump_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_dump_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/process_memory_dump_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_config_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_argument_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_synthetic_delay_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/tracked_objects_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/tuple_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/values_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/version_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/vlog_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/testing/multiprocess_func_list.cc
    ${ANDROID_ROOT}/external/libchrome/testrunner.cc
    ${ANDROID_ROOT}/external/libchrome/crypto/secure_hash_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/crypto/sha2_unittest.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/valgrind/include -Iexternal/valgrind'
# Raw param [1] = '-Iexternal/libchrome'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv7ANeonCflags} ${config.ArmClangGenericCflags}'
# Raw param [7] = '-Iexternal/googletest/googletest/include'
# Raw param [8] = '-Iexternal/googletest/googlemock/include'
# Raw param [9] = '-Iexternal/libchrome'
# Raw param [10] = '-Isystem/core/base/include'
# Raw param [11] = '-Iexternal/libevent/include'
# Raw param [12] = '-Iexternal/libcxx/include'
# Raw param [13] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/valgrind/include -Iexternal/valgrind"
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/external/libevent/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/valgrind/include -Iexternal/valgrind/**/*.h"
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/external/libevent/include/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-Wno-unused-function'
# Raw param [4] = '-Wno-missing-field-initializers'
# Raw param [5] = '-DUNIT_TEST'
# Raw param [6] = '-DDONT_EMBED_BUILD_METADATA'
# Raw param [7] = '-Wno-error=unused-lambda-capture'
# Raw param [8] = '-target arm-linux-androideabi'
# Raw param [9] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [10] = '-fPIE'
# Raw param [11] = '-DGTEST_HAS_STD_STRING'
# Raw param [12] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [13] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-DUNIT_TEST' became -DUNIT_TEST
# FLAG '-DDONT_EMBED_BUILD_METADATA' became -DDONT_EMBED_BUILD_METADATA
# FLAG '-Wno-error=unused-lambda-capture' became -Wno-error=unused-lambda-capture
# FLAG '-target arm-linux-androideabi' became -target arm-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUNIT_TEST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target arm-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUNIT_TEST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target arm-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX_ANDROID")
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


add_executable(libchrome_test ${SOURCE_FILES})
