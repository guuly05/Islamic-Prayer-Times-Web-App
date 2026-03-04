# 🕌 Islamic Prayer Times Web App

A lightweight, responsive web application that fetches and displays daily Islamic prayer times based on the user's specified city and country. Built with vanilla HTML, CSS, and JavaScript, it leverages the **Aladhan API** to provide accurate prayer schedules along with the corresponding Hijri date.

---

## ✨ Features

- 🌍 **Location-based search** – Enter any city and country to get prayer times.
- 🕋 **Six daily prayers** – Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha.
- 📅 **Gregorian & Hijri dates** – Displays both calendar systems for context.
- ⚡ **Async API calls** – Uses modern `async/await` and Fetch API.
- 🎨 **Clean, responsive UI** – Works on desktop, tablet, and mobile.
- 🧭 **Error handling** – Friendly messages for invalid inputs or network issues.

---

## 🛠️ Technologies Used

- **HTML5** – Semantic structure.
- **CSS3** (custom) – Responsive grid, modern styling with CSS variables.
- **JavaScript (ES6+)** – Async/await, Promises, DOM manipulation.
- **Aladhan API** – Islamic prayer times API https://aladhan.com/prayer-times-api

---

## 🚀 How to Use

1. Clone the repository or download the `index.html` file.
2. Open the file in any modern web browser.
3. Enter a **city** (e.g., `London`) and **country** (e.g., `UK`).
4. Click **Get Times**.
5. View the prayer times and date information displayed in a grid.

> **Note**: No build tools or server required – it's a single static HTML file.

---

## 📸 Screenshot

<img width="1904" height="944" alt="image" src="https://github.com/user-attachments/assets/9f56f4d0-a12f-4164-8ed4-3aea0f73b4a6" />

---

## 📡 API Reference

This project uses the Aladhan API https://aladhan.com/prayer-times-api with the **`timingsByCity`** endpoint:

```
https://api.aladhan.com/v1/timingsByCity?city={city}&country={country}&method=2
```

- `method=2` corresponds to the **Islamic Society of North America (ISNA)** calculation method. You can change it to other methods as needed (see [API docs](https://aladhan.com/prayer-times-api#GetTimingsByCity)).

---

## 🧪 Example

**Input**:  
- City: `Mecca`  
- Country: `Saudi Arabia`  

**Output** (sample):
- Fajr: `05:12`
- Sunrise: `06:32`
- Dhuhr: `12:18`
- Asr: `15:38`
- Maghrib: `18:04`
- Isha: `19:34`
- Date: `04 Mar 2026 (14 Ramadan 1447 AH)`

---

## 📂 Project Structure

```
islamic-prayer-times/
│
├── index.html          # Main application file (contains all HTML, CSS, JS)
└── README.md           # Project documentation
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request. You can also open an issue for bugs or feature requests.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Aladhan API](https://aladhan.com) for providing reliable prayer time data.
- Icons and design inspiration from the open-source community.

---

**Made with ❤️ for the global Muslim community.**
