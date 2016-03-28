SET(cmake_minimum_version 2.8)
PROJECT(sockets)

SET(CLIENT
  Client/src/tcpclient.cpp
  )

SET(SERVER
  Server/src/tcpserver.cpp
  )

ADD_EXECUTABLE(client ${CLIENT})
ADD_EXECUTABLE(server ${SERVER})