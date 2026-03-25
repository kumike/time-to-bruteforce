# 🔐 TIBR — Time to Iterate Brute-force Rate

**TIBR** is a simple CLI tool to estimate how long it will take to brute-force a given number of passwords or a wordlist.

It supports manual input, dictionary files, and automatic benchmarking using **aircrack-ng** or **pyrit**.

---

## ✨ Features

* 📊 Estimate brute-force time based on:

  * Password count (`-n`)
  * Wordlist file (`-f`)
* ⚡ Use manual speed (`-s`) or:

  * `aircrack-ng` benchmark (`-A`)
  * `pyrit` benchmark (`-P`)
* 📁 Automatically counts passwords in a dictionary
* 🧠 Interactive mode (no arguments)
* 🖥️ Can be used as a global CLI tool

---

## 🚀 Installation

```bash
git clone https://github.com/yourusername/tibr.git
cd tibr
chmod +x tibr.py
```

### Optional (install globally)

```bash
sudo cp tibr.py /usr/bin/tibr
```

---

## 🧪 Usage

### Interactive mode

```bash
python3 tibr.py
```

---

### With arguments

```bash
python3 tibr.py -s 1500 -f /path/to/dictionary.txt
```

---

### Use aircrack-ng benchmark

```bash
python3 tibr.py -A -n 100000000
```

---

### Use pyrit benchmark

```bash
tibr -P -f ~/mydict.txt
```

---

### Count passwords only

```bash
tibr -f ~/mydict.txt
```

---

## ⚙️ Arguments

| Flag | Description                               |
| ---- | ----------------------------------------- |
| `-s` | Set manual cracking speed (passwords/sec) |
| `-f` | Path to dictionary file                   |
| `-n` | Number of passwords                       |
| `-A` | Use aircrack-ng benchmark                 |
| `-P` | Use pyrit benchmark                       |

---

## 📌 Notes

* Make sure required tools are installed:

  * `aircrack-ng` → `aircrack-ng -S`
  * `pyrit` → `pyrit benchmark`
* You can input speed manually from any other tools.
* In interactive mode, you can define everything manually.

---

## 📊 Example

```bash
tibr -A -n 50000000
```

➡️ Uses aircrack-ng speed and calculates time for 50M passwords.

---

## ⚠️ Disclaimer

This tool is intended for **educational and security testing purposes only**.
Do not use it for illegal activities.

---

## 👤 Author

Mike Kub

---
[:rus:]

# 🔐 TIBR — Время перебора паролей

**TIBR** — это простой CLI-инструмент для оценки времени, необходимого для перебора заданного количества паролей или словаря.

Поддерживает ручной ввод скорости, работу со словарями, а также автоматическое получение скорости через **aircrack-ng** или **pyrit**.

---

## ✨ Возможности

* 📊 Расчёт времени перебора на основе:

  * Количества паролей (`-n`)
  * Файла словаря (`-f`)
* ⚡ Использование скорости:

  * Вручную (`-s`)
  * Через `aircrack-ng` (`-A`)
  * Через `pyrit` (`-P`)
* 📁 Автоматический подсчёт строк (паролей) в словаре
* 🧠 Интерактивный режим (без аргументов)
* 🖥️ Возможность использовать как обычную CLI-команду

---

## 🚀 Установка

```bash id="9sz1l2"
git clone https://github.com/yourusername/tibr.git
cd tibr
chmod +x tibr.py
```

### Установка как команды

```bash id="qk3n7c"
sudo cp tibr.py /usr/bin/tibr
```

---

## 🧪 Использование

### Интерактивный режим

```bash id="w2k91p"
python3 tibr.py
```

---

### С аргументами

```bash id="8x1y6f"
python3 tibr.py -s 1500 -f /path/to_dictionary/mydict.txt
```

---

### Использовать скорость aircrack-ng

```bash id="3j5b7m"
python3 tibr.py -A -n 100000000
```

---

### Использовать скорость pyrit

```bash id="h4u8z0"
tibr -P -f ~/mydict.txt
```

---

### Только подсчитать количество паролей

```bash id="c6t2vd"
tibr -f ~/mydict.txt
```

---

## ⚙️ Аргументы

| Ключ | Описание                               |
| ---- | -------------------------------------- |
| `-s` | Задать скорость перебора (паролей/сек) |
| `-f` | Путь к словарю                         |
| `-n` | Количество паролей                     |
| `-A` | Использовать benchmark aircrack-ng     |
| `-P` | Использовать benchmark pyrit           |

---

## 📌 Примечания

* Убедитесь, что установлены необходимые утилиты:

  * `aircrack-ng` → `aircrack-ng -S`
  * `pyrit` → `pyrit benchmark`
* Скорость можно вводить вручную из любых других программ.
* В интерактивном режиме можно задать все параметры вручную.

---

## 📊 Пример

```bash id="p8z7x4"
tibr -A -n 50000000
```

➡️ Использует скорость aircrack-ng и рассчитывает время для 50 млн паролей.

---

## ⚠️ Отказ от ответственности

Инструмент предназначен **только для образовательных целей и тестирования безопасности**.
Не используйте его для противоправной деятельности.

---

## 👤 Автор

Mike Kub

---


[![Buy Me a Coffee](https://img.buymeacoffee.com/button-api/?text=Buy+me+a+coffee&emoji=&slug=yourname&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff)](https://donatello.to/MichailKubrak?g=coffee)

[![Donate](https://img.shields.io/badge/Support%20Project-2ea44f?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://donatello.to/MichailKubrak?g=coffee)

[![Donate](https://img.shields.io/badge/☕%20Donate%20Me-FF813F?style=for-the-badge&logo=buymeacoffee&logoColor=white)](https://donatello.to/MichailKubrak?g=coffee)

