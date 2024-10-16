cmake_minimum_required(VERSION 3.8)
project(r7bot)

find_package(ament_cmake REQUIRED)

install(DIRECTORY config xacro launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
