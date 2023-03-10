set(TGT HelloWorld)

set(SOURCES
    HelloWorld.swift
    )

add_library(${TGT} SHARED ${SOURCES})

set_target_properties(${TGT} PROPERTIES
  INTERFACE_INCLUDE_DIRECTORIES ${CMAKE_Swift_MODULE_DIRECTORY})