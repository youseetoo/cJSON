# ESP-IDF component for cJSON (DaveGamble/cJSON submodule).
#
# Only the two runtime sources are built as a component. The upstream
# standalone-project build (with its test/fuzz targets) is preserved in
# CMakeLists.standalone.txt for out-of-tree / host use.
idf_component_register(SRCS "cJSON.c" "cJSON_Utils.c"
                       INCLUDE_DIRS ".")
