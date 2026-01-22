# 🌦️ Weather CLI

A simple and lightweight **CLI tool** for getting the current weather directly from the terminal.
Powered by **OpenWeatherMap API**.

---

## ✨ Features

- 🌍 Get current weather by city
- 💾 Save city and API token locally
- 🎨 Colored CLI output
- ☀ Unicode weather icons (terminal-safe)
- ⚡ Fast and minimal

---

## 📦 Installation

Install globally via npm:

```bash
npm install -g weather-cli-senriv
```

After that, the `weather` command will be available globally.

---

## 🔑 Getting an API Key

This CLI uses the **OpenWeatherMap API**.

1. Go to https://openweathermap.org/
2. Create an account
3. Generate an API key
4. Save it using the CLI command below

---

## 🚀 Usage

### Save API token
```bash
weather -t YOUR_API_KEY
```

### Save city
```bash
weather -s London
```

### Get weather
```bash
weather
```

### Show help
```bash
weather -h
```

---

## 🖥 Example Output

```txt
 WEATHER  Weather in London
 ☀  clear sky
 Temperature: 21°C (feels like 20°C)
 Humidity: 56%
 Wind speed: 4.1 m/s
```

---

## 🛠 CLI Options

| Option | Description |
| ------ | ----------- |
| `-h` | Show help |
| `-s [CITY]` | Set city |
| `-t [API_KEY]` | Save API token |

---

## 📁 Data Storage

Configuration is stored locally in:

```txt
~/weather-data.json
```

It contains:
- saved city
- API token

---

## 🧩 Tech Stack

- Node.js (ES Modules)
- Axios
- Chalk
- OpenWeatherMap API

---

## ⚠ Notes

- Unicode icons are used for better terminal compatibility
- Temperature is shown in **Celsius**
- Wind speed is shown in **m/s**

---

## 📄 License

ISC

---

## 👤 Author

**Vitalii Borysenko (Senriv)**  
GitHub: https://github.com/Senriv
