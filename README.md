# 📚 Kernel Quiz App

A comprehensive, interactive quiz application for testing knowledge about Linux kernel management, systemd, and boot processes.

## 🎯 Overview

This project contains two automated quizzes covering essential Linux system administration topics:

- **CH01 Quiz**: The Boot Process with Systemd (50 questions)
- **CH02 Quiz**: Kernel Management (50 questions)

Each quiz features:
- ✅ Multiple choice questions (MCQ)
- ✅ True/False questions
- ✅ Instant feedback on answers
- ✅ Beautiful, responsive UI
- ✅ Progress tracking
- ✅ Detailed results summary

## 📋 Quiz Contents

### CH01: The Boot Process with Systemd
**Total: 50 Questions** (30 MCQ + 20 True/False)

Topics covered:
- Introduction to systemd and PID 1
- Unit files and priorities
- Unit states (Loaded, Active, Enabled, Static)
- Services and applications
- Mount units
- Targets and runlevels
- Isolating targets
- Wants and dependencies
- Important systemctl commands

### CH02: Kernel Management
**Total: 50 Questions** (30 MCQ + 20 True/False)

Topics covered:
- Understanding GRUB 2 and boot process
- GRUB configuration files
- GRUB menu navigation
- Booting to specific targets
- Resetting root password
- Linux kernel and versions
- Directory structures (/boot, /proc, /lib/modules)
- Kernel module management
- Important commands (lsmod, modinfo, modprobe, dmesg, uname)
- Kernel performance analysis

## 🚀 How to Use

### Online Access
Simply open the HTML files in your browser:
- **CH01 Quiz**: Open `ch01_quiz.html`
- **CH02 Quiz**: Open `ch02_quiz.html`

### Local Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/banna77/kernel-quiz-app.git
   cd kernel-quiz-app
   ```

2. Open the quiz files in your browser:
   ```bash
   # On Linux/Mac
   open ch01_quiz.html
   # or
   firefox ch01_quiz.html
   
   # On Windows
   start ch01_quiz.html
   ```

3. Or use a simple HTTP server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server)
   npx http-server
   ```
   Then visit: `http://localhost:8000/ch01_quiz.html`

## ✨ Features

### Interactive Quiz Experience
- **Instant Feedback**: See correct/incorrect answers immediately
- **Visual Indicators**: 
  - ✅ Correct answers highlighted in green
  - ❌ Incorrect answers highlighted in red
- **Progress Tracking**: Real-time progress bar and question counter
- **Navigation**: Move between questions freely
- **Question Overview**: View all questions and their status at a glance

### Beautiful Design
- Modern gradient purple theme
- Smooth animations and transitions
- Responsive design for all devices
- Professional typography and spacing
- Accessible color contrasts

### Comprehensive Results
- Final score and percentage
- Detailed breakdown of correct/incorrect/unanswered
- Question-by-question review
- Ability to retake the quiz

## 🎨 Design Features

- **Gradient Background**: Modern purple gradient (667eea to 764ba2)
- **Smooth Animations**: Slide-in and fade-in effects
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile
- **Accessibility**: Clear focus states and keyboard navigation support
- **Color Coding**: 
  - Green for correct answers
  - Red for incorrect answers
  - Blue for interactive elements

## 📊 Quiz Statistics

| Quiz | Total Questions | MCQ | True/False | Topics |
|------|-----------------|-----|-----------|--------|
| CH01 | 50 | 30 | 20 | Systemd & Boot Process |
| CH02 | 50 | 30 | 20 | Kernel Management |

## 🔧 Technical Details

- **Technology**: Pure HTML5, CSS3, and JavaScript (ES6+)
- **No Dependencies**: Completely standalone, no external libraries required
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **File Size**: Each quiz is ~40KB (highly optimized)
- **Performance**: Instant loading and smooth interactions

## 📝 How to Modify

### Adding New Questions
Edit the `quizData` object in the HTML file:

```javascript
{
  "id": 51,
  "type": "mcq",
  "question": "Your question here?",
  "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
  "correct": 0,
  "explanation": "Explanation of the correct answer."
}
```

### Customizing Colors
Modify the CSS variables in the `<style>` section:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Changing Quiz Title
Update the header text in the HTML:
```html
<h1>📚 Your Quiz Title</h1>
```

## 🌐 Deployment Options

### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose the main branch
5. Your quiz will be live at: `https://banna77.github.io/kernel-quiz-app/`

### Other Hosting
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **Any Web Server**: Simply copy the HTML files

## 📱 Mobile Compatibility

The quiz is fully responsive and works great on:
- ✅ Desktop browsers
- ✅ Tablets (iPad, Android)
- ✅ Mobile phones (iOS, Android)
- ✅ All screen sizes

## 🎓 Learning Outcomes

After completing these quizzes, you should understand:
- How systemd manages the boot process
- Different unit types and their purposes
- How to manage services and targets
- Kernel management and module handling
- GRUB configuration and boot options
- System administration best practices

## 🐛 Troubleshooting

### Quiz not loading?
- Ensure JavaScript is enabled in your browser
- Try a different browser
- Check browser console for errors (F12)

### Questions not showing?
- Refresh the page (Ctrl+F5 or Cmd+Shift+R)
- Clear browser cache
- Try incognito/private mode

### Answers not saving?
- This is normal - answers are stored in browser memory
- They will be cleared when you refresh or close the quiz
- Use the "Finish Quiz" button to see results before leaving

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created by **banna77**

## 🤝 Contributing

Feel free to:
- Report issues
- Suggest improvements
- Add more questions
- Improve the design
- Fix bugs

## 📞 Support

For questions or issues, please open an issue on GitHub.

---

**Last Updated**: June 2026

**Status**: ✅ Active and Maintained

Enjoy learning! 🚀
