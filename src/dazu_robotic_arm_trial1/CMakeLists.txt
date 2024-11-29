cmake_minimum_required(VERSION 3.8)
project(dazu_robotic_arm_trial1)

# Find dependencies
find_package(ament_cmake REQUIRED)

# Declare the package
ament_package()

# Install directories
install(DIRECTORY
  config
  launch
  meshes
  urdf
  DESTINATION share/${PROJECT_NAME}
)
