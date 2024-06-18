add_library(
  base

  hysteresis.h
  hysteresis.cpp
  sensor-avg.cpp
  sensor-avg.h
  sensor-const.cpp
  sensor-const.h
  sensor.h
  sensor-mock.cpp
  sensor-mock.h
  sensor-random.cpp
  sensor-random.h
  sensor-w1.h
  switch.h
  switch-mock.cpp
  switch-mock.h
  sysfs-switch.cpp
  sysfs-switch.h
)

target_include_directories(base INTERFACE .)
