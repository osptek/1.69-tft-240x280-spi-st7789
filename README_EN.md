# 1.69" 240×280 TFT SPI module (ST7789) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** for this module, together with datasheets, specifications, and interface / bring-up documentation for selection reference and integration.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.69-inch **TFT** panel, **240×280** resolution |
| Interface | **SPI** |
| Driver IC | **ST7789** |
| Spec ID | **`1.69-tft-240x280-spi-st7789`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets and specifications |
| `examples/` | **Sample projects** by category |

### `examples/` layout

| Location | Description (internal package folder) |
|:--|:--|
| `examples/` root | **ESP-IDF代码** (ST7789 SPI + CST816 touch + LVGL9) |
| `display-touch-test/` | **单独测试显示代码**、**单独测试触摸代码** |

### Sample project paths

#### Baseline (`examples/` root)

| Description | Path |
|:--|:--|
| ST7789 SPI + CST816 + LVGL9 | `examples/s3-idf5_st7789-spi_cst816-i2c_lvgl-v9/` |

#### Display / touch tests (`display-touch-test/`)

| Description | Path |
|:--|:--|
| ST7789 SPI display test | `examples/display-touch-test/s3-idf_st7789-spi_lvgl-v9/` |
| CST816 touch I2C test | `examples/display-touch-test/S3-IDF_CST816-I2C/` |
