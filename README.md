# Search UI

This repository contains the complete source code for Search_modernize, an interactive web-based search application publicly hosted at: https://aryak-mohanty.github.io/Search_modernize/ .  The project provides a modern, responsive, and user-friendly interface that integrates Google Custom Search, offering a clean search experience with resizable panels, infinite scrolling, and optional dark mode.


<h2>📌 Overview</h2>

Search_modernize is designed to replicate a modern search UI with smooth transitions, split-view resizing, animated results, and mobile responsiveness. It demonstrates the integration of real-time search results via Google Custom Search API, combined with practical UI/UX enhancements using HTML, CSS, Bootstrap, JavaScript, and a service worker for offline fallback capability.


<h2>🧩 Features</h2>
 
 1. Modern & Responsive UI ->
<ul style="list-style-type: disc;"> 
<li>Clean layout built using Bootstrap 5 and Inter font</li>
<li>Adjustable split-view with draggable divider (desktop & mobile)</li> 
<li>Smooth animated result cards and transitions</li>
</ul>

2. Light/Dark Theme Toggle ->
<ul style="list-style-type: disc;"> 
<li>Optional dark mode with persistent state via localStorage</li>
<li>Auto-adapts to system preference (prefers-color-scheme)</li> 
</ul>

3. Advanced Search Behavior ->
<ul style="list-style-type: disc;"> 
<li>Integrated Google Custom Search API</li>
<li>Infinite scroll for continuous result loading</li> 
<li>Real-time search with Enter key and clickable Search button</li>
<li>Thumbnail preview if available via pagemap.cse_image</li>
</ul>

4. Offline Support (Service Worker) ->
<ul style="list-style-type: disc;"> 
<li>Caches essential resources (index.html, icons)</li>
<li>Provides fallback view when offline</li> 
</ul>

5. Mobile-Optimized Design ->
<ul style="list-style-type: disc;"> 
<li>Search panel collapses vertically</li>
<li>Touch-enabled divider for resizing</li> 
<li>Layout automatically adjusts for small screens</li>
</ul>

<h2>🛠 Technologies Used</h2>
<ul style="list-style-type: disc;"> 
<li>HTML5, CSS3, JavaScript (ES6)</li>
<li>Bootstrap 5</li> 
<li>Google Custom Search API</li>
<li>Service Worker (for caching and offline fallback)</li>
<li>Inter typeface (Google Fonts)</li>
</ul>


<h2>📦 Installation & Setup</h2>

To run this project locally:
1. Clone the repository
    <pre><code>git clone https://github.com/Aryak-Mohanty/Search_modernize.git</code></pre>
    <pre><code>cd Search_modernize</code></pre>
2. Run the application:
Simply open the index.html file in any modern web browser.

<h5>Important Notes:</h5>
<b>The Google Custom Search API requires internet access — offline search results are not possible.</b>


<h2>🚀 Deployment</h2>

Search_modernize is deployed using GitHub Pages, ensuring:
<ul style="list-style-type: disc;"> 
<li>Fast static hosting</li>
<li>Automatic updates on push</li> 
<li>Easy public accessibility</li>
</ul>

<h3>🔗 Live Site:</h3>
https://aryak-mohanty.github.io/Search_modernize/


<h2>🐞 Known Issues / Bugs</h2>

1.Infinite Scroll:
At times, Google API may return fewer results than expected, leading to empty loads at the bottom.

2.Panel Resizing:
On some mobile browsers, the drag movement may feel slightly jumpy.

3.Offline Cache Limitations:
Only essential files are cached. Search API cannot operate offline (expected behavior).

4.API Rate Limits:
Free-tier Google API quotas may cause intermittent failures.


<h2>🔮 Future Improvements</h2>

🔒 Secure API Handling:
Move API keys to a backend proxy to prevent exposure in front-end code.

🎨 UI Smoothness Enhancements:
Add micro-animations, better transitions, and more fluid resizing.

⚙️ Search Optimization:
Introduce filters (images, news, time range) and better error handling.

📱 Better Mobile UX:
Add a collapsing search bar and more compact result cards.

📦 Improved Caching:
Cache CSS/JS files more effectively for faster offline fallback.

🐛 Bug Fix Pass:
Patch inconsistent infinite scrolling and resize sensitivity.


<h2>📄 License</h2>

This project is developed for educational and personal use. Redistribution or replication without permission is discouraged. API keys included in this project should not be reused for production systems.

<br>
