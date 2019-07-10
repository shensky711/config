# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libchrome)
set(ANDROID_ROOT /home/chenhang/source/M1882_QOF8_base)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-4053586/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libchrome/base/at_exit.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64url.cc
    ${ANDROID_ROOT}/external/libchrome/base/base_switches.cc
    ${ANDROID_ROOT}/external/libchrome/base/bind_helpers.cc
    ${ANDROID_ROOT}/external/libchrome/base/build_time.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_helpers.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_internal.cc
    ${ANDROID_ROOT}/external/libchrome/base/command_line.cc
    ${ANDROID_ROOT}/external/libchrome/base/cpu.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/alias.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/debugger.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/debugger_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/stack_trace.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/stack_trace_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/task_annotator.cc
    ${ANDROID_ROOT}/external/libchrome/base/environment.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_enumerator.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_enumerator_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_constants.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_watcher.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_tracing.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_util_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/important_file_writer.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/memory_mapped_file.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/memory_mapped_file_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/scoped_file.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/scoped_temp_dir.cc
    ${ANDROID_ROOT}/external/libchrome/base/guid.cc
    ${ANDROID_ROOT}/external/libchrome/base/hash.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_file_value_serializer.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_parser.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_reader.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_string_value_serializer.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_value_converter.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_writer.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/string_escape.cc
    ${ANDROID_ROOT}/external/libchrome/base/lazy_instance.cc
    ${ANDROID_ROOT}/external/libchrome/base/location.cc
    ${ANDROID_ROOT}/external/libchrome/base/logging.cc
    ${ANDROID_ROOT}/external/libchrome/base/md5.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/aligned_memory.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted_memory.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/singleton.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/weak_ptr.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/incoming_task_queue.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_pump.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_pump_default.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_pump_libevent.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/bucket_ranges.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/field_trial.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/metrics_hashes.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_base.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_samples.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_snapshot_manager.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_histogram_allocator.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_memory_allocator.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_sample_map.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_map.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_vector.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sparse_histogram.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/statistics_recorder.cc
    ${ANDROID_ROOT}/external/libchrome/base/pending_task.cc
    ${ANDROID_ROOT}/external/libchrome/base/pickle.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/file_descriptor_shuffle.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/safe_strerror.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/kill.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/kill_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/launch.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/launch_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_handle.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_handle_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_iterator.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_metrics.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_metrics_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/profiler/scoped_profile.cc
    ${ANDROID_ROOT}/external/libchrome/base/profiler/scoped_tracker.cc
    ${ANDROID_ROOT}/external/libchrome/base/profiler/tracked_time.cc
    ${ANDROID_ROOT}/external/libchrome/base/rand_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/rand_util_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/run_loop.cc
    ${ANDROID_ROOT}/external/libchrome/base/sequence_checker_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/sequenced_task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/sha1_portable.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/pattern.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/safe_sprintf.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string16.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_number_conversions.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_piece.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/stringprintf.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_split.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_util_constants.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/utf_string_conversions.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/utf_string_conversion_utils.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/cancellation_flag.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/condition_variable_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/lock.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/lock_impl_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/read_write_lock_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/waitable_event_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/sync_socket_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/sys_info.cc
    ${ANDROID_ROOT}/external/libchrome/base/sys_info_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/task/cancelable_task_tracker.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/scheduler_lock_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence_sort_key.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/task.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/task_traits.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/trace_event_analyzer.cc
    ${ANDROID_ROOT}/external/libchrome/base/third_party/icu/icu_utf.cc
    ${ANDROID_ROOT}/external/libchrome/base/third_party/nspr/prtime.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/non_thread_safe_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/platform_thread_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/post_task_and_reply_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/sequenced_task_runner_handle.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/sequenced_worker_pool.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/simple_thread.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_checker_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_collision_warner.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_id_name_manager.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_storage.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_storage_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_restrictions.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_task_runner_handle.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/worker_pool.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/worker_pool_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/clock.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/default_clock.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/default_tick_clock.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/tick_clock.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/time.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/time_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/elapsed_timer.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/timer.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_allocation_context.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_allocation_context_tracker.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_allocation_register.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_allocation_register_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_heap_dump_writer.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_stack_frame_deduplicator.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/heap_profiler_type_name_deduplicator.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/malloc_dump_provider.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_allocator_dump.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_allocator_dump_guid.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_dump_manager.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_dump_request_args.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_dump_session_state.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/memory_infra_background_whitelist.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/process_memory_dump.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/process_memory_maps.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/process_memory_totals.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_buffer.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_config.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_argument.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_impl.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_memory_overhead.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_event_synthetic_delay.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_log.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_log_constants.cc
    ${ANDROID_ROOT}/external/libchrome/base/trace_event/trace_sampling_thread.cc
    ${ANDROID_ROOT}/external/libchrome/base/tracked_objects.cc
    ${ANDROID_ROOT}/external/libchrome/base/tracking_info.cc
    ${ANDROID_ROOT}/external/libchrome/base/values.cc
    ${ANDROID_ROOT}/external/libchrome/base/version.cc
    ${ANDROID_ROOT}/external/libchrome/base/vlog.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_watcher_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_util_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/shared_memory_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/unix_domain_socket_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/internal_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_handle_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_iterator_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_metrics_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/sys_string_conversions_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/sys_info_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/platform_thread_internal_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/platform_thread_linux.cc
    ${ANDROID_ROOT}/external/libchrome/components/timers/alarm_timer_chromeos.cc
    ${ANDROID_ROOT}/external/libchrome/base/allocator/allocator_shim.cc
    ${ANDROID_ROOT}/external/libchrome/base/allocator/allocator_shim_default_dispatch_to_glibc.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/libchrome'
# Raw param [1] = '-Iexternal/valgrind/include -Iexternal/valgrind'
# Raw param [2] = '-Iexternal/libchrome'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/modp_b64'
# Raw param [9] = '-Iexternal/googletest/googletest/include'
# Raw param [10] = '-Iexternal/libcxx/include'
# Raw param [11] = '-Iexternal/libcxxabi/include'
# Raw param [12] = '-Isystem/core/base/include'
# Raw param [13] = '-Iexternal/libevent/include'
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
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/external/valgrind/include -Iexternal/valgrind"
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/external/modp_b64"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/external/libevent/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/valgrind/include -Iexternal/valgrind/**/*.h"
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/modp_b64/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/external/libevent/include/**/*.h"
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
# Raw param [2] = '-D__ANDROID_HOST__'
# Raw param [3] = '-DDONT_EMBED_BUILD_METADATA'
# Raw param [4] = '-target i686-linux-gnu'
# Raw param [5] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [6] = '-fPIC'
# Raw param [7] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-D__ANDROID_HOST__' became -D__ANDROID_HOST__
# FLAG '-DDONT_EMBED_BUILD_METADATA' became -DDONT_EMBED_BUILD_METADATA
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_HOST__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_HOST__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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


add_executable(libchrome ${SOURCE_FILES})
