# Typing Test Application

## Description
A web-based typing speed test application that measures your typing speed in Words Per Minute (WPM) with real-time feedback on accuracy. The application provides a clean, minimalist interface for testing and improving typing skills.

## What It Does
The typing test application:
- Displays a continuous stream of randomly shuffled words for users to type
- Tracks typing accuracy in real-time with visual feedback (green for correct, red for errors)
- Measures typing speed in Words Per Minute (WPM)
- Provides a 60-second countdown timer
- Calculates final WPM score with error penalties
- Offers the ability to restart the test with newly shuffled words
- Automatically scrolls text horizontally after 20 characters to maintain focus
- Restricts usage to desktop devices only for optimal experience

## Technologies Used
- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, layout, and responsive design
- **Vanilla JavaScript** - Core functionality and DOM manipulation
- **JSON** - Word bank data storage

## Features

### Core Features
- **60-Second Timed Test**: Standard typing test duration with countdown timer
- **Real-Time Feedback**: Immediate visual indication of correct (green) and incorrect (red) characters
- **WPM Calculation**: Accurate words-per-minute calculation with error adjustment
- **Word Shuffling**: Random word order for each test session
- **Horizontal Scrolling**: Smart text scrolling after 20 characters to maintain typing focus
- **Error Penalty System**: WPM score reduced by number of errors made
- **Try Again Functionality**: Easy test restart with new word arrangement

### User Interface Features
- **Clean Design**: Minimalist interface with whitesmoke background
- **Monospace Font**: Consistent character spacing for accurate typing
- **Responsive Layout**: Flexbox-based centered design
- **Hidden Cursor**: Cursor hidden over text area for distraction-free typing
- **Visual Feedback**: Color-coded character feedback system
- **Button Hover Effects**: Interactive button styling with brightness effects

### Technical Features
- **Mobile Detection**: Automatic detection of mobile devices
- **Desktop-Only Experience**: Optimized for desktop use with mobile restriction message
- **Keyboard Event Handling**: Comprehensive keyboard input processing
- **Backspace Support**: Full backspace functionality with character deletion
- **Memory Management**: Efficient text rendering and scroll positioning
- **Error Tracking**: Real-time error counting and WPM adjustment

### Accessibility Features
- **Keyboard Navigation**: Full keyboard-based interaction
- **Large Text**: 1.5rem font size for readability
- **High Contrast**: Clear color differentiation for correct/incorrect feedback
- **Mobile Awareness**: Informative message for mobile users

## File Structure
```
typing-test-main/
├── index.html          # Main HTML structure
├── style.css           # Styling and layout
├── script.js           # Core JavaScript functionality
├── words.json          # Word bank data (currently unused)
├── favicon.png         # Application icon
└── README.md           # This documentation
```

## How to Use
1. Open `index.html` in a web browser on a desktop device
2. The test begins automatically when you start typing
3. Type the displayed words as accurately as possible
4. Green highlighting indicates correct characters, red indicates errors
5. The timer counts down from 60 seconds
6. Your final WPM score is displayed at the end
7. Click "Try Again" to start a new test with shuffled words

## Browser Compatibility
- Modern web browsers with ES6 support
- Chrome, Firefox, Safari, Edge (latest versions)
- Requires JavaScript enabled

## Performance Considerations
- Efficient DOM manipulation with span elements
- Optimized scrolling calculations
- Memory-friendly text rendering
- Real-time error tracking without performance impact

## Future Enhancement Possibilities
- Multiple test durations (30s, 60s, 120s)
- Difficulty levels with different word complexities
- Detailed statistics and progress tracking
- Custom word lists or text passages
- Multiplayer typing competitions
- Export/import of results
- Dark mode theme option
