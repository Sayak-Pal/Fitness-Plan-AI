# FitPlan AI

A rule-based fitness and diet planner with an AI-like user experience. Get personalized 10-week fitness and nutrition plans without any signup required.

## ✨ Features

- **Personalized Plans**: Customized 10-week fitness and diet plans based on your goals, fitness level, and health conditions
- **Progressive Training**: Smart progression system that adapts workout intensity week by week
- **Smart Nutrition**: Meal plans tailored to your dietary preferences, restrictions, and fitness goals
- **No Signup Required**: Start your fitness journey instantly with rule-based AI
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🎯 Fitness Goals Supported

- Weight Loss
- Muscle Gain
- Fat Loss + Toning
- General Fitness
- Endurance Improvement

## 🏃‍♂️ Workout Types

- Cardio workouts
- HIIT (High-Intensity Interval Training)
- Strength training
- Compound movements
- Isolation exercises
- Flexibility and mobility

## 🍽️ Nutrition Features

- Calorie calculations based on your goals
- Multiple cuisine preferences
- Dietary restrictions support
- Weekly meal planning
- Macro-balanced nutrition

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd "Fitness Plan AI"
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## 🏗️ Project Structure

```
Fitness Plan AI/
├── src/
│   ├── components/          # Reusable UI components
│   ├── context/            # React context providers
│   │   └── UserContext.jsx # User state management
│   ├── data/               # Static data and rules
│   │   ├── diets.json      # Diet and meal data
│   │   ├── rules.json      # Fitness and nutrition rules
│   │   └── workouts.json   # Exercise database
│   ├── pages/              # Application pages
│   │   ├── Dashboard.jsx   # Main dashboard
│   │   ├── DietWeek.jsx    # Weekly diet plans
│   │   ├── Landing.jsx     # Landing page
│   │   ├── PlanOverview.jsx # Plan summary
│   │   ├── Profile.jsx     # User profile
│   │   ├── Progress.jsx    # Progress tracking
│   │   ├── Register.jsx    # User registration
│   │   └── WorkoutDay.jsx  # Daily workout details
│   ├── App.jsx             # Main application component
│   ├── index.css           # Global styles
│   └── main.jsx            # Application entry point
├── index.html              # HTML template
├── package.json            # Project dependencies
└── vite.config.js          # Vite configuration
```

## 🛠️ Technology Stack

- **Frontend**: React 18 with Vite
- **Routing**: React Router DOM
- **Styling**: CSS with custom properties
- **Build Tool**: Vite
- **Package Manager**: npm

## 📱 Pages Overview

- **Landing**: Welcome page with feature highlights
- **Register**: Multi-step user onboarding form
- **Dashboard**: Main hub with quick access to plans and progress
- **Plan Overview**: Complete 10-week plan summary
- **Workout Day**: Detailed daily workout instructions
- **Diet Week**: Weekly meal plans and nutrition info
- **Progress**: Track your fitness journey
- **Profile**: Manage your personal information

## 🎨 Design System

The app uses a modern design system with:
- Fitness green (`--fitness-green`) and energy orange (`--energy-orange`) color scheme
- Responsive grid layouts
- Card-based UI components
- Gradient backgrounds
- Clean typography

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## Owner

Sayak , Ritwik , Praneeth , Ankit

## 🔮 Future Enhancements

- Exercise video demonstrations
- Progress photos and measurements
- Social sharing features
- Workout reminders and notifications
- Integration with fitness trackers
- Advanced analytics and insights

---

**Start your fitness journey today with FitPlan AI!** 🏋️‍♀️💪