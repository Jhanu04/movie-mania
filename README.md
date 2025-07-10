# 🎬 Movie Mania – Movie Recommendation Website

## ✨ Overview

**Movie Mania** is an interactive and genre-based movie recommendation website that showcases handpicked films across Sci-Fi, Drama, Animation, and Thriller. Users can explore curated movie cards, watch trailers in modals, and leave short reviews — all in a smooth, responsive interface.

Designed with a strong focus on aesthetics and usability, the site is lightweight and visually engaging, making it ideal for frontend showcases or static deployments.

---

## 🌟 Features

- 🎞️ Browse movies by genre using animated filters
- ⭐ Star rating visuals for quick impressions
- 🎥 Embedded YouTube trailers in modals
- 📝 Inline review submission for each movie card
- 💡 Smooth hover effects and transitions
- 📱 Fully responsive design powered by Bootstrap 5

---

## 🧪 Technologies Used

- **HTML5** for structure  
- **Bootstrap 5** for styling and responsiveness  
- **JavaScript** for interactivity (filtering, modals, reviews)  
- **Nginx** as a lightweight web server  
- **Docker** for containerization and deployment

---

## 🐳 Docker Deployment

This project is packaged with a simple `Dockerfile` using the **Nginx Alpine** image to serve static content.

### 🔧 To build and run:

```bash
# Step 1: Build the Docker image
docker build -t moviemania .

# Step 2: Run the container
docker run -d -p 8080:80 moviemania
