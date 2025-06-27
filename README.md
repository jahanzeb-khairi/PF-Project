# C Your Weather 🌤️

A simple console-based weather information application built in C that allows users to view simulated weather data for any day and month in the year **2022** for **Karachi, Pakistan**. This application offers flexibility by allowing the user to select a specific date and time of day to view the temperature, sea temperature, humidity, and windspeed data.

## 📌 Features

- View weather data for any date in 2022
- Select time of day:
  - Morning (M)
  - Evening (E)
  - Night (N)
- Displayed metrics:
  - Hourly temperature
  - Sea temperature
  - Humidity level
  - Wind speed

## 🏙️ Location
- Fixed for **Karachi**, Pakistan

## ⚙️ Technology

- Language: **C**
- Platform: Console-based CLI

## 🧩 How It Works

1. The user selects a **month (1-12)**.
2. Then selects a **day** within that month.
3. Finally, chooses a **time slot** of the day (`M`, `E`, or `N`).
4. The program displays a pre-defined weather dataset based on the selection.

## 🚀 Getting Started

### Compilation

Use any C compiler such as GCC:

```bash
gcc "C your weather.cpp" -o weather
