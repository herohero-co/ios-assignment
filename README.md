# 🎧 iOS Developer Interview Assignment: SwiftUI Audio Player

## 🧠 Objective

Create a simple **Audio Player App** using **SwiftUI**. The app should fetch a list of songs from an API and allow the user to play a selected track.

---

## 📲 App Features

### 1. Song List Screen

- Fetch and display a list of songs from an API.
- Each list item should show:
  - Song title
  - Artist name
  - Optional: Artwork image (if available)
- Tapping on a song navigates to the **Player Screen**.

### 2. Player Screen

- Show:
  - Song title and artist
  - Artwork image (if available)
- Audio controls:
  - Play/Pause
  - Seek bar with current time and total duration
- Bonus:
  - Skip forward/backward
  - Show buffering/loading state

---

## 🔧 Requirements

- Use **SwiftUI** for UI.
- Implement audio playback using `AVPlayer` or similar.
- Fetch data from this API - https://harmanec.com/hh-assignment/tracks.json.
- Show loading indicators and handle errors (e.g., failed network request or audio playback issue).

---

## 🧪 Bonus (Optional)

- Implement background audio playback.
- Persist last played song and position.
- Add support for remote control (lock screen controls).
- Add simple unit tests for ViewModels.
- Display waveform or animation during playback.
- Add option to download song for offline use.

---

## 🗂 Submission Instructions

- Push the project to GitHub (public or private).
- Include a **README** that covers:
  - Instructions to run the app
  - Any assumptions or known issues

---

## ✅ Evaluation Criteria

- Clean and maintainable Swift code
- Use of proper architecture
- Effective use of **SwiftUI**
- Audio handling and UI responsiveness
- Attention to UX/UI details
- Bonus features and creativity
