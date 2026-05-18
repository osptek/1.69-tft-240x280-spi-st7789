# 1.69 寸 240×280 TFT SPI 模组（ST7789）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 1.69 英寸 **TFT**，分辨率 **240×280** |
| 接口 | **SPI** |
| 驱动芯片 | **ST7789** |
| 规格标识 | 产品资料中常用 **`1.69-tft-240x280-spi-st7789`** 表示本规格 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `docs/` | 数据手册、规格说明等 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **ESP-IDF代码**（ST7789 SPI + CST816 触摸 + LVGL9） |
| `display-touch-test/` | **单独测试显示代码**、**单独测试触摸代码** |

### 示例工程路径

#### 基础（`examples/` 根目录）

| 说明 | 路径 |
|:--|:--|
| ST7789 SPI + CST816 + LVGL9 | `examples/s3-idf5_st7789-spi_cst816-i2c_lvgl-v9/` |

#### 单独测试（`display-touch-test/`）

| 说明 | 路径 |
|:--|:--|
| ST7789 SPI 显示测试 | `examples/display-touch-test/s3-idf_st7789-spi_lvgl-v9/` |
| CST816 触摸 I2C 测试 | `examples/display-touch-test/S3-IDF_CST816-I2C/` |
