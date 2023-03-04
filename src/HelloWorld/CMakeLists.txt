set(TGT HelloWorld)

set(SOURCES
    HelloWorld.swift
    )

add_library(${TGT} SHARED ${SOURCES})