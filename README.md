# Portuguese GCSE Audio Trainer 🎧

A modern, offline-capable web application designed to help GCSE students master Portuguese listening and speaking skills through interactive audio exercises.

## Features

✨ **Core Learning Features:**
- 🎵 Real GCSE-style listening exercises with professional audio
- 🎤 Speaking practice with recording and playback
- 📚 Comprehensive vocabulary builder with pronunciation guides
- ✏️ Interactive grammar exercises with instant feedback
- 📊 Detailed progress tracking and statistics
- 🌙 Full offline functionality (works anywhere, anytime)

🔧 **Technical Features:**
- Progressive Web App (PWA) - install as a native app
- Works on all devices (desktop, tablet, mobile)
- Offline support via Service Worker
- Local storage for progress tracking
- Dark mode support
- Responsive design

## Getting Started

### Installation

#### As a Web App:
1. Open the app in your browser
2. Click the **"Install"** button or use your browser's menu to **"Add to Home Screen"**
3. Launch from your home screen or app drawer

#### In Browser:
Simply visit the hosted URL and start learning immediately.

### Quick Start Guide

1. **Home Tab** - Overview of features and quick navigation
2. **Listen & Repeat Tab** - Core listening exercises
   - Select a category (Greetings, Daily Routines, Food, etc.)
   - Listen to authentic Portuguese audio
   - View transcriptions
   - Record yourself and compare
3. **Vocabulary Tab** - Build your Portuguese vocabulary
   - Learn themed vocabulary with pronunciation
   - Listen to native pronunciation guides
4. **Grammar Tab** - Master Portuguese grammar rules
   - Practice verb conjugations
   - Learn sentence structures
   - Get instant feedback
5. **Progress Tab** - Track your learning journey
   - View statistics and achievements
   - Monitor progress by category
   - Export your results

## Usage Tips

### Listening Exercises
- 🔊 **Play Audio** - Listen to the full speed Portuguese audio
- 🐢 **Slow Speed** - Listen at 75% speed for better comprehension
- 📖 **Show Transcription** - See the Portuguese text and English translation
- 🎤 **Record Yourself** - Practice speaking and compare with the original

### Best Practices
1. **Before Recording** - Listen to the audio 2-3 times
2. **Try Recording** - Record your own pronunciation
3. **Compare** - Play back your recording and the original
4. **Review Weak Areas** - Use progress tracking to focus on challenging content
5. **Practice Regularly** - Consistent daily practice yields best results

## Data & Privacy

- ✅ All your progress is stored **locally on your device**
- ✅ No data is sent to external servers
- ✅ Your recordings are only stored in your browser
- ✅ Complete privacy and control of your learning data

### Exporting Data
1. Go to the **Progress** tab
2. Click **"Export Results"**
3. Download your progress as a JSON file
4. Share with your teacher for feedback

### Resetting Progress
- To reset all progress, go to **Progress** tab → **"Reset Progress"**
- This action cannot be undone

## Offline Functionality

This app is fully functional offline after the first load:

1. ✅ All exercises and content are cached
2. ✅ Recording and playback work offline
3. ✅ Progress is saved locally
4. ✅ No internet connection required

Simply load the app once while connected, and you can use it anywhere!

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Microphone access (for speaking practice)
- ~5MB storage space for the app

## Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome/Chromium | ✅ Full | Best performance |
| Firefox | ✅ Full | Full support |
| Safari | ✅ Full | iOS 15.1+ recommended |
| Edge | ✅ Full | Full support |
| Mobile Safari | ⚠️ Limited | Recording may be limited |

## Content Coverage

### Listening Exercises
- Greetings & Introductions
- Daily Routines
- Food & Drinks
- Shopping
- Travel & Transport
- School & Education

### Vocabulary Themes
- Numbers & Counting
- Colors & Descriptions
- Family & Relations
- Animals
- Clothes & Fashion
- Sports & Hobbies

### Grammar Topics
- Present Tense
- Past Tense
- Future Tense
- Adjectives & Agreement
- Pronouns
- Prepositions

## Troubleshooting

### Microphone Not Working?
1. Check browser permissions (Settings → Privacy & Security)
2. Ensure no other app is using the microphone
3. Try a different browser
4. Restart your device

### Audio Not Playing?
1. Check system volume
2. Clear browser cache
3. Try refreshing the page
4. Check your speakers/headphones

### Progress Not Saving?
1. Check if localStorage is enabled in browser settings
2. Ensure sufficient storage space
3. Try clearing browser cache (but not site data)

### App Not Loading?
1. Check internet connection (for initial load)
2. Clear browser cache
3. Try a different browser
4. Check if JavaScript is enabled

## Settings

Access settings through the **Settings** link in the footer:
- Dark Mode (automatic based on system preference)
- Audio Quality (automatic optimization)
- Microphone Permissions
- Data Management

## For Teachers

### Recommended Usage

1. **In Classroom:**
   - Use for warm-up exercises
   - Listen & Repeat for pronunciation practice
   - Grammar exercises for reinforcement

2. **For Homework:**
   - Students can practice all exercises
   - Track progress via export feature
   - Review vocabulary themes

3. **For Revision:**
   - Complete all exercises in a category
   - Monitor progress statistics
   - Focus on weak areas

### Sharing Student Progress
Students can export their progress from the Progress tab and share with you via:
- Email
- Learning Management System
- Direct file upload

## Technical Information

### Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Storage:** LocalStorage API
- **Offline:** Service Worker API
- **Audio:** Web Audio API, MediaRecorder API
- **Speech:** Web Speech API (for pronunciation)

### File Structure
```
/
├── index.html           # Main app structure
├── styles.css          # Complete styling
├── app.js              # Application logic
├── sw.js               # Service worker for offline
├── manifest.json       # PWA configuration
└── README.md          # This file
```

## Version History

### v1.0 (Current)
- Initial release
- Full listening, vocabulary, and grammar exercises
- Progress tracking
- Offline support
- Recording functionality

## Future Features (Planned)

- 🎯 Listening comprehension quizzes
- 📱 Mobile app versions
- 🌐 Multiplayer practice sessions
- 🗣️ AI-powered pronunciation feedback
- 📈 Detailed analytics dashboard
- 🎓 Teacher dashboard for class management
- 🔊 Higher quality audio samples
- 🌍 More regional accents

## Support & Feedback

Having issues or suggestions? Please:
1. Check the Troubleshooting section above
2. Contact your teacher
3. Provide detailed information about the issue
4. Include your browser and device information

## License

© 2026 Portuguese GCSE Audio Trainer. Educational use permitted.

## Credits

Designed and developed for GCSE Portuguese learners.

---

**Happy Learning! 🎧📚** 

Boa Sorte! 🍀
