cmake_minimum_required(VERSION 3.8)
project(amrsweeper_description)



find_package(ament_cmake REQUIRED)



install(
  DIRECTORY config launch meshes urdf worlds
  DESTINATION share/${PROJECT_NAME}  
)

ament_package()
