set(srcs "ESP32MotorControl.cpp")
# set(requires "arduino" )

idf_component_register(SRCS ${srcs}
                       INCLUDE_DIRS "."
                       REQUIRES "arduino"
                       )

                       