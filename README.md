# Maganatti Calendar

A dynamic, fully responsive annual calendar for **Maganatti Tech Solution**, featuring year toggles, print and PDF download, and brand styling.

---

## 🚀 Features

- **Dynamic Year**: Automatically displays the current year with Previous/Next controls
- **Print-Ready**: Clean layout optimized for printing (hides controls/services)
- **PDF Export**: Download calendar view as a PDF via html2canvas + jsPDF
- **Responsive Design**: Bootstrap 5 grid for mobile-friendly 1–3 column layouts
- **Branding**: Uses Maganatti Tech Solution logo and brand colors (`#0058a8`, `#f48a26`)
- **Services Section**: Sample list of company offerings shown below the calendar

---

## 📂 Project Structure

```plaintext
maganatti-calendar/
├── index.html      # Main calendar page
├── style.css       # Custom styles (brand colors, borders, hover effects)
├── script.js       # Calendar logic (rendering, year toggle, print & download)
├── maganatti-logo.png # Company logo
└── README.md       # This documentation
```

---

## 💻 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Optional: Local HTTP server for testing (e.g. Live Server extension, `python -m http.server`)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Waqo-Dida-Godana/maganatti-calendar.git
   cd maganatti-calendar
   ```

2. **Open in browser**
   - Double-click `index.html`, or
   - Serve via local HTTP server:
     ```bash
     python -m http.server 8080
     open http://localhost:8080/index.html
     ```

---

## 🎨 Usage

- Click **Previous Year** / **Next Year** to navigate between years.
- Click **Print Calendar** to open print dialog (controls and services hidden).
- Click **Download PDF** to save the current calendar view as `calendar-<year>.pdf`.

---

## 🛠️ Technologies

- **HTML5** & **CSS3**
- **Bootstrap 5** (grid, buttons)
- **JavaScript** (ES6 modules)
- **html2canvas** (screenshot capture)
- **jsPDF** (PDF generation)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

*© 2025 Maganatti Tech Solution*
