# Guess The Tune

Game inspired by [https://whatsamook.games/mu](https://zbiorkom.live/krakow) (a little bit)

Planned project start: 2025/09/01
Planned project completion: 2026/12/01

A fun, real-time “guess the tune” phone and web game where players pick songs and challenge friends (or strangers) to identify them. Perfect for music lovers, parties, classrooms, and anyone who wants to test their ear for melody!

## 🎵 Features:

- **Real-time gameplay**: Host or join rooms that update instantly as players submit guesses.
- **Custom song selection**: Any player can choose a track from YouTube, SoundCloud, or a custom URL.
- **Timed rounds**: Set a time limit per melody to keep the game fast and exciting.
- **Scoreboard & leaderboards**: Track individual and cumulative scores.  
- **Chat & reactions**: Cheering, taunting, or sending hints—interact as you play.
- **Mobile-friendly responsive UI**: Play on phones, tablets, or desktop browsers.

## 🛠️ Tech Stack - fullstack by me:

- **Frontend **: React + Tailwind CSS + ShadCN
- **Mobile version **: React Native
- **Backend **: Node.js + Express + Python + AI API
- **Real-time**: Socket.io  
- **Database**: MongoD

## 🤖 AI Features:
### 1. Real-Time Hint Generator  
Stuck on a tricky melody? Our AI listens to the clip and, if no one’s guessed after 10 seconds, drops context-aware hints—artist trivia, release year, or a lyric snippet—to nudge players toward the right answer without giving it away.

### 2. Not sure what song to choose? Give us the genre and the character, and AI will give you some examples.

### 3. Real-Time Vocal Isolation  
An AI audio filter that separates vocals from instrumentation on the fly—helping players focus purely on melody or, if they prefer, play only the instrumental track for an extra challenge.

### 4. Acoustic Fingerprint Search
Upload a recorded humming or whistle of the melody and our AI fingerprinting engine matches it to the closest song in the database—ideal for when you can’t recall the title but remember the tune.
(API maybe like https://docs.acrcloud.com/reference/identification-api ;  https://docs.audd.io/ )

### 5. Custom Challenge Generator  
AI crafts bespoke round rules—like “only instrumentals with piano,” “songs under 2 minutes,” or “duets”—based on player preferences and past performance data.
