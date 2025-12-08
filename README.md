# Phred Demo

Interactive demo of Phred - Phishing Simulation Platform

## 🎯 Overview

This is a live, interactive demo showcasing Phred's core features with mocked interactions. The demo simulates:

- **Campaign Management**: Real-time campaign metrics
- **Email Tracking**: Open, click, and submission tracking
- **Live Activity Feed**: Real-time event logging
- **Metrics Visualization**: Interactive charts showing campaign performance
- **Email Preview**: Sample phishing email template

## 🚀 Live Demo

Visit the demo: [GitHub Pages URL will be here after deployment]

## ✨ Features Demonstrated

- ✅ Real-time campaign metrics (emails sent, opened, clicked, submitted)
- ✅ Interactive email simulation
- ✅ Live activity feed with timestamps
- ✅ Real-time metrics chart
- ✅ Button-based interaction simulation
- ✅ Auto-simulation mode for continuous updates
- ✅ Responsive design for mobile and desktop

## 🛠️ Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/ChickenPwny/LivingArchive-Phred-demo.git
   cd LivingArchive-Phred-demo
   ```

2. Open `index.html` in a web browser:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Or simply open index.html in your browser
   ```

3. No server required - works as static files!

## 📦 Deployment

This demo is designed for GitHub Pages:

1. Push this repository to GitHub
2. Go to Repository Settings → Pages
3. Select source branch (usually `main` or `gh-pages`)
4. Your demo will be live at: `https://[username].github.io/LivingArchive-Phred-demo/`

## 🎮 How to Use

### Manual Interaction
- Click **"Open Email"** to simulate email opens
- Click **"Click Link"** to simulate link clicks (requires emails to be opened first)
- Click **"Submit Form"** to simulate form submissions (requires links to be clicked first)
- Click **"Reset Demo"** to start over

### Auto-Simulation
The demo automatically simulates interactions every 3 seconds to show real-time updates.

## 📊 Metrics Explained

- **Emails Sent**: Total number of emails sent in the campaign
- **Emails Opened**: Number of recipients who opened the email
- **Links Clicked**: Number of recipients who clicked the phishing link
- **Forms Submitted**: Number of recipients who submitted credentials

Percentages are calculated as: (metric / emails sent) × 100

## 🎨 Customization

All styling is in `assets/css/demo.css` and behavior is in `assets/js/demo.js`. You can easily customize:

- Colors and themes
- Initial campaign values
- Auto-simulation frequency
- Chart appearance
- Activity feed messages

## 🔗 Related Projects

- **Phred Main**: [PhishingRetrievalEmailDetection](https://github.com/ChickenPwny/PhishingRetrievalEmailDetection)
- **Phred Pro**: Commercial version with advanced features

## 📄 License

This demo is part of the Phred project. See the main repository for license information.

## 🤝 Contributing

This is a demo repository. For contributions to the main Phred project, please visit the main repository.

---

**Phred** - Making security awareness training effective and measurable.

