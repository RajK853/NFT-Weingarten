# NFT Weingarten - Interactive Football Training & Nutrition Plan

This project provides an interactive single-page application (SPA) designed to offer a comprehensive football training and nutrition plan for university student-athletes, specifically for the NFT Weingarten team. It aims to make dense information accessible and engaging through a user-friendly interface.

## Objective

To provide a clear, organized, and interactive roadmap for beginner-level university footballers to improve their physical fitness and build fundamental football skills, emphasizing the synergy between proper nutrition and effective training.

## Key Features & Components

### 1. Core Technologies

*   **Frontend**: HTML5, CSS3 (with Tailwind CSS for utility-first styling), JavaScript.
*   **Charting**: Chart.js for data visualization (e.g., macronutrient ratios).
*   **AI Integration**: Utilizes the Gemini API for personalized meal ideas and custom drill suggestions.

### 2. Application Structure (Tab-Based SPA)

*   **Home**: An overview of the plan, welcoming users and highlighting the importance of integrated training and nutrition.
*   **Nutrition Plan**: 
    *   **Macronutrient Goals**: Visual representation of daily macronutrient targets.
    *   **Food Guidance**: Lists of recommended and to-be-limited foods.
    *   **Game Day Fueling Timeline**: A chronological guide for pre-game, during-game, and post-game nutrition.
    *   **AI-Powered Meal Ideas**: Users can generate personalized meal suggestions based on meal type and dietary focus.
*   **Training Plan**: 
    *   **Filterable Drill Library**: A collection of football drills categorized by skill (stamina, strength, passing, dribbling, etc.), each with descriptions and linked YouTube videos.
    *   **AI-Powered Custom Drill Suggestion**: Users can request tailored drill ideas based on specific skill focus and context.
    *   **Weekly Schedule**: A sample weekly training schedule to guide athletes.
*   **Gameplay Tips**: 
    *   **Role-Specific Advice**: Detailed strategic tips for different positions (Striker, Midfielder, Defender, Goalkeeper).
    *   **Video Resources**: Curated YouTube video links to further explain and demonstrate gameplay strategies.

### 3. User Experience & Design

*   **Interactive & Engaging**: Designed to be more user-friendly than a linear document, allowing quick access to relevant information.
*   **Responsive Design**: Adapts to various screen sizes for optimal viewing on different devices.
*   **Dark/Bright Mode Toggle**: Allows users to switch between themes for improved accessibility and preference.
*   **Subtle Visuals**: Includes a background player slideshow for thematic appeal without distracting from content.

## Requirements

*   A web browser to access the HTML file.
*   Internet connectivity for loading external libraries (Tailwind CSS, Chart.js, Google Fonts) and interacting with the Gemini API.
*   (For AI features) An API key for the Gemini API, which is expected to be provided at runtime by the hosting environment (e.g., Google Cloud Canvas).

This project is intended to be hosted on platforms like GitHub Pages to publicly share the interactive training and nutrition plan.