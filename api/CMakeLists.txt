file(
  COPY ${CMAKE_CURRENT_LIST_DIR}/xcfun.h
  DESTINATION ${PROJECT_BINARY_DIR}/${CMAKE_INSTALL_INCLUDEDIR}/${PROJECT_NAME}
  )

install(
  FILES
    ${CMAKE_CURRENT_LIST_DIR}/xcfun.h
  DESTINATION
    ${CMAKE_INSTALL_INCLUDEDIR}/${PROJECT_NAME}
  )

file(
  COPY ${CMAKE_CURRENT_LIST_DIR}/xcfun.F90
  DESTINATION ${PROJECT_BINARY_DIR}/${CMAKE_INSTALL_INCLUDEDIR}/${PROJECT_NAME}
  )

install(
  FILES
    ${CMAKE_CURRENT_LIST_DIR}/xcfun.F90
  DESTINATION
    ${CMAKE_INSTALL_INCLUDEDIR}/${PROJECT_NAME}
  )
