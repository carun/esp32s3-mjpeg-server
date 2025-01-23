idf_component_register(
    SRCS "take_picture.c"
    INCLUDE_DIRS "."
    REQUIRES esp_http_server esp_wifi nvs_flash esp32-camera esp_timer log)