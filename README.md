<div align="center">
<img width="1200" height="475" alt="GHBanner" src="plansphere-ai\publicbanner.png"/>
</div>

# PlanSphere AI 🌍✈️ 

### The Future of Travel Planning.

PlanSphere AI is an innovative, full-stack travel assistant application powered by **Google's Gemini 2.5 Flash**. It goes beyond simple scheduling by acting as a personalized travel agent, financial planner, and social media manager all in one.

From generating day-by-day itineraries based on your specific "vibe" to analyzing your travel photos for viral Instagram captions, PlanSphere handles the logistics so you can focus on the experience.

---

## ✨ Key Features

### 1. 🗺️ AI-Powered Itinerary Generation
* **Hyper-Personalized**: Generates detailed, day-by-day plans based on destination, budget, travel party, and specific interests like "Anime" or "Hidden Gems".
* **Time-Boxed Schedules**: Provides logical time slots for activities (e.g., 09:00 AM - 11:00 AM) accounting for travel time.
* **Context Aware**: Suggests activities that actually fit the user's selected budget and travel style.

### 2. 📸 Social Studio (Powered by Gemini Vision)
* **Image Analysis**: Upload photos directly from your trip. The AI analyzes the image to detect the location and context.
* **Viral Content Generation**: Automatically generates platform-specific content (Instagram captions, Twitter threads, TikTok concepts) matching your personal "voice".
* **Hashtag Strategy**: Generates trending and relevant hashtags based on image analysis.

### 3. 💸 Smart Expense Dashboard
* **Budget Tracking**: Set a trip budget and track spending in real-time with visual progress bars.
* **AI Auto-Categorization**: Simply type "Sushi at Ginza 5000", and the AI automatically tags the category and subcategory.
* **Visual Analytics**: Interactive pie and bar charts to analyze spending habits using Recharts.
* **Currency Converter**: Real-time AI-powered currency conversion for major global currencies.

### 4. 🤖 AI Travel Assistant
* **Real-Time Chat**: A persistent chatbot available throughout the app to answer questions or adjust plans.
* **Google Search Grounding**: Uses Google Search grounding to provide up-to-date information on events, news, and opening hours.
* **Context Aware**: The bot knows your current itinerary and budget to provide highly relevant answers.

### 5. 🌏 Community & Guides
* **Local Guide Finder**: AI generates profiles of potential local guides matched to your specific destination.
* **Community Hub**: A simulated social feed showing tips and posts from other travelers in your destination.

---

## 🛠️ Tech Stack

* **Frontend Framework**: React 19
* **Language**: TypeScript
* **Styling**: Tailwind CSS (with glassmorphism effects)
* **AI Model**: Google Gemini API (`gemini-2.5-flash`) via `@google/genai` SDK
* **Icons**: Lucide React
* **Charts**: Recharts
* **Build Tool**: Vite

---

## 🚀 Getting Started

### Prerequisites
* **Node.js**: v18 or higher.
* **Google Gemini API Key**: Obtain one from [Google AI Studio](https://aistudio.google.com/).

### Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/yourusername/plansphere-ai.git](https://github.com/yourusername/plansphere-ai.git)
   cd plansphere-ai

```

2. **Install dependencies**:
```bash
npm install

```


3. **Configure Environment Variables**:
Create a `.env.local` file in the root directory and add your API key:
```env
GEMINI_API_KEY=your_actual_api_key_here

```


4. **Run the application**:
```bash
npm run dev

```



---

## 📖 Usage Guide

1. **Planner**: Enter a destination, dates, budget, and interests. Click **Generate Itinerary**.
2. **Itinerary View**: Explore your schedule. Use the **Ask Assistant** chat to tweak the plan.
3. **Expenses**: Enter a cost description (e.g., "Taxi to hotel 4000") and click the **Magic Wand** icon for AI categorization.
4. **Social Studio**: Upload a trip photo, click **Analyze Photo**, select a **Tone of Voice**, and generate a full campaign.

---

## 🎨 Design System

* **Dark Mode Support**: Seamless toggle between Light and Dark themes.
* **Glassmorphism**: Modern UI with blurred backgrounds and thin borders.
* **Responsive**: Optimized for everything from mobile phones to large desktops.

---

## 📄 License

This project is licensed under the MIT License.

Made with ❤️ and 🤖 by Gandharva
