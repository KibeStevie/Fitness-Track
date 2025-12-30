# 🏃‍♂️ Fitness Track 

Fitness Track is a **desktop fitness tracking application** built with **Python, PyQt6, SQLite, and Matplotlib**. It allows users to log workouts, track calories and distance, visualize progress, and switch between light and dark modes.

---

## ✨ Features

* 📅 Add workout entries (date, calories burned, distance, description)
* 🗄️ Persistent storage using **SQLite**
* 📊 Data visualization using **Matplotlib** (Distance vs Calories)
* 🧾 View workouts in a sortable table
* 🗑️ Delete selected workout entries
* 🌗 Toggle **Light / Dark Mode**
* 🧹 Clear input fields and reset charts
* 🖥️ Modern GUI built with **PyQt6**

---

## 🛠️ Technologies Used

* **Python 3.10+**
* **PyQt6** – GUI framework
* **SQLite (QSqlDatabase)** – Local database
* **Matplotlib** – Data visualization

---

## 📂 Project Structure

```text
Fitness-Track/
│
├── main.py              # Main application file
├── fitness.db           # SQLite database (auto-created)
├── README.md            # Project documentation
└── .venv/               # Virtual environment (recommended)
```

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Fitness-Track.git
cd Fitness-Track
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

* **Windows (PowerShell)**

```powershell
.\.venv\Scripts\Activate.ps1
```

* **Linux / macOS**

```bash
source .venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install PyQt6 matplotlib
```

(Optional)

```bash
pip install pyinstaller
```

---

## ▶️ Running the Application

```bash
python main.py
```

The SQLite database (`fitness.db`) will be created automatically on first run.

---

## 📊 How It Works

1. Enter workout details (date, calories, distance, description)
2. Click **Add** to save the workout
3. View workouts in the table
4. Click **Submit** to visualize calories vs distance
5. Use **Delete** to remove selected workouts
6. Toggle **Dark Mode** for a different theme

---

## 📦 Building a Windows Executable (Optional)

```bash
pyinstaller main.py --noconsole --onefile --name FitnessTrack
```

The executable will be available in the `dist/` folder.

---

## 🧠 Known Improvements / Future Enhancements

* Input validation for numeric fields
* Edit/update existing workouts
* Export data to CSV
* More charts (weekly/monthly summaries)
* User profiles & authentication

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/my-feature`)
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Stephen Kibe**
Software Developer

---

⭐ If you like this project, give it a star and feel free to improve it!
