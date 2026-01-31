
</header>
<article>

<h1>Digital Marketing: The Key to Growing Your Business Online</h1>

<p>
Digital marketing is the backbone of modern business growth. In today’s digital world, businesses use online platforms such as search engines, social media, websites, and email to promote their products and services. A strong digital marketing strategy helps brands reach the right audience and stay competitive in the market.
</p>

<h2>Why Digital Marketing Is Important</h2>

<p>
Digital marketing allows businesses to connect with potential customers anytime and anywhere. Unlike traditional marketing, online marketing is cost-effective and measurable. You can track website traffic, clicks, conversions, and customer behavior to improve your strategy.
</p>

<h2>Main Types of Digital Marketing</h2>

<p>
Search Engine Optimization (SEO) helps websites rank higher on search engines like Google. Social media marketing builds brand awareness and engagement. Content marketing, such as blogs and videos, educates users and builds trust. Email marketing keeps customers informed about offers and updates.
</p>

<h2>How Digital Marketing Helps Your Business Grow</h2>

<p>
With the right digital marketing plan, businesses can increase website traffic, generate leads, and boost sales. Consistent content creation and data-driven decisions help improve results over time. Whether you are a beginner or an experienced marketer, focusing on quality and consistency leads to long-term success.
</p>

<h2>Conclusion</h2>

<p>
Digital marketing is a powerful tool for building a strong online presence. By using the right strategies and staying updated with trends, any business can grow faster and reach more customers in today’s competitive digital landscape.
</p>

</article>

<head>
    <button id="darkToggle">🌙 Dark Mode</button>

    <link rel="stylesheet" href="style.css">
</head>
<script>
const toggle = document.getElementById("darkToggle");

toggle.onclick = function(){
  document.body.classList.toggle("dark");
}
</script>

<div class="blog-grid">

  <div class="blog-card">
    <h2>Digital Marketing Basics</h2>
    <p>Learn how digital marketing helps businesses grow online.</p>
    <button>Read More</button>
  </div>

  <div class="blog-card">
    <h2>SEO Tips for Beginners</h2>
    <p>Simple SEO strategies to rank higher on Google.</p>
    <button>Read More</button>
  </div>

  <div class="blog-card">
    <h2>Social Media Growth</h2>
    <p>Grow your audience using smart social media techniques.</p>
    <button>Read More</button>
  </div>

</div>
<!-- Header -->
<header class="site-header">
  <div class="logo">
    <a href="index.html">HamaraMarket</a>
  </div>
</header>

<script>
const toggle = document.getElementById('darkModeToggle');

toggle.addEventListener('click', () => {
  document.body.classList.toggle('dark-mode');
  // Change icon based on mode
  if(document.body.classList.contains('dark-mode')) {
    toggle.textContent = '☀️'; // Sun icon in dark mode
  } else {
    toggle.textContent = '🌙'; // Moon icon in light mode
  }
});
</script>


<section class="follow-us">
  <h2>Follow us on Social Media</h2>
  <p>Stay updated with my latest posts and tips:</p>
  <div class="social-links">
    </a>
    <a href="https://twitter.com/yourprofile" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="Twitter" />
    </a>
    <a href="https://www.instagram.com/sk_kingeditzkali200?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" />
    </a>
    <a href="https://www.linkedin.com/in/santanu-konwar-8b17143a8" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn" />
    </a>
  </div>
</section>
 <body>
<style>
body{
  animation: fadePage 1s ease-in;
}

@keyframes fadePage{
  from{opacity:0;}
  to{opacity:1;}
}

/* Title Animation */
h1{
  animation: slideDown 1s ease;
}

