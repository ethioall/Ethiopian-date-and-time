# Ethiopian Current Local Date and time Display

This project is a simple, elegant web application that displays the current **Ethiopian date and time**, alongside real-time global times for various major cities. It's designed to be user-friendly, visually appealing, and provides a quick reference for understanding time differences.

---

## 🌟 Features

- **Real-time Ethiopian Date**  
  Displays the current Ethiopian day (Amharic), month (Amharic), date, and year, along with the numeric date format.

- **Precise Ethiopian Time**  
  Shows the current Ethiopian time, including the period (e.g., `ከጠዋቱ` for morning).

- **Global Time Zones**  
  Provides real-time updates for major cities around the world, including **New York, London, Tokyo, Dubai, Sydney, and Paris**.

- **Responsive Design**  
  Optimized for various screen sizes, from mobile devices to desktops, ensuring a consistent user experience.

- **Modern UI/UX**  
  Features a clean design with a subtle hover effect on the main display container, enhancing user interaction.

- **Dynamic Updates**  
  Both Ethiopian and global times are fetched and updated periodically from external APIs to ensure accuracy.

---

## 🛠 Technologies Used

- **HTML5** – For the structure of the web page.  
- **CSS3** – For styling, including custom CSS variables and gradient text effects.  
- **Tailwind CSS** – A utility-first CSS framework for rapid UI development and responsive design.  
- **JavaScript (ES6+)** – For fetching data from APIs, updating the DOM, and handling real-time clock functionality.

---

## 🌐 API References

This application relies on the following external APIs:

### Ethiopian Date API

- **Base URL:** `https://api.ethioall.com/date/api`  
- **Sample Response:**
```json
{
  "day_amharic": "ሰኞ",
  "day_english": "Monday",
  "month_amharic": "ኃምሌ",
  "month_english": "Hamle",
  "month_number": 11,
  "date": 14,
  "year": 2017,
  "numeric_date": "14-11-2017"
}
````

### Ethiopian Time API

* **Base URL:** `https://api.ethioall.com/time/api`
* **Sample Response:**

```json
{
  "system_time": "07:02:41",
  "ethiopian_time": {
    "hour": 1,
    "minute": 2,
    "second": 41,
    "period_amharic": "ከጠዋቱ"
  }
}
```

### World Time API (for Global Times)

* **Base URL:** `https://worldtimeapi.org/api/timezone/{timezone}`
* **Example:** `https://worldtimeapi.org/api/timezone/America/New_York`

---

## 🚀 Setup and Usage

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ethioall/Ethiopian-date-and-time
   cd Ethiopian-date-and-time
   ```

2. **Open the application:**

   * Open the `index.html` file in your web browser.
   * The page will automatically fetch and display the date and time information.

---

## 📁 Project Structure

```
.
├── index.html          # Main application file (HTML, CSS, JavaScript)
└── README.md           # This README file
```

---

## 🤝 Contributing

Contributions are welcome!
If you have suggestions for improvements, new features, or bug fixes, please **open an issue** or **submit a pull request**.

---

## 📄 License

This project is open-source and available under the **MIT License**.

