# 📐 Gyro Heading Tracker

A simple browser-based compass that uses your device’s gyroscope to track and display your current heading. Built with React and Framer Motion.

> 🧠 **Originally built for use with LEGO Spike Prime** to assist in directional calibration during robotics development.

---

## 🚀 Features

* Real-time heading display (yaw)
* Reset heading to make current direction "0°"
* Save, restore, rename, and delete resets
* Undo reset history
* Visual rotation indicator with smooth animation

---

## 📸 Preview

![image](https://github.com/user-attachments/assets/50f7e919-d97c-49e2-bcec-cf8788eace52)


---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/gyro-heading-tracker.git
cd gyro-heading-tracker
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Then open your browser to [http://localhost:5173](http://localhost:5173)

---

## 🧭 How to Use

* Rotate your phone/device to see the heading update.
* Tap **Reset Yaw** to make your current direction the new 0°.
* Then the program automatically lists out your previous yaw offsets to go back to if you would like.
* Tap on any saved yaw reference point to restore that yaw reference point offset.
* Use the ✏️ icon to rename saved yaw reference points, and 🗑️ to delete them.
> Best used on mobile devices that support gyroscope input.

---

## 🤖 Why This Exists

This tool was built to assist in calibrating turning directions for a LEGO Spike Prime robot as part of a robotics showcase. The app allows for quick resets and heading snapshots to help with alignment and consistency during testing on real surfaces.

---

## 🌐 Deployment

This project is deployed using [Vercel](https://vercel.com). Any commit to the `main` branch is automatically deployed.

---

## 📦 Built With

* [React](https://reactjs.org/)
* [Framer Motion](https://www.framer.com/motion/)
* [Vite](https://vitejs.dev/)
* [Tailwind CSS](https://tailwindcss.com/)

---

## 📄 License

MIT License. Do whatever you want, just don’t claim it’s yours.
