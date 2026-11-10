# Example for `bmp280` driver

## What it does

It shows device name, `BME280` or `BMP280`, found on I2C bus.

It shows temperature and pressure in a loop.

## Wiring

Connect `SCL` and `SDA` pins to the following pins with appropriate pull-up
resistors.

| Name | Description | Defaults |
|------|-------------|----------|
| `CONFIG_EXAMPLE_I2C_MASTER_SCL` | GPIO number for `SCL` | "6" for `esp32c3`, "19" for `esp32`, `esp32s2`, and `esp32s3` |
| `CONFIG_EXAMPLE_I2C_MASTER_SDA` | GPIO number for `SDA` | "5" for `esp32c3`, "18" for `esp32`, `esp32s2`, and `esp32s3` |
