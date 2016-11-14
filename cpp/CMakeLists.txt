file(GLOB SRCS "*.hpp" "*.cpp" ) 
file(GLOB HDRS "*.hpp" ) 

add_library(FitSdkCpp ${SRCS})
set_target_properties(FitSdkCpp PROPERTIES PUBLIC_HEADER "${HDRS}")

install( TARGETS FitSdkCpp
  ARCHIVE DESTINATION ${CMAKE_BINARY_DIR}/lib
  PUBLIC_HEADER DESTINATION ${CMAKE_BINARY_DIR}/include
 ) 
