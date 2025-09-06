cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 17)
add_library(CHATCBBThirdPartyDepends INTERFACE)
target_include_directories(CHATCBBThirdPartyDepends INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)
target_link_libraries(CHATCBBThirdPartyDepends INTERFACE
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_atomic.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_charconv.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_chrono.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_container.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_context.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_contract.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_coroutine.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_date_time.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_exception.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_fiber.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_filesystem.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_graph.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_iostreams.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_json.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_locale.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_log.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_log_setup.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_c99.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_c99f.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_c99l.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_tr1.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_tr1f.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_math_tr1l.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_nowide.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_prg_exec_monitor.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_process.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_program_options.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_random.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_regex.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_serialization.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_stacktrace_addr2line.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_stacktrace_backtrace.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_stacktrace_basic.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_stacktrace_from_exception.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_stacktrace_noop.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_test_exec_monitor.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_thread.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_timer.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_type_erasure.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_unit_test_framework.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_url.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_wave.a
    ${CMAKE_CURRENT_SOURCE_DIR}/lib/boost/libboost_wserialization.a
)