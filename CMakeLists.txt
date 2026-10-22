project(CFS_RPI_IOLIB C)

include_directories(src)

aux_source_directory(src LIB_SRC_FILES)

# Create the app module
add_cfe_app(rpi_iolib ${LIB_SRC_FILES})