<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Living The Simple Life - Project README</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Lora:wght@400;700&family=Ubuntu:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Ubuntu', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem;
    }

    header {
      background-color: #143774;
      color: white;
      padding: 2rem 0;
      margin-bottom: 2rem;
    }

    header .container {
      padding: 0 2rem;
    }

    h1 {
      font-family: 'Lora', serif;
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    h2 {
      font-family: 'Lora', serif;
      color: #143774;
      margin: 2rem 0 1rem;
      padding-bottom: 0.5rem;
      border-bottom: 3px solid #1792D2;
    }

    h3 {
      color: #1792D2;
      margin: 1.5rem 0 1rem;
      font-size: 1.3rem;
    }

    .badge {
      display: inline-block;
      background-color: #1792D2;
      color: white;
      padding: 0.25rem 0.75rem;
      border-radius: 20px;
      font-size: 0.8rem;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .demo-link {
      display: inline-block;
      background-color: #143774;
      color: white;
      text-decoration: none;
      padding: 0.75rem 1.5rem;
      border-radius: 30px;
      font-weight: bold;
      margin: 1rem 0;
      transition: background-color 0.3s;
    }

    .demo-link:hover {
      background-color: #1792D2;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin: 1.5rem 0;
    }

    .card {
      background: white;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      border-top: 4px solid #1792D2;
    }

    .card h4 {
      color: #143774;
      margin-bottom: 0.5rem;
      font-size: 1.2rem;
    }

    .tech-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      margin: 1rem 0;
      list-style: none;
    }

    .tech-list li {
      background-color: #e9ecef;
      padding: 0.4rem 1rem;
      border-radius: 25px;
      font-size: 0.9rem;
      font-weight: bold;
      color: #143774;
    }

    .breakpoint {
      background-color: #f0f4f8;
      padding: 1rem;
      border-radius: 8px;
      margin: 1rem 0;
      border-left: 4px solid #1792D2;
    }

    .color-palette {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      margin: 1.5rem 0;
    }

    .color {
      width: 120px;
      height: 80px;
      border-radius: 8px;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      padding: 0.5rem;
      color: white;
      font-size: 0.8rem;
      font-weight: bold;
      text-shadow: 0 1px 2px rgba(0,0,0,0.3);
    }

    .color span {
      background: rgba(0,0,0,0.3);
      padding: 0.2rem;
      border-radius: 4px;
    }

    hr {
      border: 0;
      height: 1px;
      background: linear-gradient(to right, transparent, #ddd, transparent);
      margin: 2rem 0;
    }

    .footer-note {
      text-align: center;
      margin-top: 3rem;
      padding-top: 2rem;
      color: #666;
      font-size: 0.9rem;
      border-top: 1px solid #ddd;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }
      
      .container {
        padding: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <span class="badge">Responsive Web Design</span>
      <h1>🌿 Living The Simple Life</h1>
      <p>A responsive blog website exploring minimalism through CSS</p>
    </div>
  </header>

  <main class="container">
    <!-- Overview Section -->
    <section>
      <h2>📖 Overview</h2>
      <p><strong>Living The Simple Life</strong> is a responsive blog website project I built while learning responsive web design with CSS. The site explores minimalism in life through blog posts about simplifying cooking, work, decorations, and finding simplicity in everyday living.</p>
      
      <div class="grid">
        <div class="card">
          <h4>📱 Responsive Design</h4>
          <p>Mobile-first approach with fluid layouts that adapt to any screen size</p>
        </div>
        <div class="card">
          <h4>🧩 Flexbox Layouts</h4>
          <p>Building flexible navigation and article layouts with CSS Flexbox</p>
        </div>
        <div class="card">
          <h4>🎨 Design System</h4>
          <p>Consistent colors, typography, and components across multiple pages</p>
        </div>
        <div class="card">
          <h4>📄 Semantic HTML</h4>
          <p>Clean, accessible markup with proper document structure</p>
        </div>
      </div>

      <a href="https://aylivingthesimplelife.netlify.app/" class="demo-link" target="_blank">🚀 View Live Demo</a>
    </section>

    <!-- What I Learned -->
    <section>
      <h2>🎯 What I Learned</h2>
      
      <h3>1. CSS Flexbox</h3>
      <ul>
        <li>Creating flexible layouts that adapt to different screen sizes</li>
        <li>Building navigation bars with proper spacing</li>
        <li>Aligning content vertically and horizontally</li>
      </ul>

      <h3>2. Responsive Design</h3>
      <ul>
        <li>Using media queries for different breakpoints (768px, 480px)</li>
        <li>Mobile-first approach to styling</li>
        <li>Making images scale properly with <code>object-fit</code></li>
      </ul>

      <h3>3. Design System</h3>
      <ul>
        <li>Consistent color scheme throughout the site</li>
        <li>Typography pairing (Lora for headings, Ubuntu for body text)</li>
        <li>Reusable component patterns</li>
      </ul>

      <h3>4. Multiple Page Consistency</h3>
      <ul>
        <li>Shared CSS file across all pages</li>
        <li>Page-specific overrides without duplicating code</li>
        <li>Active navigation states with <code>aria-current</code></li>
      </ul>
    </section>

    <!-- Color Palette -->
    <section>
      <h2>🎨 Color Palette</h2>
      <div class="color-palette">
        <div class="color" style="background-color: #143774;">
          <span>#143774</span>
          <span>Headings, Footer</span>
        </div>
        <div class="color" style="background-color: #1792D2;">
          <span>#1792D2</span>
          <span>Links, Accents</span>
        </div>
        <div class="color" style="background-color: #707070;">
          <span>#707070</span>
          <span>Body Text</span>
        </div>
        <div class="color" style="background-color: #F8F8F8; color: #333; text-shadow: none;">
          <span style="background: rgba(0,0,0,0.1); color: #333;">#F8F8F8</span>
          <span style="background: rgba(0,0,0,0.1); color: #333;">Header BG</span>
        </div>
        <div class="color" style="background-color: #EBEBEB; color: #333; text-shadow: none;">
          <span style="background: rgba(0,0,0,0.1); color: #333;">#EBEBEB</span>
          <span style="background: rgba(0,0,0,0.1); color: #333;">Card Borders</span>
        </div>
      </div>
    </section>

    <!-- Technologies -->
    <section>
      <h2>🛠️ Technologies Used</h2>
      <ul class="tech-list">
        <li>HTML5</li>
        <li>CSS3 (Flexbox, Media Queries)</li>
        <li>Google Fonts (Lora, Ubuntu)</li>
      </ul>
    </section>

    <!-- Responsive Features -->
    <section>
      <h2>📱 Responsive Features</h2>
      <p>The site is fully responsive with two breakpoints:</p>
      
      <div class="breakpoint">
        <strong>💻 Desktop (>768px):</strong> Multi-column layout with sidebar
      </div>
      <div class="breakpoint">
        <strong>📟 Tablet (≤768px):</strong> Stacked layout with adjusted spacing
      </div>
      <div class="breakpoint">
        <strong>📱 Mobile (≤480px):</strong> Single column with optimized typography
      </div>
    </section>

    <!-- Key Takeaways -->
    <section>
      <h2>💡 Key Takeaways</h2>
      <p>This project taught me that responsive design isn't just about making things fit on smaller screens—it's about rethinking the layout to provide the best user experience on any device. I learned to:</p>
      
      <ul style="margin-top: 1rem;">
        <li>Start with mobile layout first, then enhance for larger screens</li>
        <li>Use relative units (em, %) instead of fixed pixels where possible</li>
        <li>Keep CSS organized with clear comments</li>
        <li>Create reusable components that work across multiple pages</li>
      </ul>
    </section>

    <hr>

    <!-- Project Structure -->
    <section>
      <h2>📂 Project Structure</h2>
      <pre style="background: #f4f4f4; padding: 1rem; border-radius: 8px; overflow-x: auto;">
living-the-simple-life/
│
├── index.html              # Homepage with featured article
├── about.html              # About the author page
├── recentPosts.html        # All blog posts in consistent format
│
├── css/
│   ├── homeStyles.css      # Main stylesheet (shared across pages)
│   ├── aboutMe.css         # About page specific styles
│   └── recentPosts.css     # Recent posts page specific styles
│
├── images/                  # Blog images
└── README.md
      </pre>
    </section>

    <div class="footer-note">
      <p>Built with 💙 and lots of CSS learning</p>
      <p style="margin-top: 0.5rem;">© 2026 Living The Simple Life Project</p>
    </div>
  </main>
</body>
</html>
