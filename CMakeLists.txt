SET( CMAKE_CXX_FLAGS  "-Wno-error=misleading-indentation")
idf_component_register(SRCS "TFT_eSPI.cpp"
                    INCLUDE_DIRS ".")