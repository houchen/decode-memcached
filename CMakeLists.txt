cmake_minimum_required(VERSION 3.7)
project(decode_memcached)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        memcached-1.4.15/assoc.c
        memcached-1.4.15/assoc.h
        memcached-1.4.15/cache.c
        memcached-1.4.15/cache.h
        memcached-1.4.15/config.h
        memcached-1.4.15/daemon.c
        memcached-1.4.15/hash.c
        memcached-1.4.15/hash.h
        memcached-1.4.15/items.c
        memcached-1.4.15/items.h
        memcached-1.4.15/memcached.c
        memcached-1.4.15/memcached.h
        memcached-1.4.15/protocol_binary.h
        memcached-1.4.15/sasl_defs.c
        memcached-1.4.15/sasl_defs.h
        memcached-1.4.15/sizes.c
        memcached-1.4.15/slabs.c
        memcached-1.4.15/slabs.h
        memcached-1.4.15/solaris_priv.c
        memcached-1.4.15/stats.c
        memcached-1.4.15/stats.h
        memcached-1.4.15/testapp.c
        memcached-1.4.15/thread.c
        memcached-1.4.15/timedrun.c
        memcached-1.4.15/trace.h
        memcached-1.4.15/util.c
        memcached-1.4.15/util.h)

add_executable(decode_memcached ${SOURCE_FILES})