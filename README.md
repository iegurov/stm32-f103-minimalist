# 🧱 STM32F103 Minimalist Template

> Минималистичный стартовый шаблон для bare-metal разработки под **STM32 Blue Pill (STM32F103C8T6)** на `C` с использованием `arm-none-eabi-gcc`.

![STM32 Blue Pill](https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/STM32_Blue_Pill.jpg/320px-STM32_Blue_Pill.jpg)

---

## 🚀 Возможности

- Минимальный объем кода и зависимостей
- Без HAL или STM32Cube — только **CMSIS** и регистры
- Сборка через `Makefile`
- Линковочный скрипт и стартовый код включены
- Готово для прошивки через **ST-Link** или **OpenOCD**

---

## 🛠️ Требования

| Инструмент              | Назначение                     |
|------------------------|-------------------------------|
| `arm-none-eabi-gcc`    | Компилятор для Cortex-M       |
| `make`                 | Сборка проекта                 |
| `stlink` или `openocd` | Прошивка через SWD            |

