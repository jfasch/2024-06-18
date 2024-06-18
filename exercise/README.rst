Exercise: Straightforward Build
===============================

.. code-block:: console

    .
    ├── README.rst
    ├── firmware                          # <--- executables (need all the others)
    │   ├── boiling-pot.cpp
    │   └── data-logger.cpp
    └── toolcase                          # <--- descend into base, pot, logger
        ├── base                          # <--- base library
        │   ├── hysteresis.cpp
        │   ├── hysteresis.h
        │   ├── sensor-avg.cpp
        │   ├── sensor-avg.h
        │   ├── sensor-const.cpp
        │   ├── sensor-const.h
        │   ├── sensor-mock.cpp
        │   ├── sensor-mock.h
        │   ├── sensor-random.cpp
        │   ├── sensor-random.h
        │   ├── sensor-w1.h
        │   ├── sensor.h
        │   ├── switch-mock.cpp
        │   ├── switch-mock.h
        │   ├── switch.h
        │   ├── sysfs-switch.cpp
        │   └── sysfs-switch.h
        ├── boiling-pot                   # <--- boiling-pot library
        │   ├── boiling-pot.cpp
        │   └── boiling-pot.h
        └── data-logger                   # <--- data logger library
            ├── data-logger.cpp
            ├── data-logger.h
            ├── sensor-config.h
            ├── sensor-values.h
            ├── sink-file.h
            ├── sink-logger.h
            ├── sink-mock.h
            └── sink-terminal.h
    
