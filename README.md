# TO-DO-list-with-ding-list

---

# Ding! • The Most Beautiful To-Do App Ever Made

![Ding App Screenshot](screenshot.png) <!-- Replace with actual screenshot -->

**Ding!** is a visually stunning, interactive to-do app that makes completing tasks feel magical. With a clean UI, animated confetti celebrations, theme switching, a Pomodoro timer, and mood tracking, it’s designed to make productivity fun and rewarding.

---

## Features

* **Task Management**

  * Add, complete, and delete tasks.
  * Tasks are stored in `localStorage` for persistence.
  * Daily task completion progress with a visually animated ring.

* **Stats**

  * Daily task completion count.
  * Streak tracker for consecutive productive days.
  * Daily goal tracking (default: 8 tasks).

* **Pomodoro Timer**

  * Built-in focus timer (25 minutes by default).
  * Start/Reset functionality.
  * Celebration confetti on completion.

* **Themes**

  * Switch between multiple vibrant themes:

    * Sakura, Matcha, Ocean, Sunset, Midnight, Peach.
  * Theme preferences are stored in `localStorage`.

* **Mood Tracking**

  * Emoji-based mood tracker.
  * Fun confetti animation when clicking mood buttons.

* **Interactive Animations**

  * Confetti for task completion and milestones.
  * Animated task entrance and delete transitions.
  * Sound effects for task completion, level up, and deletion.

---

## Demo

You can try the live demo here: [Link to your live demo]

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ding-todo-app.git
cd ding-todo-app
```

2. Open `index.html` in your browser.

No additional dependencies are required as all scripts are included via CDN.

---

## Usage

* **Adding Tasks:** Type your task in the input box and click `+` or press Enter.
* **Completing Tasks:** Click on the task text to mark it as done. Enjoy the confetti!
* **Deleting Tasks:** Click the red `×` button.
* **Switching Themes:** Click a theme dot on the top-right.
* **Pomodoro Timer:** Start a 25-minute focus session and reset if needed.
* **Tracking Mood:** Click an emoji to express how you feel.

---

## Technologies Used

* HTML5
* CSS3 (with CSS Variables and Backdrop Filters)
* JavaScript (Vanilla)
* Canvas Confetti ([canvas-confetti CDN](https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js))

---

## File Structure

```
ding-todo-app/
│
├── index.html        # Main HTML file
├── README.md         # Project documentation
└── assets/           # Optional: store images or sounds locally
```

---

## Future Enhancements

* Sync tasks across devices with cloud storage.
* Customizable daily goals.
* Notifications for Pomodoro timer completion.
* More moods, themes, and animations.

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

* Confetti animations powered by [canvas-confetti](https://github.com/catdad/canvas-confetti)
* Sound effects from [Mixkit](https://mixkit.co)

---


