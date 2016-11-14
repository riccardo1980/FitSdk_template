
set ( CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin )

include_directories( ${FITSDK_INCLUDE_DIR} ) 
add_executable( decode decode.cpp )
target_link_libraries( decode LINK_PUBLIC FitSdkCpp ) 

  
  
