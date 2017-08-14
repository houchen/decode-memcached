cmake_minimum_required(VERSION 3.7)
project(memcached_1_4_15)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        assoc.c
        assoc.h
        cache.c
        cache.h
        daemon.c
        hash.c
        hash.h
        items.c
        items.h
        memcached.c
        memcached.h
        protocol_binary.h
        sasl_defs.c
        sasl_defs.h
        sizes.c
        slabs.c
        slabs.h
        solaris_priv.c
        stats.c
        stats.h
        testapp.c
        thread.c
        timedrun.c
        trace.h
        util.c
        util.h)

add_executable(memcached_1_4_15 ${SOURCE_FILES})