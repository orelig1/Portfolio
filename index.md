---
layout: default
---

# Welcome to My Portfolio

## About Me

Hi my name is Aurélie and I am bilingual (FR/EN) junior game developer. I also have experience in front-end development which has refined my organizational skills and attention to detail. I use my skills in C# and Unity to create immersive, user-friendly and interactive game experiences. Using my problem-solving abilities, I aim to make games accessible by providing intuitive, engaging gameplay. In my free time I enjoy playing games like League of Legends, World of Warcraft and Fae Farm.

## Projects

### Game Development Projects

- **[Unity Game: Objects](https://profe.github.io/GameDevBootcamp-Objects/)**
  - Description: Asteroids-like 2D retro-style game during CircuitStream Game Development Bootcamp using Unity 6.
  - Collaborators: School collegue
  - Skills Used: C#, Unity, Git, GitHub, Attention to detail, Collaboration, Creativity
  - Link: [GitHub Repo](https://github.com/orelig1/GameDevBootcamp-Objects)

- **[Unity Game: Escape room]**
  - Description: Multiple levels where you have to solve the puzzle and get out of the rooms without dying.
  - Skills Used: C#, Unity, Git, GitHub, Creativity, Design patterns, Implementation of levels
  - Link: [GitHub Repo](https://github.com/orelig1/Midterm)

## Certificates
- AEC Programmer/Analyst in Java, C#, ASP.NET, HTML, ORACLE, SQL, C++, PL/SQL, JavaScript, PHP
- IT Essentials Certification – Cisco Network Academy

## Project Gallery

<style>
.carousel-container {
  position: relative;
  max-width: 600px;
  margin: auto;
  overflow: hidden;
}
.carousel-slide {
  display: none;
  width: 100%;
}
.carousel-slide.active {
  display: block;
}
.carousel-buttons {
  text-align: center;
  margin-top: 10px;
}
.carousel-buttons button {
  margin: 0 5px;
  padding: 5px 10px;
}
</style>

<div class="carousel-container">
  <img class="carousel-slide active" src="https://via.placeholder.com/600x300?text=Escape+Room+1" alt="Escape Room">
  <img class="carousel-slide" src="https://via.placeholder.com/600x300?text=Asteroids+Game" alt="Asteroids Game">
  <img class="carousel-slide" src="https://via.placeholder.com/600x300?text=Escape+Room+2" alt="Escape Room 2">
</div>

<div class="carousel-buttons">
  <button onclick="changeSlide(-1)">Previous</button>
  <button onclick="changeSlide(1)">Next</button>
</div>

<script>
let currentSlide = 0;
const slides = document.querySelectorAll('.carousel-slide');

function changeSlide(n) {
  slides[currentSlide].classList.remove('active');
  currentSlide = (currentSlide + n + slides.length) % slides.length;
  slides[currentSlide].classList.add('active');
}
</script>

