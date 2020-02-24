CMAKE_MINIMUM_REQUIRED(VERSION 3.14)

SET(CMAKE_C_STANDARD 11)

MESSAGE(STATUS "Building neo library")

ADD_LIBRARY(neo STATIC
	neo_err.c
	neo_files.c
	neo_misc.c
	neo_rand.c
	ulist.c
	neo_hdf.c
	neo_str.c
	neo_date.c
	wildmat.c
	neo_hash.c
	ulocks.c
	rcfs.c
	skiplist.c
	dict.c
	filter.c
	neo_net.c
	neo_server.c)
