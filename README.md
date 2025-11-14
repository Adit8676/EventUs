# EventUs - Your Feed. Your Future.

**Discover personalized events powered by AI. Never miss workshops, hackathons, or networking opportunities that match your interests and career goals.**

## 🚀 Features

- **AI-Powered Recommendations**: Smart event suggestions based on your preferences and interests
- **Personalized Feed**: Curated events tailored to your skills and career goals
- **Organization Discovery**: Find and follow tech organizations like IEEE, Google Developer Groups, and coding clubs
- **Event Management**: Host workshops, hackathons, seminars, and networking events
- **Smart Matching**: Advanced algorithm matches events with your profile using similarity scoring
- **Dual Interface**: Separate portals for users and organizations

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **AI/ML**: Google Gemini AI, Natural Language Processing
- **Frontend**: EJS templating, CSS3, JavaScript
- **Authentication**: JWT tokens, bcrypt encryption
- **File Upload**: Multer for image handling

## 📱 Screenshots

### Landing Page
![Landing Page](screenshots/landing.png)
*AI-powered event discovery with personalized recommendations*

### Event Discovery
![Event Discovery](screenshots/events.png)
*Browse hackathons, workshops, and networking opportunities*

### Organization Explorer
![Organizations](screenshots/organizations.png)
*Discover and follow tech organizations*

### Preference Settings
![Preferences](screenshots/preferences.png)
*Set your interests for personalized recommendations*

### Event Creation
![Event Creation](screenshots/create-event.png)
*Easy event hosting for organizations*

## 🎯 Key Features

### For Users
- **Smart Feed**: AI curates events based on your tech stack and interests
- **Skill Matching**: Events matched to your programming languages and domains
- **Bookmark System**: Save interesting events for later
- **Organization Following**: Stay updated with your favorite tech communities

### For Organizations
- **Event Hosting**: Create hackathons, workshops, seminars, and networking events
- **Audience Targeting**: Reach users with relevant interests
- **Analytics**: Track event engagement and participation

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Google Gemini API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/Adit8676/EventUs.git
cd EventUs
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
# Create .env file
GEMINI_API_KEY=your_gemini_api_key
MONGO_URI=your_mongodb_connection_string
```

4. Start the application
```bash
npm start
```

5. Open your browser and navigate to `http://localhost:3000`

## 🤖 AI Recommendation System

EventUs uses advanced machine learning algorithms to provide personalized event recommendations:

- **Natural Language Processing**: Analyzes event descriptions and user preferences
- **Similarity Scoring**: Calculates match scores between users and events
- **Google Gemini Integration**: Enhances recommendation accuracy with AI insights
- **Preference Learning**: Continuously improves suggestions based on user interactions

## 📁 Project Structure

```
EventUs/
├── models/          # Database schemas
├── views/           # EJS templates
├── public/          # Static assets
├── utils/           # AI and recommendation utilities
├── uploads/         # User uploaded files
├── scripts/         # Data processing scripts
└── app.js          # Main application file
```

## 🎨 Event Types Supported

- **Hackathons**: Competitive programming events
- **Workshops**: Skill-building sessions
- **Seminars**: Knowledge sharing talks
- **Networking**: Professional meetups
- **Conferences**: Large-scale tech events

## 🏆 Hackathon Project

This project was developed during a hackathon, focusing on solving the problem of event discovery in the tech community. The AI-powered recommendation system helps students and professionals find relevant opportunities without missing deadlines.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License.

## 👥 Team

Built with ❤️ during a hackathon by passionate developers who believe in the power of AI to connect people with opportunities.

---

**EventUs** - Transforming how you discover and engage with tech events through the power of artificial intelligence.