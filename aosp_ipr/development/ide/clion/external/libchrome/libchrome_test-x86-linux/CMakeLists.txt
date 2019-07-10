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
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/valgrind/include -Iexternal/valgrind'
# Raw param [1] = '-Iexternal/libchrome'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/googletest/googletest/include'
# Raw param [8] = '-Iexternal/googletest/googlemock/include'
# Raw param [9] = '-Iexternal/libchrome'
# Raw param [10] = '-Isystem/core/base/include'
# Raw param [11] = '-Iexternal/libevent/include'
# Raw param [12] = '-Iexternal/libcxx/include'
# Raw param [13] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX86ClangCflags} = '-fno-exceptions -Wno-multichar -Wa,--noexecstack -fPIC -no-canonical-prefixes -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -O2 -g -fno-strict-aliasing --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/sysroot -fstack-protector-strong -msse3 -m32 -march=prescott -D_FILE_OFFSET_BITS=64 -D_LARGEFILE_SOURCE=1'
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
# Raw param [17] = '-msse3'
# Raw param [18] = '-m32'
# Raw param [19] = '-march=prescott'
# Raw param [20] = '-D_FILE_OFFSET_BITS=64'
# Raw param [21] = '-D_LARGEFILE_SOURCE=1'
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
# FLAG '-msse3' became -msse3
# FLAG '-m32' became -m32
# FLAG '-march=prescott' became -march=prescott
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=prescott")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=prescott")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-Wno-unused-function'
# Raw param [4] = '-Wno-missing-field-initializers'
# Raw param [5] = '-DUNIT_TEST'
# Raw param [6] = '-D__ANDROID_HOST__'
# Raw param [7] = '-DDONT_EMBED_BUILD_METADATA'
# Raw param [8] = '-Wno-error=unused-lambda-capture'
# Raw param [9] = '-target i686-linux-gnu'
# Raw param [10] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [11] = '-fPIE'
# Raw param [12] = '-DGTEST_HAS_STD_STRING'
# Raw param [13] = '-O0'
# Raw param [14] = '-g'
# Raw param [15] = '-DGTEST_OS_LINUX'
# Raw param [16] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-DUNIT_TEST' became -DUNIT_TEST
# FLAG '-D__ANDROID_HOST__' became -D__ANDROID_HOST__
# FLAG '-DDONT_EMBED_BUILD_METADATA' became -DDONT_EMBED_BUILD_METADATA
# FLAG '-Wno-error=unused-lambda-capture' became -Wno-error=unused-lambda-capture
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-O0' became -O0
# FLAG '-g' became -g
# FLAG '-DGTEST_OS_LINUX' became -DGTEST_OS_LINUX
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUNIT_TEST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_HOST__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUNIT_TEST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_HOST__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX")
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
# Raw param [2] = '${config.LinuxClangCppflags} ${config.LinuxX86ClangCppflags}'
# Raw param [3] = '-nostdinc++'
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
# variable ${config.LinuxClangCppflags} ${config.LinuxX86ClangCppflags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8 -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward -isystem prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8'
# Raw param [2] = '-isystem'
# Raw param [3] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward'
# Raw param [4] = '-isystem'
# Raw param [5] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32'
# FLAG '-nostdinc++' became -nostdinc++
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/backward/**/*.h"
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.15-4.8/x86_64-linux/include/c++/4.8/x86_64-linux/32/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++14")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
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


add_executable(libchrome_test ${SOURCE_FILES})
