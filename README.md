### 🌐 Connect with Me
<p align="center" class="social-links">
  <a href="https://www.linkedin.com/in/madhav-debbata-938b54169/" class="badge linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  
  <a href="mailto:madhavdebbata2004@gmail.com" class="badge email">
    <img src="https://img.shields.io/badge/Email-D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>

  <a href="https://madhavdebbata.github.io" class="badge portfolio">
    <img src="https://img.shields.io/badge/Portfolio-000000.svg?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/>
  </a>
</p>

<style>
/* === Glow Animation for Badges === */
.social-links {
  display: flex;
  justify-content: center;
  gap: 15px;
  flex-wrap: wrap;
}

.badge img {
  transition: transform 0.4s ease, box-shadow 0.4s ease, filter 0.4s ease;
  border-radius: 10px;
}

/* Hover effects per badge type */
.badge.linkedin img:hover {
  transform: scale(1.15) rotate(-3deg);
  box-shadow: 0 0 20px rgba(0, 119, 181, 0.7);
  filter: brightness(1.2);
}

.badge.email img:hover {
  transform: scale(1.15) rotate(3deg);
  box-shadow: 0 0 25px rgba(209, 72, 54, 0.8);
  filter: brightness(1.3);
}

.badge.portfolio img:hover {
  transform: scale(1.15) rotate(-2deg);
  box-shadow: 0 0 20px rgba(255, 255, 255, 0.6);
  filter: brightness(1.4);
}

/* Floating up-down animation */
@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-6px); }
}

.badge img {
  animation: float 3s ease-in-out infinite;
}
</style>
