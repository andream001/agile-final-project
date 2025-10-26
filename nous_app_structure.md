
# NousApp - Project Structure

## 1. High-Level Directory Structure

```
nous-app/
├── src/
│   ├── components/         # Reusable UI components (e.g., buttons, cards)
│   ├── screens/            # Main screens of the app
│   │   ├── DailyRitual/
│   │   ├── AtomicHabits/
│   │   ├── EnergyCodes/
│   │   ├── ExpansionMode/
│   │   └── VibrationMonitor/
│   ├── navigation/         # Navigation configuration
│   ├── services/           # API calls, data management
│   ├── assets/             # Images, fonts, etc.
│   └── App.js              # Main app component
├── .gitignore
├── babel.config.js
├── index.js
├── package.json
└── README.md
```

## 2. Feature Breakdown

### 2.1. Rotina de Elevação Diária (DailyRitual)
- **Screen:** `src/screens/DailyRitual/index.js`
- **Components:**
    - `RitualTimer.js`: 5-minute timer component.
    - `MudraSelector.js`: Component to display and select Mudras.
    - `Affirmation.js`: Displays daily affirmations.
    - `EmotionTracker.js`: Component for logging emotional state.

### 2.2. Hábitos Atômicos Espirituais (AtomicHabits)
- **Screen:** `src/screens/AtomicHabits/index.js`
- **Components:**
    - `HabitList.js`: Lists the atomic habits.
    - `HabitTracker.js`: Tracks completion of habits.

### 2.3. Códigos Energéticos (EnergyCodes)
- **Screen:** `src/screens/EnergyCodes/index.js`
- **Components:**
    - `CodeLibrary.js`: Illustrated library of Mudras, Mantras, and frequencies.
    - `CombinationBuilder.js`: Allows users to create combinations.
    - `PointsTracker.js`: "Luz acumulada" system.

### 2.4. Modo Expansão (ExpansionMode)
- **Screen:** `src/screens/ExpansionMode/index.js`
- **Components:**
    - `LessonViewer.js`: Displays lessons from the books.
    - `Journal.js`: "Diário quântico" for reflections.

### 2.5. Monitor de Vibração e Presença (VibrationMonitor)
- **Screen:** `src/screens/VibrationMonitor/index.js`
- **Components:**
    - `MoodChart.js`: Displays the mood and energy graph.
    - `ReportGenerator.js`: Generates weekly reports.

