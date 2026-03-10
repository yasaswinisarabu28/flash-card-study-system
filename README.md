# Flashcard Study App

A modern, interactive flashcard application built with HTML, CSS, and JavaScript to help you study and memorize information effectively.

## 📁 Project Structure

```
d:\main study app\
├── 1 title.html          # Landing/Title page
├── 2 login.html          # User login page
├── 3 create flashcard.html # Create new flashcards
├── 4 flipcard.html       # Main flashcard game/study mode
├── 5 dashboard.html      # User dashboard
├── 6 navigation.html     # Navigation components
└── README.md            # This file
```

## 🎯 Features

### Core Functionality
- **Interactive Flashcards**: Flip cards to reveal answers
- **Auto-Progress**: Automatically moves to next question after answering
- **Score Tracking**: Real-time score, streak, and accuracy monitoring
- **Progress Bar**: Visual indicator of study session progress
- **Local Storage**: Saves flashcards and game statistics locally

### Study Modes
- **Practice Mode**: Answer questions and get immediate feedback
- **Hint System**: Get hints when stuck on difficult questions
- **Skip Function**: Skip difficult questions and review them later
- **Mistakes Review**: Review incorrect answers at the end of each session

### User Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, gradient-based design with smooth animations
- **Category Badges**: Organize flashcards by subject/topic
- **Performance Metrics**: Track accuracy, streaks, and overall performance

## 🚀 How to Use

### Starting a Study Session
1. Open `4 flipcard.html` in your web browser
2. The app will automatically load saved flashcards or use sample cards
3. Click "Check Answer" after typing your response
4. The card will flip to show the correct answer if wrong
5. Automatically advances to the next question

### Creating Flashcards
1. Navigate to `3 create flashcard.html`
2. Enter your question and answer
3. Select a category for organization
4. Save to add to your flashcard deck

### Game Controls
- **Check Answer**: Validates your response and shows feedback
- **Next**: Skip current question (marked as incorrect)
- **Hint**: Get a clue about the current answer
- **Enter Key**: Submit answer using keyboard

## 🎮 Game Mechanics

### Scoring System
- **Correct Answer**: +10 points + streak bonus
- **Streak Bonus**: +2 points per consecutive correct answer
- **Accuracy Tracking**: Real-time percentage calculation
- **Performance Rating**: Final grade based on accuracy

### Card Categories
- 📚 Vocabulary
- 📖 Definitions  
- 🔤 Abbreviations
- 🔄 Antonyms
- 🌍 Translations
- 🧮 Formulas
- 📅 Dates
- ✏️ Custom

### Progress Tracking
- **Current Card**: Shows question number
- **Total Cards**: Displays deck size
- **Score**: Current session score
- **Streak**: Consecutive correct answers
- **Accuracy**: Percentage of correct answers

## 💾 Data Storage

### Local Storage Features
- **Flashcard Persistence**: Cards are saved between sessions
- **Game Statistics**: Last 10 game sessions stored
- **Progress Tracking**: Individual card performance metrics
- **Mistakes Log**: Incorrect answers saved for review

### Data Structure
```javascript
// Flashcard Structure
{
  id: unique_id,
  category: "category_name",
  question: "Your question",
  answer: "The correct answer",
  difficulty: 1-5,
  attempts: number,
  correct: number
}

// Game Statistics
{
  date: "ISO_timestamp",
  accuracy: percentage,
  score: points,
  totalCards: number,
  mistakes: [array_of_mistakes]
}
```

## 🎨 Customization

### Styling
- **Color Scheme**: Purple and green gradient theme
- **Typography**: Segoe UI font family
- **Animations**: Smooth card flips and UI transitions
- **Responsive**: Adapts to mobile screens (768px breakpoint)

### Card Dimensions
- **Desktop**: 350px × 250px
- **Mobile**: 300px × 200px
- **Perspective**: 1000px for 3D flip effect

## ⌨️ Keyboard Shortcuts

- **Enter**: Submit answer
- **Tab**: Navigate between buttons
- **Space**: Not used (reserved for future features)

## 🔄 Game Flow

1. **Load Cards**: Fetch from localStorage or use samples
2. **Shuffle Deck**: Randomize question order
3. **Display Question**: Show current card
4. **User Input**: Collect answer
5. **Validate Response**: Check correctness
6. **Show Feedback**: Display result message
7. **Auto-Advance**: Move to next card after delay
8. **Track Progress**: Update statistics
9. **End Game**: Show final results and performance

## 📱 Browser Compatibility

- **Chrome**: Full support
- **Firefox**: Full support  
- **Safari**: Full support
- **Edge**: Full support
- **Mobile Browsers**: Responsive design supported

## 🛠️ Technical Details

### HTML Structure
- Semantic HTML5 elements
- Accessible form controls
- Responsive grid layouts

### CSS Features
- Flexbox for layouts
- CSS Grid for statistics
- 3D transforms for card flips
- CSS animations and transitions
- Media queries for responsiveness

### JavaScript Functionality
- ES6+ features
- LocalStorage API
- Event handling
- DOM manipulation
- Array methods for data processing

## 🚀 Future Enhancements

### Planned Features
- [ ] Multiple difficulty levels
- [ ] Timer mode
- [ ] Audio pronunciation
- [ ] Image support for cards
- [ ] Cloud sync for multiple devices
- [ ] Study reminders
- [ ] Export/Import functionality
- [ ] Multi-language support

### Potential Improvements
- [ ] Spaced repetition algorithm
- [ ] Performance analytics dashboard
- [ ] Collaborative study modes
- [ ] Gamification elements
- [ ] Integration with educational platforms

## 📝 Usage Tips

### Best Practices
1. **Regular Study**: Use daily for best retention
2. **Review Mistakes**: Focus on cards you get wrong
3. **Use Hints**: Don't be afraid to ask for help
4. **Track Progress**: Monitor your accuracy over time
5. **Create Categories**: Organize cards by subject

### Study Strategies
- **Active Recall**: Try to answer before flipping
- **Spaced Repetition**: Review difficult cards more often
- **Mix Categories**: Study different subjects together
- **Set Goals**: Aim for specific accuracy targets

## 🐛 Troubleshooting

### Common Issues
- **Cards not saving**: Check browser localStorage permissions
- **Animations not working**: Ensure CSS3 support is enabled
- **Mobile layout issues**: Refresh page and check orientation
- **Score not updating**: Clear browser cache and restart

### Performance Tips
- **Limit deck size**: Keep under 100 cards per session
- **Regular cleanup**: Clear old statistics periodically
- **Browser update**: Use latest browser version

## 📄 License

This project is open source and available for educational purposes.

---

**Happy Studying! 🎓**
