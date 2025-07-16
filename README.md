# Rory's Flag & Domain Quiz

An interactive geography quiz game where players identify countries by their flags or domain extensions on a world map. Test your knowledge of world geography through visual clues!

## 🎮 Game Features

### Two Quiz Modes
- **Flag Quiz**: Identify countries by their national flags
- **Domain Quiz**: Identify countries by their internet domain extensions (e.g., `.de` for Germany)

### Interactive Gameplay
- Click on countries on the world map to make your guess
- 3 attempts per country with visual feedback
- Real-time progress tracking
- Statistics showing performance breakdown

### Visual Feedback System
- 🟦 **Blue**: Available countries to guess
- 🟢 **Green**: Correctly identified countries
- 🔴 **Red**: Incorrect guesses
- ⚫ **Dark Red**: Failed attempts (ran out of tries)
- 🔘 **Gray**: Countries not included in the quiz

### Smart Features
- **Last Missed Indicator**: Shows the flag of the most recently missed country
- **Hover Tooltips**: Country information when not in quiz mode
- **Progress Display**: Current question number and remaining tries
- **Final Statistics**: Breakdown of first-try, second-try, third-try successes and failures

## 🗺️ Countries Included

The quiz includes **87 countries** that have Google Street View coverage, making them relevant for geography games like GeoGuessr. Countries without Street View coverage are displayed on the map but excluded from the quiz.

### Quiz Countries Include:
- All major European countries
- North and South American countries with Street View
- Asian countries like Japan, South Korea, Thailand, India
- African countries including South Africa, Ghana, Kenya
- Oceania: Australia, New Zealand

## 🚀 Getting Started

### Prerequisites
- A modern web browser with JavaScript enabled
- Internet connection (for external libraries and flag images)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/flag-domain-quiz.git
```

2. Navigate to the project directory:
```bash
cd flag-domain-quiz
```

3. Open `index.html` in your web browser

### File Structure
```
├── index.html          # Main game file with HTML structure and JavaScript logic
├── countries.js        # Country data with names, domains, and quiz inclusion status
├── style.css          # Custom CSS styles
└── README.md          # This file
```

## 🎯 How to Play

1. **Choose a Mode**: Click either "Guess Flags" or "Guess Domains"
2. **Study the Clue**: Look at the flag or domain extension displayed
3. **Make Your Guess**: Click on the country you think matches on the world map
4. **Track Progress**: Monitor your tries (❤️) and progress through the quiz
5. **Review Results**: See your final statistics when you complete all countries

### Scoring System
- **First Try**: Perfect identification
- **Second Try**: Good identification (1 mistake)
- **Third Try**: Successful identification (2 mistakes)
- **Failed**: Used all 3 attempts without success

## 🛠️ Technologies Used

- **HTML5** & **CSS3** for structure and styling
- **JavaScript** (ES6+) for game logic
- **Tailwind CSS** for responsive design
- **amCharts 5** for interactive world map
- **Flag CDN** for country flag images
- **Google Fonts** (Inter) for typography

## 🎨 Features & Functionality

### Interactive Map
- Built with amCharts 5 for smooth interactions
- Responsive design that works on desktop and mobile
- Zoom and pan capabilities
- Country highlighting and tooltips

### Smart Data Management
- Efficient country data structure
- Quiz randomization for replay value
- State management for game progress
- Statistics tracking throughout the session

### User Experience
- Clean, modern interface
- Visual feedback for all interactions
- Responsive design for all screen sizes
- Accessibility considerations

## 🔧 Customization

### Adding Countries
To add new countries to the quiz, edit `countries.js`:

```javascript
"XX": { name: "Country Name", domain: ".xx", inQuiz: true },
```

### Modifying Colors
Update the `COLORS` object in `index.html`:

```javascript
const COLORS = {
  default: am5.color(0xdbeafe),    // Default country color
  correct: am5.color(0x86efac),    // Correct answer
  incorrect: am5.color(0xfca5a5),  // Wrong answer
  // ... more colors
};
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [amCharts](https://www.amcharts.com/) for the excellent mapping library
- [Flagpedia](https://flagcdn.com/) for providing flag images
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- GeoGuessr community for inspiration on country selection

## 📊 Statistics

- **87 quiz countries** included
- **2 game modes** (flags and domains)
- **3 attempts** per country
- **Comprehensive statistics** tracking

---

**Enjoy testing your geography knowledge!** 🌍