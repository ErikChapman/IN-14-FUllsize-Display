<div align="center">

**🌐 Choose language / Выберите язык:**

[![English](https://img.shields.io/badge/Language-English-blue?style=for-the-badge)](#english)
[![Русский](https://img.shields.io/badge/Язык-Русский-red?style=for-the-badge)](#русский)

</div>

---

## English

<details>
  <summary>📖 Click to expand English version</summary>

<br>

# 🕰️ IN-14 Fullsize Display

<div align="center">

<img src="https://github.com/user-attachments/assets/c3def975-86fc-4351-9fa8-bca152c25f1d" alt="IN-14 Fullsize Display" width="600">

**Clock based on IN-14 nixie tube indicators with TFT display and environmental sensors**

[![Status](https://img.shields.io/badge/PCB-✅_Done-brightgreen?style=for-the-badge)](#-pcb)
[![Status](https://img.shields.io/badge/Case-✅_Done-brightgreen?style=for-the-badge)](#-case)
[![Status](https://img.shields.io/badge/Code-🚧_In_Progress-orange?style=for-the-badge)](#-code)

</div>

---

## 📋 About the Project

A comprehensive open-source project for creating a desktop clock using classic Soviet nixie tube indicators **IN-14 (ИН-14)**, complemented with a TFT screen and environmental sensors. The project consists of three key components that assemble into a single device:

| Component | Description | Status |
|:---------:|----------|:------:|
| 🔌 **PCB** | Electrical schematic and PCB in Altium Designer | ✅ Done |
| 🏗️ **Case** | 3D model of the case for printing/manufacturing | ✅ Done |
| 💻 **Code** | Firmware and software | 🚧 In Progress |

### ✨ Key Features

- 🔴 **IN-14 Nixie Tube Indicators** — classic Soviet tubes with warm orange glow
- 📺 **TFT Display** — additional screen for displaying information and control
- 🌡️ **BMP280 Sensor** — temperature and atmospheric pressure measurement
- 💧 **SHT30-DIS-B2.5KS Sensor** — precise humidity and temperature measurement
- 💡 **6 RGB LEDs** — indicator backlighting with customizable colors

---

## 🔌 PCB

<details>
<summary><b>📐 Expand — Schematics, PCB and production files</b></summary>

<br>

<div align="center">

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/6cf544ae-efce-4b3d-a8eb-26e8f8d92e4c" alt="PCB Top Layer" width="400">
<br><b>Top Layer</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/79a8452c-baa4-49b8-98a8-aab6fe60a002" alt="PCB Bottom Layer" width="400">
<br><b>Bottom Layer</b>
</td>
</tr>
</table>

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/f3ff560a-51c3-414d-86fa-358828131263" width="220">
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/c316249f-90b3-40c2-88c3-461949d19eeb" width="220">
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/2cd30982-976f-42e1-bc8f-576ccbd08aef" width="220">
</td>
</tr>
</table>

</div>

### Schematic Modules

| File | Purpose |
|------|-----------|
| `Main_Logic.SchDoc` | Main logic and display control |
| `Power.SchDoc` | Power supply and voltage stabilization |
| `Lamp.SchDoc` | IN-14 nixie tube control |

### PCB Files

| File | Purpose |
|------|-----------|
| `IN-14.PcbDoc` | Main printed circuit board |
| `PcbLib1.PcbLib` | Footprint library #1 |
| `PcbLib2.PcbLib` | Footprint library #2 |
| `SOP127P1030X245-18N.PcbLib` | Component package library |

### Component Libraries

| File | Purpose |
|------|-----------|
| `Schlib1.SchLib` | Schematic symbol library |
| `UGO.SchLib` / `UGO-1.SchLib` | Conventional graphic symbols |
| `SAMTEC-TMM-107-01-X-S.LibPkg` | SAMTEC connector library package |

### Production Files

| Resource | Location |
|--------|-------------|
| 📦 **Gerber Files** | [`Project Outputs for IN-14-FUllsize-Display/`](Project%20Outputs%20for%20IN-14-FUllsize-Display/) |

### 🔧 How to Use

1. Open the project `IN-14-FUllsize-Display.PrjPcb` in **Altium Designer**
2. Start with `Main_Logic.SchDoc` to understand the logic
3. For manufacturing, use Gerber files from the `Project Outputs for IN-14-FUllsize-Display/` folder

</details>

---

## 🏗️ Case

<details>
<summary><b>📦 Expand — 3D case model</b></summary>

<br>

### 3D Case Model

The case is designed in Autodesk Fusion 360 and is available in two ways:

| Method | Link |
|--------|--------|
| 🌐 **Online View** | [Open in Autodesk Viewer (A360)](https://a360.co/46kFfag) |
| 📥 **Download Files** | Folder [`case model/`](case%20model/) in the repository |

### 🔧 How to Use

1. For quick preview — open [online model on A360](https://a360.co/46kFfag)
2. For editing — download files from the `case model/` folder and open in Fusion 360
3. For 3D printing — export the model to STL/STEP from Fusion 360

</details>

---

## 💻 Code

<details>
<summary><b>⚡ Expand — Firmware and software</b></summary>

<br>

### 🚧 In Development

This section is under development. In the future, it will include:

- 📟 **Microcontroller Firmware** — control of indicators and sensors
- 🕐 **Display Logic** — clock, temperature, humidity, pressure
- 📺 **TFT Display Driver** — output information to additional screen
- 🌐 **Network Functions** — time synchronization (NTP) and more
- ⚙️ **Configuration** — operating mode settings

> 📌 *Stay tuned for repository updates!*

</details>

---

## 📊 Technical Specifications

| Parameter | Value |
|----------|----------|
| **Indicators** | IN-14 (ИН-14) nixie tubes |
| **Backlighting** | 6 RGB LEDs |
| **Additional Display** | TFT |
| **Sensors** | BMP280, SHT30-DIS-B2.5KS |
| **CAD (PCB)** | Altium Designer |
| **CAD (Case)** | Autodesk Fusion 360 |
| **Output Files** | Gerber, 3D models |

---

## 📚 Documentation & Datasheets

<details>
<summary><b>📄 Expand — Component documentation links</b></summary>

<br>

### 🧠 Microcontroller

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **ESP32-WROOM-32U (16MB)** | Wi-Fi + Bluetooth microcontroller | [📄 Datasheet](https://static.chipdip.ru/lib/789/DOC015789371.pdf) |

### 📺 Display

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **2.25" ST7789 TFT** | TFT display for information output | [🛒 Product Page](https://aliexpress.ru/item/1005009024495784.html?sku_id=12000047620457684&spm=a2g2w.productlist.search_results.7.7e2846db5Jg2tP) |

### ⚡ Logic and Drivers

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **CD74HC4514EN** | 4-to-16 line decoder/demultiplexer | [📄 Datasheet](https://www.silicon-ark.co.uk/datasheets/mc74hc4514n-datasheet-motorola.pdf) |
| **TD62783AFG** | 8-channel high-voltage output driver | [📄 Datasheet](https://docs.rs-online.com/bc35/0900766b80811071.pdf) |

### 🌡️ Sensors

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **SHT30-DIS-B2.5KS** | Temperature and humidity sensor | [📄 Datasheet](https://sensirion.com/media/documents/213E6A3B/63A5A569/Datasheet_SHT3x_DIS.pdf) |
| **BMP280** | Temperature and atmospheric pressure sensor | [📄 Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmp280-ds001.pdf) |

### 🔋 Power Supply

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **LM3671MF-ADJ/NOPB** | Step-down DC-DC converter | [📄 Datasheet](https://www.ti.com/lit/ds/symlink/lm3671.pdf) |
| **MAX1771** | Step-up DC-DC converter for high-voltage tube power | [📄 Reference Circuit](https://9zip.ru/vintage/usb_nixie_power_supply.htm) |

### 💡 Backlighting

| Component | Description | Documentation |
|-----------|----------|:------------:|
| **LED RGB CLEAR 4SMD** | RGB LEDs for indicator backlighting | [🛒 Product Page](https://aliexpress.ru/item/1005005890554477.html?sku_id=12000034724821714&spm=a2g2w.productlist.search_results.1.6aa154bfwtVn8v) |

</details>

---

<div align="center">

*Made with ❤️ and nixie tubes*

</div>

</details>

---

## Русский

<details open>
  <summary>📖 Нажмите, чтобы развернуть/свернуть русскую версию</summary>

<br>

# 🕰️ IN-14 Fullsize Display

<div align="center">

<img src="https://github.com/user-attachments/assets/c3def975-86fc-4351-9fa8-bca152c25f1d" alt="IN-14 Fullsize Display" width="600">

**Часы на газоразрядных индикаторах IN-14 с использованием TFT дисплея и датчиками окружающей среды**

[![Status](https://img.shields.io/badge/Печатная_плата-✅_Готово-brightgreen?style=for-the-badge)](#-печатная-плата)
[![Status](https://img.shields.io/badge/Корпус-✅_Готово-brightgreen?style=for-the-badge)](#-корпус)
[![Status](https://img.shields.io/badge/Код-🚧_В_разработке-orange?style=for-the-badge)](#-код)

</div>

---

## 📋 О проекте

Комплексный open-source проект для создания настольных часов с использованием классических советских газоразрядных ламп **IN-14 (ИН-14)**, дополненный TFT-экраном и датчиками окружающей среды. Проект состоит из трёх ключевых частей, которые собираются в единое устройство:

| Компонент | Описание | Статус |
|:---------:|----------|:------:|
| 🔌 **Печатная плата** | Электрическая схема и PCB в Altium Designer | ✅ Готово |
| 🏗️ **Корпус** | 3D-модель корпуса для печати/производства | ✅ Готово |
| 💻 **Код** | Прошивка и программное обеспечение | 🚧 В разработке |

### ✨ Ключевые особенности

- 🔴 **Газоразрядные индикаторы IN-14** — классические советские лампы с тёплым оранжевым свечением
- 📺 **TFT-дисплей** — дополнительный экран для отображения информации и управления
- 🌡️ **Датчик BMP280** — измерение температуры и атмосферного давления
- 💧 **Датчик SHT30-DIS-B2.5KS** — точное измерение влажности и температуры
- 💡 **6 RGB-светодиодов** — подсветка индикаторов с возможностью настройки цвета

---

## 🔌 Печатная плата

<details>
<summary><b>📐 Развернуть — Схемы, PCB и производственные файлы</b></summary>

<br>

<div align="center">

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/6cf544ae-efce-4b3d-a8eb-26e8f8d92e4c" alt="PCB Top Layer" width="400">
<br><b>Top Layer</b>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/79a8452c-baa4-49b8-98a8-aab6fe60a002" alt="PCB Bottom Layer" width="400">
<br><b>Bottom Layer</b>
</td>
</tr>
</table>

<table>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/f3ff560a-51c3-414d-86fa-358828131263" width="220">
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/c316249f-90b3-40c2-88c3-461949d19eeb" width="220">
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/2cd30982-976f-42e1-bc8f-576ccbd08aef" width="220">
</td>
</tr>
</table>

</div>

### Модули схемы

| Файл | Назначение |
|------|-----------|
| `Main_Logic.SchDoc` | Основная логика и управление дисплеем |
| `Power.SchDoc` | Блок питания и стабилизация напряжения |
| `Lamp.SchDoc` | Управление газоразрядными лампами IN-14 |

### Печатная плата

| Файл | Назначение |
|------|-----------|
| `IN-14.PcbDoc` | Основная печатная плата |
| `PcbLib1.PcbLib` | Библиотека посадочных мест №1 |
| `PcbLib2.PcbLib` | Библиотека посадочных мест №2 |
| `SOP127P1030X245-18N.PcbLib` | Библиотека корпусов компонентов |

### Библиотеки компонентов

| Файл | Назначение |
|------|-----------|
| `Schlib1.SchLib` | Библиотека схемных символов |
| `UGO.SchLib` / `UGO-1.SchLib` | Условные графические обозначения |
| `SAMTEC-TMM-107-01-X-S.LibPkg` | Пакет библиотеки разъёма SAMTEC |

### Производственные файлы

| Ресурс | Расположение |
|--------|-------------|
| 📦 **Gerber-файлы** | [`Project Outputs for IN-14-FUllsize-Display/`](Project%20Outputs%20for%20IN-14-FUllsize-Display/) |

### 🔧 Как использовать

1. Откройте проект `IN-14-FUllsize-Display.PrjPcb` в **Altium Designer**
2. Начните с `Main_Logic.SchDoc` для понимания логики
3. Для производства используйте Gerber-файлы из папки `Project Outputs for IN-14-FUllsize-Display/`

</details>

---

## 🏗️ Корпус

<details>
<summary><b>📦 Развернуть — 3D-модель корпуса</b></summary>

<br>

### 3D-модель корпуса

Корпус спроектирован в Autodesk Fusion 360 и доступен двумя способами:

| Способ | Ссылка |
|--------|--------|
| 🌐 **Онлайн-просмотр** | [Открыть в Autodesk Viewer (A360)](https://a360.co/46kFfag) |
| 📥 **Скачать файлы** | Папка [`case model/`](case%20model/) в репозитории |

### 🔧 Как использовать

1. Для быстрого просмотра — откройте [онлайн-модель на A360](https://a360.co/46kFfag)
2. Для редактирования — скачайте файлы из папки `case model/` и откройте в Fusion 360
3. Для 3D-печати — экспортируйте модель в STL/STEP из Fusion 360

</details>

---

## 💻 Код

<details>
<summary><b>⚡ Развернуть — Прошивка и программное обеспечение</b></summary>

<br>

### 🚧 В разработке

Этот раздел находится в процессе разработки. В будущем здесь появятся:

- 📟 **Прошивка микроконтроллера** — управление индикаторами и датчиками
- 🕐 **Логика отображения** — часы, температура, влажность, давление
- 📺 **Драйвер TFT-дисплея** — вывод информации на дополнительный экран
- 🌐 **Сетевые функции** — синхронизация времени (NTP) и прочее
- ⚙️ **Конфигурация** — настройка режимов работы

> 📌 *Следите за обновлениями репозитория!*

</details>

---

## 📊 Технические характеристики

| Параметр | Значение |
|----------|----------|
| **Индикаторы** | Газоразрядные лампы IN-14 (ИН-14) |
| **Подсветка** | 6 RGB-светодиодов |
| **Дополнительный дисплей** | TFT |
| **Датчики** | BMP280, SHT30-DIS-B2.5KS |
| **САПР (плата)** | Altium Designer |
| **САПР (корпус)** | Autodesk Fusion 360 |
| **Выходные файлы** | Gerber, 3D-модели |

---

## 📚 Документация и Datasheet'ы

<details>
<summary><b>📄 Развернуть — Ссылки на документацию компонентов</b></summary>

<br>

### 🧠 Микроконтроллер

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **ESP32-WROOM-32U (16MB)** | Wi-Fi + Bluetooth микроконтроллер | [📄 Datasheet](https://static.chipdip.ru/lib/789/DOC015789371.pdf) |

### 📺 Дисплей

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **2.25" ST7789 TFT** | TFT-дисплей для отображения информации | [🛒 Страница товара](https://aliexpress.ru/item/1005009024495784.html?sku_id=12000047620457684&spm=a2g2w.productlist.search_results.7.7e2846db5Jg2tP) |

### ⚡ Логика и драйверы

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **CD74HC4514EN** | 4-to-16 линейный декодер/демультиплексор | [📄 Datasheet](https://www.silicon-ark.co.uk/datasheets/mc74hc4514n-datasheet-motorola.pdf) |
| **TD62783AFG** | 8-канальный драйвер высоковольтного выхода | [📄 Datasheet](https://docs.rs-online.com/bc35/0900766b80811071.pdf) |

### 🌡️ Датчики

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **SHT30-DIS-B2.5KS** | Датчик температуры и влажности | [📄 Datasheet](https://sensirion.com/media/documents/213E6A3B/63A5A569/Datasheet_SHT3x_DIS.pdf) |
| **BMP280** | Датчик температуры и атмосферного давления | [📄 Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmp280-ds001.pdf) |

### 🔋 Питание

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **LM3671MF-ADJ/NOPB** | Понижающий DC-DC преобразователь | [📄 Datasheet](https://www.ti.com/lit/ds/symlink/lm3671.pdf) |
| **MAX1771** | Повышающий DC-DC преобразователь для высоковольтного питания ламп | [📄 Справочная схема](https://9zip.ru/vintage/usb_nixie_power_supply.htm) |

### 💡 Подсветка

| Компонент | Описание | Документация |
|-----------|----------|:------------:|
| **LED RGB CLEAR 4SMD** | RGB-светодиоды для подсветки индикаторов | [🛒 Страница товара](https://aliexpress.ru/item/1005005890554477.html?sku_id=12000034724821714&spm=a2g2w.productlist.search_results.1.6aa154bfwtVn8v) |

</details>

---

<div align="center">

*Сделано с ❤️ и газоразрядными лампами*

</div>

</details>
