ADD_EXECUTABLE(proxy proxy.cc)
INCLUDE_DIRECTORIES(../../inc)
TARGET_LINK_LIBRARIES(proxy ahttpd)
