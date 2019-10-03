file(GLOB_RECURSE SOURCES ../lv_examples/*.c)
idf_component_register(SRCS ${SOURCES}
                       INCLUDE_DIRS ../lv_examples
                       REQUIRES lvgl_idf)
