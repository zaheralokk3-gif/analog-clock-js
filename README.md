# ⏰ Analog Clock (JavaScript Bootcamp Project)

A sleek, fully functional Interactive Analog Clock built with HTML5, CSS3, and Vanilla JavaScript. This project was created as part of hands-on practice during a JavaScript Bootcamp.

It tracks real-time system time and smoothly updates the clock hands (Hours, Minutes, and Seconds) using mathematical degree calculations.

---

## 🌟 Features

- 🕒 Real-Time Tracking: Automatically syncs with the user's local system time.
- 📐 Smooth Rotations: Precise angle calculations ($360^\circ$) for smooth movements of all three hands.
- 🎨 Clean UI: Styled with modern CSS without relying on any external libraries or frameworks.
- 📱 Responsive Design: Fits comfortably across different screen sizes.

---

## 🎓 Learning Outcomes

This project was built to master key front-end and JavaScript concepts:
- Working with JavaScript's Date() object.
- DOM manipulation and dynamic updates using setInterval().
- Applying basic trigonometry/geometry concepts for $360^\circ$ element positioning.
- Advanced CSS properties like transform and transform-origin.

---

## 🛠️ Tech Stack

- HTML5: Structure of the clock container and hands.
- CSS3: Styling, layout, and rotation pivots.
- JavaScript (ES6): Core logic, time retrieval, and rotation degree calculations.

---

## 📐 Mathematical Logic

The movement of the clock hands is based on a $360^\circ$ circle:
- Seconds Hand: Each second represents $6^\circ$ ($\frac{360^\circ}{60}$).
- Minutes Hand: Each minute represents $6^\circ$ ($\frac{360^\circ}{60}$).
- Hours Hand: Each hour represents $30^\circ$ ($\frac{360^\circ}{12}$) + minute offset for seamless movement between hours.

---

## 🚀 How to Run

1. Clone the repository:
   `bash
   git clone [https://github.com/your-username/js-analog-clock.git](https://github.com/your-username/js-analog-clock.git)
