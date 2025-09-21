# K-lana AI - Smart Homework & Doubt Solver 🧠

A fully responsive, ultra-modern web application that helps Class 10 students solve doubts, complete homework, and unlock amazing rewards through an innovative XP system.

## 🌟 Features

### 📚 Doubt Section
- **AI-Powered Solutions**: Get instant, step-by-step solutions for any subject
- **Multi-Subject Support**: Mathematics, Physics, Chemistry, Biology, English, Social Science
- **Smart Explanations**: Clear, detailed explanations tailored for Class 10 level
- **Save & Copy**: Save solutions for later reference or copy to clipboard

### 📝 Homework Section  
- **Batch Processing**: Add multiple homework questions at once
- **AI Solving**: Comprehensive solutions for all questions simultaneously
- **PDF Generation**: Beautiful, formatted PDF compilation of all answers
- **Professional Layout**: Ruled pages, proper headings, readable fonts

### 🏆 Reward System
- **XP Points**: Earn XP for every doubt solved and homework completed
- **Sample Papers**: Unlock 30+ Class 10 sample papers at 20,000 XP
- **Premium Features**: Advanced AI tutoring at 100,000 XP
- **Progress Tracking**: Visual progress bars and achievement badges
- **Google Drive Integration**: Direct access to curated study materials

### 🎨 Modern UI/UX
- **Responsive Design**: Perfect on mobile, tablet, and desktop
- **Dark/Light Mode**: Eye-friendly themes with smooth transitions
- **Smooth Animations**: GSAP-powered animations and micro-interactions
- **Clean Interface**: Modern, minimalist design with intuitive navigation
- **Real-time Feedback**: Loading states, notifications, and progress indicators

## 🚀 Technology Stack

### Frontend
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6+)**: Modern features, async/await, classes
- **GSAP**: Professional animations and transitions

### APIs & Integrations
- **OpenRouter API**: AI model integration (google/gemma-2-27b-it:free)
- **jsPDF**: Client-side PDF generation
- **Google Drive API**: Sample papers and resources
- **LocalStorage**: User data persistence

### External Libraries
- **Font Awesome**: Beautiful icons
- **Inter Font**: Modern typography
- **Service Worker**: Offline support and caching

## 📱 Device Compatibility

- **Mobile**: iOS Safari, Android Chrome, responsive touch interface
- **Tablet**: iPad, Android tablets, optimized layouts
- **Desktop**: Chrome, Firefox, Safari, Edge

## 🎯 XP System

| Action | XP Earned |
|--------|-----------|
| Solve Doubt | 50 XP |
| Complete Homework Question | 25 XP |
| Generate PDF | 100 XP |

### Rewards Unlocked
- **20,000 XP**: 30+ Sample Papers from Google Drive
- **100,000 XP**: Premium AI Features & Personalized Study Plans

## 🔧 Installation & Setup

1. **Clone/Download** the project files
2. **Open Terminal** in the project directory
3. **Start Local Server**:
   ```bash
   python -m http.server 8000
   ```
4. **Open Browser** and navigate to `http://localhost:8000`

## 📂 Project Structure

```
K-lana AI/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS framework
├── script.js           # Core JavaScript application
├── sw.js              # Service Worker for offline support
└── README.md          # This documentation
```

## 🔐 API Configuration

The application uses OpenRouter API with the following configuration:
- **API Key**: Pre-configured (included in code)
- **Model**: google/gemma-2-27b-it:free
- **Endpoint**: https://openrouter.ai/api/v1/chat/completions

## 💾 Data Storage

- **User Progress**: Stored in browser's LocalStorage
- **XP Points**: Persistent across sessions
- **Saved Solutions**: Available for future reference
- **Theme Preference**: Remembered between visits

## 🔄 Offline Support

- **Service Worker**: Caches essential files
- **Fallback Responses**: Available when AI service is unavailable
- **Local Data**: Progress saved locally

## 🎨 Customization

### Color Themes
The app supports light and dark themes with CSS custom properties:
```css
:root {
    --primary: #667eea;
    --secondary: #764ba2;
    --accent: #f093fb;
    /* ... more variables */
}
```

### Responsive Breakpoints
- **Mobile**: max-width: 768px
- **Small Mobile**: max-width: 480px

## 🚀 Performance Features

- **Lazy Loading**: Optimized resource loading
- **Smooth Animations**: 60fps animations with GSAP
- **Efficient Caching**: Service Worker implementation
- **Optimized Images**: Minimal resource usage

## 🔒 Security Features

- **API Key Protection**: Secure API integration
- **Input Validation**: Prevents malicious input
- **CORS Handling**: Proper cross-origin setup

## 🎯 Future Enhancements

- **Voice Input**: Speech-to-text for questions
- **Leaderboard**: Compete with other students
- **Daily Streaks**: Consistency rewards
- **Subject-wise Analytics**: Detailed progress tracking
- **Collaborative Features**: Study groups and sharing

## 🐛 Troubleshooting

### Common Issues

1. **AI Not Responding**
   - Check internet connection
   - Fallback responses are provided
   - Try again after a moment

2. **PDF Generation Issues**
   - Ensure browser supports jsPDF
   - Check for popup blockers

3. **Theme Not Switching**
   - Clear browser cache
   - Check localStorage permissions

## 📞 Support

For issues or feature requests, the application includes:
- **Built-in Notifications**: Real-time feedback
- **Error Handling**: Graceful degradation
- **Fallback Mechanisms**: Works even without AI

## 📄 License

This project is created for educational purposes and includes all necessary components for a complete learning management system.

---

**Built with ❤️ for students who want to excel in their studies!**