set(TGT HelloWorldSample)

set(SRCS HelloWorldSample.swift)

add_executable(${TGT} ${SRCS})

target_link_libraries(${TGT} HelloWorld)