add_library(hello

  hello.h 
  hello.c
  hello-name.h
  hello-name.c
)
set_property(TARGET hello PROPERTY VERSION 2)
install(TARGETS hello DESTINATION lib)
install(FILES hello.h hello-name.h DESTINATION include)

target_include_directories(hello INTERFACE .)

