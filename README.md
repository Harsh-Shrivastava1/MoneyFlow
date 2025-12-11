#  MoneyFlow – Personal Finance & Savings Tracker  
A modern Android app to track expenses, manage saving goals, visualize spending insights, and maintain better financial control.  
Built using **Kotlin**, **MVVM**, **Room DB**, **Coroutines/Flow**, and **Material 3 UI**.

---

##  Features

###  Expense Tracking
- Add, edit, and delete expenses  
- Categorize expenses (Food, Travel, Shopping, etc.)  
- Automatic total expense calculation  
- Clean, modern Material 3 card layout  

### Saving Goals
- Create saving goals with target amount  
- Track real-time progress with circular indicators  
- Add savings logs  
- Detailed analytics view for each goal  

### Smart Insights (Dashboard)
- Detects your highest spending category  
- Insights update automatically using Kotlin Flow  
- Motivational savings feedback  

### Beautiful Material 3 UI
- Premium bright theme  
- Smooth transitions & animations  
- Clean layout with guiding empty states  

### Offline First
- Uses **Room Database**  
- All data is stored securely on the device  

---

##  Tech Stack

| Layer | Technologies |
|------|--------------|
| **Architecture** | MVVM + Repository Pattern |
| **UI** | Material 3, RecyclerView, ConstraintLayout |
| **Database** | Room Persistence Library |
| **Async** | Kotlin Coroutines + StateFlow |
| **Language** | Kotlin |
| **App Storage** | Local (no backend needed) |

---

##  Project Structure

```
MoneyFlow/
│
├── data/
│   ├── dao/                
│   ├── database/           
│   ├── entities/          
│   └── repository/         
│
├── 
│
├── ui/
│   ├── dashboard/       
│   ├── expenses/          
│   ├── goals/             
│   ├── intro/             
│   └── base/              
├── utils/                 
└── MoneyFlowApplication.kt
```



##  Setup Instructions

### Clone Repository
```bash
git clone https://github.com/your-username/MoneyFlow.git
cd MoneyFlow
```

###  Open in Android Studio  
- Open → select project folder  
- Wait for Gradle to sync  

### Run App  
- Connect a device or launch emulator  
- Press **Run ▶**

---

##  Module Explanations

### ✔ Expense Module
- Stores expenses with category & timestamp  
- Total expense = Live from Room using Flow  

### ✔ Savings Module
- Tracks saving goals & amount saved  
- Progress calculation:
```
progress = (savedAmount / targetAmount) * 100
```

### ✔ Dashboard Module
- Combines expenses + goals using Flow  
- Shows total expense, total savings, and insights  

---

##  Why MoneyFlow?

- Lightweight  
- Fast UI  
- No login needed  
- 100% offline  
- Perfect for daily budgeting  

---

##  Contributing

```
1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Open a pull request  
```

---

