CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

PROJECT(Non-Rigid-Registar)

MESSAGE(STATUS "This is BINARY dir " ${PROJECT_BINARY_DIR})
MESSAGE(STATUS "This is SOURCE dir " ${PROJECT_SOURCE_DIR})

ADD_SUBDIRECTORY(src)

#SET(CMAKE_INSTALL_PREFIX /usr/local)

#INSTALL(PROGRAMS Non-Rigid-Registar.sh DESTINATION bin)

#INSTALL(FILES COPYRIGHT README DESTINATION share/doc/Non-Rigid-Registar)

#INSTALL(DIRECTORY doc/ DESTINATION share/doc/Non-Rigid-Registar)

