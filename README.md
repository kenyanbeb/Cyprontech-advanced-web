<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>NEWS</title>
  <meta name="description" content="A modern news platform featuring the latest headlines and in-depth stories." />
  <link href="https://fonts.googleapis.com/css?family=Inter:400,700&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <div class="main-wrapper">
    <aside class="sidebar">
      <div class="logo-row">
        <span class="logo-icon"><i class="fa fa-newspaper"></i></span>
        <span class="logo-title">NEWS</span>
      </div>
      <nav class="sidebar-nav">
        <a href="#">Home</a>
        <a href="#">World</a>
        <a href="#">Business</a>
        <a href="#">Politics</a>
        <a href="#">About</a>
      </nav>
      <div class="sidebar-categories">
        <h3>Categories</h3>
        <ul>
          <li>Tech</li>
          <li>Business</li>
          <li>Politics</li>
        </ul>
      </div>
      <div class="sidebar-authors">
        <h3>Authors</h3>
        <div class="author">
          <img src="https://randomuser.me/api/portraits/women/50.jpg" alt="Jane Smith" />
          <div>
            <span class="author-name">Jane Smith</span>
            <span class="author-role">Senior Writer</span>
          </div>
        </div>
      </div>
      <div class="sidebar-contact">
        <h3>Contact</h3>
      </div>
    </aside>
    <main class="content">
      <section class="latest-news">
        <h2>Latest News</h2>
        <div class="news-list">
          <div class="news-item">
            <img src="https://images.unsplash.com/photo-1511367461989-f85a21fda167?auto=format&fit=crop&w=400&q=80" alt="Tech Industry Continues to Expand Rapidly" />
            <div class="news-info">
              <h4>Tech Industry Continues to Expand Rapidly</h4>
              <span class="news-date">April 23, 2024</span>
            </div>
          </div>
          <div class="news-item">
            <img src="https://images.unsplash.com/photo-1465101046530-73398c7f28ca?auto=format&fit=crop&w=400&q=80" alt="Market Watch: Stocks Jump as Trading Begins" />
            <div class="news-info">
              <h4>Market Watch: Stocks Jump as Trading Begins</h4>
              <span class="news-date">April 23, 2024</span>
            </div>
          </div>
          <div class="news-item">
            <img src="https://images.unsplash.com/photo-1519125323398-675f0ddb6308?auto=format&fit=crop&w=400&q=80" alt="President Addresses Rising Tensions in Speech" />
            <div class="news-info">
              <h4>President Addresses Rising Tensions in Speech</h4>
              <span class="news-date">April 23, 2024</span>
            </div>
          </div>
          <div class="news-item">
            <img src="https://images.unsplash.com/photo-1503676382389-4809596d5290?auto=format&fit=crop&w=400&q=80" alt="New Study Reveals Trends in Remote Work" />
            <div class="news-info">
              <h4>New Study Reveals Trends in Remote Work</h4>
              <span class="news-date">April 23, 2024</span>
            </div>
          </div>
        </div>
      </section>
      <section class="featured-story">
        <h2>Featured Stories</h2>
        <div class="featured-card">
          <img src="https://images.unsplash.com/photo-1465101178521-c1a9136a06b3?auto=format&fit=crop&w=800&q=80" alt="The Future of Work" class="featured-img" />
          <div class="featured-text">
            <h3>The Future of Work: Changes and Challenges Ahead</h3>
            <p>
              The workplace is undergoing rapid transformation. Shifts in work practices and expectations pose both opportunities and challenges for employees and employers.
            </p>
          </div>
        </div>
      </section>
    </main>
  </div>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" />
</body>
</html>

body {
  margin: 0;
  font-family: 'Inter', Arial, sans-serif;
  background: #15181b;
  color: #fff;
}

.main-wrapper {
  display: flex;
  min-height: 100vh;
}

/* Sidebar */
.sidebar {
  background: #181c20;
  padding: 2rem 1.5rem 1rem 2rem;
  width: 290px;
  display: flex;
  flex-direction: column;
  gap: 2.5rem;
  min-height: 100vh;
  border-right: 1px solid #23262a;
}
.logo-row {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 2rem;
}
.logo-icon {
  font-size: 2rem;
  color: #fff;
}
.logo-title {
  font-size: 1.6rem;
  font-weight: bold;
  letter-spacing: 0.04em;
}
.sidebar-nav {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
.sidebar-nav a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  font-size: 1.1rem;
  opacity: 0.85;
  transition: color 0.2s;
}
.sidebar-nav a:hover {
  color: #e14b33;
}
.sidebar-categories,
.sidebar-authors,
.sidebar-contact {
  margin-top: 1.2rem;
}
.sidebar-categories h3,
.sidebar-authors h3,
.sidebar-contact h3 {
  font-size: 1.1rem;
  margin-bottom: 0.6rem;
  color: #fff;
  opacity: 0.9;
  font-weight: 600;
  letter-spacing: 0.02em;
}
.sidebar-categories ul {
  padding: 0;
  margin: 0;
  list-style: none;
}
.sidebar-categories li {
  margin-bottom: 0.3rem;
  font-size: 1rem;
  color: #d7dae0;
}
.sidebar-authors .author {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-top: 0.3rem;
}
.sidebar-authors img {
  width: 46px;
  height: 46px;
  border-radius: 50%;
  object-fit: cover;
  border: 2px solid #23262a;
}
.author-name {
  display: block;
  font-weight: 600;
  font-size: 1rem;
  color: #fff;
}
.author-role {
  font-size: 0.92rem;
  color: #c8c8c9;
  opacity: 0.8;
}

/* Content area */
.content {
  flex: 1;
  padding: 2.5rem 3rem;
  background: #15181b;
}

.latest-news h2,
.featured-story h2 {
  font-size: 2rem;
  font-weight: 700;
  margin: 0 0 1.2rem 0;
  color: #fff;
}

.news-list {
  display: flex;
  gap: 1.7rem;
  flex-wrap: wrap;
}
.news-item {
  background: #181c20;
  border-radius: 12px;
  width: 210px;
  display: flex;
  flex-direction: column;
  box-shadow: 0 2px 12px 0 rgba(45, 45, 58, 0.10);
  overflow: hidden;
  transition: transform 0.18s, box-shadow 0.18s;
  cursor: pointer;
}
.news-item:hover {
  transform: translateY(-6px) scale(1.032);
  box-shadow: 0 8px 20px 0 rgba(45, 45, 58, 0.14);
}
.news-item img {
  width: 100%;
  height: 120px;
  object-fit: cover;
}
.news-info {
  padding: 1rem 0.9rem 1rem 0.9rem;
  display: flex;
  flex-direction: column;
