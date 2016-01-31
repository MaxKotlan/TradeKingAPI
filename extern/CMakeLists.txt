#configure submodule cpp-netlib
option(CPP-NETLIB_BUILD_EXAMPLES OFF)
option(CPP-NETLIB_BUILD_EXPERIMENTS OFF)
option(CPP-NETLIB_BUILD_SHARED_LIBS OFF)
option(CPP-NETLIB_BUILD_TESTS ON)
option(CPP-NETLIB_ENABLE_HTTPS ON)
#build submodule cpp-netlib
add_subdirectory(cpp-netlib)
