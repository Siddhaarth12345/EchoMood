# 🎵 MoodTunes — Music That Matches Your Soul

**MoodTunes** is a modern, high-fidelity music discovery platform that goes beyond genres to find music that resonates with your current (or target) emotional state. Built with a "Dark Cosmic" aesthetic and powered by a custom emotion-blending engine, it transforms how you explore and experience music.

![MoodTunes Hero](https://via.placeholder.com/1200x600/07070f/c084fc?text=MoodTunes+—+Discover+Music+By+Emotion)

## ✨ Key Features

### 🎨 1. Emotion Blender
Discover the unique intersection of two different feelings.
- **50+ Nuanced Emotions**: Choose from feelings like *Wistful, Awestruck, Languid, Brooding, Transcendent,* and more.
- **Instant Synergy**: Combine two feelings (e.g., *Euphoric × Melancholic*) to get a curated 10-song playlist at their emotional center.
- **Smart Mapping**: Recommends music based on calculated *Valence* (Happiness) and *Energy* (Intensity).

### 🛣️ 2. Emotional Journeys
A 5-stage musical arc designed to transition your mood.
- **Journey Presets**: Quick-start journeys like *Morning Kickstart* or *Heartbreak Heal*.
- **Custom Arc**: Define your starting and target emotions (e.g., *Sad* to *Happy*) and get a 15-song sequence that bridges the gap.
- **Variety Guaranteed**: Advanced deduplication ensures 15 unique, non-repeating tracks per journey.

### 📁 3. Persistent Playlist Builder
- **Personal Queue**: Save your favorite discoveries with a single click.
- **Local Persistence**: Your playlist is saved to `localStorage`, so your songs are there even after a refresh.
- **Queue Control**: Reorder, remove, or clear your tracks in our sleek glassmorphism side panel.

### 🔊 4. Full Song Playback
- **SoundCloud Integration**: Move beyond 30-second previews with our embedded full-track player.
- **Multi-Platform Fallbacks**: If a track isn't on SoundCloud, quickly jump to **YouTube Music** or **Spotify** via integrated links.

### 🌍 5. Global & Regional Support
- **Multi-Language Presets**: Tailor your results to specific markets like *Tamil (Modern, 90s, AR Rahman)*, *Hindi (Bollywood, Indie)*, *K-Pop*, *Spanish*, and more.
- **Strict Filtering**: Our recommendation engine ensures that results stay within your selected language profile.

---

## 🛠️ Tech Stack
- **Frontend**: React 18, Framer Motion (Animations)
- **Styling**: Vanilla CSS (Global Variables, Glassmorphism, Advanced Gradients)
- **APIs**: 
  - **iTunes Search API**: (Primary) Metadata and 30s previews (100% Free, No Key needed).
  - **SoundCloud**: Full song embedding via search-based iframe integration.
- **Persistence**: Browser LocalStorage for Playlists and Search History.

---

## 🚀 Getting Started

### 1. Installation
Ensure you have [Node.js](https://nodejs.org/) installed, then run:
```bash
git clone https://github.com/YOUR_USERNAME/moodtunes.git
cd moodtunes/moodtunes
npm install
```

### 2. Run Locally
```bash
npm start
```
The app will be available at `http://localhost:3000`.

---

## 🎨 Design Language
- **Theme**: Dark Cosmic (Deep blacks, vibrant purples, and blues).
- **Aesthetic**: Glassmorphism (Translucent surfaces with heavy blurs).
- **Typography**: Playfair Display (Headers) & Inter (UI text).
- **Animations**: Smooth transitions powered by CSS Keyframes and Framer Motion.

---

## 🤝 Credits & Disclaimer
- **Music Data**: Provided by the Apple iTunes Search API.
- **Full Streams**: Powered by SoundCloud Embeds.
- **Project Goal**: Created as a free, client-side tool for emotional music discovery.

---

**Made with 💜 for music lovers everywhere.**
