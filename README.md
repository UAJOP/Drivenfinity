# 🚗 Drivenfinity

**Drivenfinity** is a hyper-casual 3D mobile driving simulation game where players challenge themselves to achieve the highest possible score by navigating through obstacles without collisions. Designed for smooth gameplay and an engaging experience, the game pushes players to improve their reflexes and beat their own records.

---

## 🎮 Features

- **Challenging Endless Mode** – Keep driving, avoid obstacles, and beat your own high score.
- **Dynamic Speed Mechanic** – The longer you drive, the faster you go, making the game progressively harder.
- **Obstacle Avoidance System** – React quickly to avoid crashes and keep progressing.
- **Intuitive Touch Controls** – Smooth and responsive steering for an engaging experience.
- **High Score Tracking** – Compete against yourself to set new records.
- **Energy System** – Manage your energy levels to keep playing.

---

## 🔜 Future Enhancements

- **Multiple Levels with Unique Mechanics** – Expanding the game with different environments and new challenges.
- **Advanced UI Design** – Further refinements for a polished and immersive experience.
- **Game Music & Sound Effects** – A custom soundtrack and sound effects for a more engaging atmosphere.
- **New Power-Ups & Abilities** – Additional mechanics to enhance gameplay and variety.

---

## 🛠 Core Gameplay Mechanics

### 🚗 Car Controller (`Car.cs`)
- Handles vehicle movement, including acceleration and turning.
- Implements progressive speed increase over time.
- Detects collisions with obstacles and resets the game when necessary.

### 📊 Score System (`ScoreSystem.cs`)
- Tracks and displays the player’s current score.
- Saves and updates the highest score using `PlayerPrefs`.
- Updates and stores high scores upon game exit.

### 🎮 Main Menu (`MainMenu.cs`)
- Displays the high score and current energy level.
- Manages energy recharge and prevents playing when energy is depleted.
- Uses Unity’s `PlayerPrefs` to store and retrieve game data.
- Handles scene transitions.

### 🔔 Android Notification Handler (`AndroidNotificationHandler.cs`)
- Schedules and sends notifications when energy is recharged (Android only).
- Registers a notification channel and delivers alerts to encourage player engagement.

---

## 📦 Installation & Setup

1. Clone the repository:
   git clone https://github.com/yourusername/drivenfinity.git
2. Open the project in **Unity (Recommended Version: 2021 or later)**.
3. Ensure **TextMeshPro** and **Android Notifications Package** (for Android builds) are installed.
4. Build and deploy the game to your mobile device.

---

## 🎯 How to Play

1. Steer left and right to avoid obstacles.
2. Survive as long as possible to achieve a higher score.
3. Keep track of your energy – once depleted, wait for a recharge or receive a notification when it's ready!

---

## 🤝 Contributing

We welcome contributions! Feel free to submit pull requests or report issues.

---

## 📜 License

This project is licensed under the ** UnLicense**.
