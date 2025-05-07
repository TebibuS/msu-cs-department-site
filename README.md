# MSU Computer Science Department Website  

📄 **Author**: Tebibu Kebede  
🏫 **University**: Minnesota State University, Mankato  
🎯 **Project Scope**: Department Portfolio Site (Spring 2025)  
💻 **Tech Stack**: HTML, CSS, JavaScript, AOS.js  

---

## 🧭 Objective  
To build a visually branded, interactive, and content-rich website representing the MSU Computer Science Department. The goal is to showcase faculty, real client projects, internship experiences, and student outcomes to appeal to prospective students, industry partners, and academic donors.  

---

## 🏗️ Project Structure  
📁 WEBSITE/
├── index.html # Homepage with hero, intro, and program overview
├── projects.html # Real Client Projects by semester
├── faculty.html # Expandable faculty & staff directory
├── Careers.html # Internships, testimonials, and job outcomes
├── style.css # Central stylesheet using MSU branding
└── Pictures/ # Images: faculty, projects, campus, logos


---

## ✨ Core Features  

### 1. Responsive Navigation Bar  
- Sticky top nav using Flexbox.  
- Branding uses Maverick Purple (`#49306e`) and Gold (`#febd11`).  

### 2. Hero Section with Slideshow  
- Rotates full-screen background images every 4 seconds.  
- Layered overlay for contrast and gold-colored headings.  

### 3. Real Client Projects (`projects.html`)  
- Organized by semester (Fall 2023 – Spring 2025).  
- Clickable collapsible sections per company:  
  ```html
  <div class="project-card">
    <div class="project-company">BBB</div>
    <div class="project-title">Data Gets Better and Better</div>
  </div>
4. Faculty & Staff Directory
Click-to-expand profile cards with headshots, titles, and contact info.

Animated using AOS.js.

🎨 Branding Guidelines
Element	Style Guide
Font	Kanit (Google Fonts)
Purple	#49306e (Maverick Purple)
Gold	#febd11 (Maverick Gold)
Layout	Flex/Grid with box shadows
🛠️ Tools & Libraries
Editor: VS Code

Styling: HTML5/CSS3

Animations: AOS (Animate on Scroll)

Embedded Media: YouTube promo video

📋 How to Contribute
Add Projects:
Copy an existing <div class="semester-column"> and update content.

Store new images in /Pictures with consistent naming.

Update Branding:
Modify the CSS variables in style.css:

css
:root {
  --msu-purple: #49306e;
  --msu-gold: #febd11;
}
🔮 Future Ideas
Add a CMS/JSON backend for dynamic content.

Implement dark mode.

Integrate search/filter functionality.

✅ Completed Tasks (Spring 2025)
Designed multi-page layout with MSU theme.

Embedded promo video and real client projects.

Added smooth animations and interactive faculty cards.

📌 Summary: A student-built showcase of MSU’s CS Department, emphasizing academic rigor, industry collaboration, and scalable design.


### How to Use:  
1. Copy the entire text above.  
2. Create a file named `README.md` in your project folder.  
3. Paste the text into the file.  
4. Commit and push to GitHub.  
