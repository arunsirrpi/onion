
include_directories (${CMAKE_SOURCE_DIR}/src/) 

add_executable(01-url 01-url.c buffer.c)
target_link_libraries(01-url onion onion_handlers)


add_executable(02-exportlocal 02-exportlocal.c buffer.c)
target_link_libraries(02-exportlocal onion onion_handlers)

