build_lib_example(
    NAME highway 
    SOURCE_FILES HIGHWAY.cc
    LIBRARIES_TO_LINK
    ${libnetwork}
    ${liblte}
    ${libmorev2x}
    ${libantenna}
)
build_lib_example(
    NAME highway_2 
    SOURCE_FILES HIGHWAY_2.cc
    LIBRARIES_TO_LINK
    ${libautomotive}
    ${libnetwork}
    ${liblte}
    ${libmorev2x}
    ${libantenna}
)
