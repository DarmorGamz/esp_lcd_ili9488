# ESP LCD ILI9488

Implementation of the ILI9488 LCD controller with esp_lcd component. 

| LCD controller | Communication interface | Component name | Link to datasheet |
| :------------: | :---------------------: | :------------: | :---------------: |
| ILI9488        | SPI                     | esp_lcd_ili9488     | [Specification](https://www.hpinfotech.ro/ILI9488.pdf) |

## Add to project

Packages from this repository are not yet added to the [Espressif's component service](https://components.espressif.com/).  

You can add them to your project via the git respository.
```
dependencies:
  esp_lcd_ili9488:
    git: https://https://github.com/DarmorGamz/esp_lcd_ili9488.git
```

Alternatively, you can create `idf_component.yml`. More is in [Espressif's documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-guides/tools/idf-component-manager.html).

## Example use

There is an example in ESP-IDF with this LCD controller. Please follow this [link](https://github.com/espressif/esp-idf/tree/master/examples/peripherals/lcd/i80_controller). 
