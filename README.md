# WanderMate

WanderMate is a web application designed for **solo travelers** who want to discover exciting places, meet like-minded explorers, and make the most of their trips. It curates **personalized travel recommendations** based on user preferences, helping adventurers find the best hangout spots, restaurants, and activities in any location.

## Why I Built This

As a solo traveler myself, I often found it challenging to **discover places beyond the typical tourist traps** and connect with fellow travelers in real-time. Existing apps focus on general travel planning, but few cater specifically to the solo travel experience. That’s why I built WanderMate — an app that **suggests the best spots tailored to individual travel styles** and fosters meaningful interactions between travelers.

The goal: Make solo travel feel less lonely and more enriching by providing smart location-based recommendations.

## Live Demo

[Check out WanderMate here!](https://your-deployed-site-link.com) 🔗

📖 [Read the full journey of this project in my blog post!](https://your-blog-article-link.com)



## Author

Mbali Skhosana https\://www\.linkedin.com/in/mbali-skhosana/

---

## Tech Stack

WanderMate is built with:

- **Frontend:** React, Tailwind CSS, Framer Motion (for animations)
- **Backend:** Node.js, Express
- **Database:** MongoDB (storing user preferences and travel locations)
- **APIs:** Google Maps API (for location suggestions)



## Screenshots

### Home Page 
![image](https://github.com/user-attachments/assets/7ee7d2f5-3c87-4e08-956c-b13d4ab0f12e)



### Profile
![image](https://github.com/user-attachments/assets/afaf67d3-180b-448c-a0e6-66d7f1a586e4)




### Interactive Map 

![image](https://github.com/user-attachments/assets/98c74f64-f37a-4d80-86c0-61499e2f3a42)

Clone the repository and install dependencies:

```bash
$ git clone https://github.com/your-username/wandamate.git
$ cd wandamate
$ npm install
$ npm start
```

## Challenges & What I Learned

### 1️⃣ **Personalized Recommendations** 

**Challenge:** How do I make recommendations that actually feel **personal** to solo travelers?
**Solution:** I built a **scoring algorithm** that factors in:

- User-selected interests (e.g., food, nightlife, adventure, relaxation)
- Popularity & ratings of locations
- Weather conditions (suggests indoor places if it’s raining 🌧️)
- Traveler sentiment analysis from reviews

### 2️⃣ **Balancing Simplicity & Functionality** 

**Challenge:** I wanted the app to be powerful but also **intuitive** for users.
**Solution:**

- Focused on **a clean UI** with easy-to-understand categories
- Used **progressive disclosure** (show details only when needed)
- Optimized search performance using **indexed queries** in MongoDB

### 3️⃣ **Handling Real-Time Location Data** 

**Challenge:** Integrating **Google Maps API** efficiently without slowing the app down.
**Solution:**

- Used **debouncing** to optimize search queries
- Implemented **caching** to reduce API calls and speed up results

## Future Improvements

Solo Traveler Meetup Feature: Connect with fellow solo travelers nearby! 

**Offline Mode:** Download recommendations for offline use.

A**I-Based Itineraries:** Auto-generate trip plans based on interests and time constraints. 

 **Dark Mode:** Because, well… everyone loves it. 

## Contributing

Want to help improve WanderMate? Follow these steps:

1. **Fork the repo**
2. **Create a new branch:** `git checkout -b feature-name`
3. **Make changes & commit:** `git commit -m 'Added a cool feature'`
4. **Push to GitHub:** `git push origin feature-name`
5. **Submit a pull request** 

## License

WanderMate is licensed under the **MIT License**. 
---

## My Takeaway From This Project

Building WanderMate was a **challenging yet deeply rewarding experience**. I learned how to:

- Optimize **real-time APIs** for fast performance 
- Use **data-driven decision-making** to improve user experience 



But more than that, I got to **build something I truly care about**—helping solo travelers feel less alone. 

&#x20;If you’re a fellow dev or traveler, I’d love to connect on [LinkedIn][(https://www.linkedin.com/in/mbali-skhosana/)]! Let’s chat about tech, travel, or both. 