@keyframes slideDown{
  from{
    opacity:0;
    transform:translateY(-30px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* Section Heading Animation */
h2{
  animation: slideUp 1s ease;
}

@keyframes slideUp{
  from{
    opacity:0;
    transform:translateY(30px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* Paragraph Fade */
p{
  animation: fadeText 1.2s ease;
}

@keyframes fadeText{
  from{opacity:0;}
  to{opacity:1;}
}

/* Hover Effect */
article:hover{
  transform:scale(1.01);
  transition:0.3s;
}

/* Button Animation (If You Add Buttons Later) */
button{
  transition:0.3s;
}

button:hover{
  transform:translateY(-3px);
}

/* Blog Grid */
.blog-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(280px,1fr));
  gap:25px;
  margin-top:40px;
}

/* Blog Card */
.blog-card{
  background:white;
  padding:25px;
  border-radius:12px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
  transition:0.3s;
}/* Header */
.site-header {
  text-align: center;
  padding: 20px 0;
  background-color: #202124;
  color: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
}

.site-header .logo a {
  font-size: 40px;
  font-weight: 900;
  color: #fff;
  text-decoration: none;
}

/* Dark Mode Toggle Button */
#darkModeToggle {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #3186FF;
  color: white;
  border: none;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  font-size: 24px;
  cursor: pointer;
  z-index: 1000;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  transition: background-color 0.3s, transform 0.2s;
}

#darkModeToggle:hover {
  background-color: #202124;
  transform: scale(1.1);
}

/* Blog Content */
.blog-content {
  padding: 20px;
  max-width: 900px;
  margin: 0 auto;
  background-color: #fff;
  color: #202124;
  transition: background-color 0.3s, color 0.3s;
}

/* Dark Mode Styles */
body.dark-mode {
  background-color: #121212;
  color: #f5f5f5;
}

body.dark-mode .blog-content {
  background-color: #1e1e1e;
  color: #f5f5f5;
}

/* Page Fade In */
body{
  animation: fadePage 1s ease-in;
}

@keyframes fadePage{
  from{opacity:0;}
  to{opacity:1;}
}

/* Title Animation */
h1{
  animation: slideDown 1s ease;
}

@keyframes slideDown{
  from{
    opacity:0;
    transform:translateY(-30px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* Section Heading Animation */
h2{
  animation: slideUp 1s ease;
}

@keyframes slideUp{
  from{
    opacity:0;
    transform:translateY(30px);
  }
  to{
    opacity:1;
    transform:translateY(0);
  }
}

/* Paragraph Fade */
p{
  animation: fadeText 1.2s ease;
}

@keyframes fadeText{
  from{opacity:0;}
  to{opacity:1;}
}

/* Hover Effect */
article:hover{
  transform:scale(1.01);
  transition:0.3s;
}

/* Button Animation (If You Add Buttons Later) */
button{
  transition:0.3s;
}

button:hover{
  transform:translateY(-3px);
}

/* Blog Grid */
.blog-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(280px,1fr));
  gap:25px;
  margin-top:40px;
}

/* Blog Card */
.blog-card{
  background:white;
  padding:25px;
  border-radius:12px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
  transition:0.3s;
}

.blog-card:hover{
  transform:translateY(-8px);
  box-shadow:0 10px 25px rgba(0,0,0,0.15);
}

.blog-card h2{
  color:#0a2540;
}

.blog-card p{
  margin:15px 0;
}

/* Dark Mode Support */
.dark .blog-card{
  background:#141a2a;
}

.dark .blog-card h2{
  color:#93c5fd;
}

.follow-us {
  text-align: center;
  margin-top: 50px;
  padding: 20px;
  border-top: 1px solid #ddd;
}

.follow-us h2 {
  font-size: 24px;
  margin-bottom: 10px;
}

.follow-us p {
  margin-bottom: 20px;
  color: #555;
}

.social-links a {
  display: inline-block;
  margin: 0 10px;
  transition: transform 0.3s;
}

.social-links a img {
  width: 40px;
  height: 40px;
}

.social-links a:hover {
  transform: scale(1.2);
}
/* Header */
.site-header {
  text-align: center;
  padding: 20px 0;
  background-color: #202124;
  color: #fff;
  position: sticky;
  top: 0;
  z-index: 100;
}

.site-header .logo a {
  font-size: 40px;
  font-weight: 900;
  color: #fff;
  text-decoration: none;
}

/* Dark Mode Toggle Button */
#darkModeToggle {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background-color: #3186FF;
  color: white;
  border: none;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  font-size: 24px;
  cursor: pointer;
  z-index: 1000;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  transition: background-color 0.3s, transform 0.2s;
}

#darkModeToggle:hover {
  background-color: #202124;
  transform: scale(1.1);
}

/* Blog Content */
.blog-content {
  padding: 20px;
  max-width: 900px;
  margin: 0 auto;
  background-color: #fff;
  color: #202124;
  transition: background-color 0.3s, color 0.3s;
}

/* Dark Mode Styles */
body.dark-mode {
  background-color: #121212;
  color: #f5f5f5;
}

body.dark-mode .blog-content {
  background-color: #1e1e1e;
  color: #f5f5f5;
}

/* Dark Mode Button */
#darkToggle{
  position:fixed;
  top:20px;
  right:20px;
  padding:8px 15px;
  background:#111;
  color:white;
  border:none;
  border-radius:5px;
  cursor:pointer;
}

/* Dark Theme */
.dark{
  background:#0b0f19;
  color:#e5e7eb;
}

.dark article{
  background:#141a2a;
  box-shadow:none;
}

.dark h1{
  color:#93c5fd;
}

.dark h2{
  color:#60a5fa;
}

.dark p{
  color:#d1d5db;
}
</style>
