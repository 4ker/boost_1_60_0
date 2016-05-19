project( boost_thread )
file( GLOB_RECURSE LIBSRCS *.c *.cpp *.cc *.h *.hpp )
add_library( "${PROJECT_NAME}_static" STATIC ${LIBSRCS} )
add_library(  ${PROJECT_NAME}         SHARED ${LIBSRCS} )
