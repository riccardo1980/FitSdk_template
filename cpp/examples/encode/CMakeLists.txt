
set ( CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin )

include_directories( ${FITSDK_INCLUDE_DIR} ) 
add_executable( encode encode.cpp )
target_link_libraries( encode LINK_PUBLIC FitSdkCpp ) 

  
  
