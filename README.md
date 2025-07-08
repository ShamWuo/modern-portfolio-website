# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS (Tailwind), and JavaScript. Features a modern design with smooth animations, glass morphism effects, and a clean, professional layout.

## 🌟 Features

- **Modern Design**: Glass morphism effects, gradients, and smooth animations
- **Responsive**: Works perfectly on all devices (mobile, tablet, desktop)
- **Interactive**: Smooth scrolling, mobile menu, project filtering
- **Fast Loading**: Optimized images and efficient code
- **SEO Friendly**: Semantic HTML structure
- **Easy to Customize**: Clear comments and organized code structure

## 📁 Project Structure

```
portfolio/
├── index.html          # Home page with hero, about, skills, contact sections
├── works.html          # Portfolio/projects page with filtering
├── js/
│   └── script.js       # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### 1. Personal Information

**In `index.html`:**
- Line 63: Replace "Your Name" with your actual name
- Line 95-97: Replace profile picture URL
- Line 103: Replace with your name
- Line 106: Replace with your title/profession
- Line 110-113: Replace with your description
- Line 154-160: Replace with your story and background
- Line 164-168: Replace with more about yourself
- Line 171-183: Update social media links
- Line 298: Replace with your email
- Line 304: Replace with your phone number
- Line 310: Replace with your location
- Line 325: Replace with your name and current year

**Skills Section (Lines 190-280):**
- Replace skill names and percentages with your actual skills
- Adjust progress bar widths by changing the `style="width: X%"` values

### 2. Projects (works.html)

**To add your projects:**

1. **Find the projects section** (around line 140 in works.html)
2. **Copy the project template** provided in the comments (lines 259-288)
3. **Replace the following for each project:**
   - `YOUR_IMAGE_URL_HERE`: Project screenshot/image URL
   - `YOUR_PROJECT_TITLE`: Name of your project
   - `YOUR_PROJECT_DESCRIPTION`: Brief description
   - `YOUR_LIVE_DEMO_URL`: Link to live demo
   - `YOUR_GITHUB_URL`: Link to GitHub repository
   - `CATEGORY_HERE`: Category (web, mobile, design)
   - Technology tags in the bottom section

**Example project structure:**
```html
<div class="project-card glass-effect rounded-2xl overflow-hidden animate-scale-in" data-category="web">
    <div class="relative overflow-hidden">
        <img src="https://your-image-url.com/project.jpg" 
             alt="My Awesome Project" 
             class="w-full h-48 object-cover transition-transform duration-300 hover:scale-110">
        <div class="absolute inset-0 bg-gradient-to-t from-black/60 to-transparent opacity-0 hover:opacity-100 transition-opacity duration-300 flex items-end">
            <div class="p-4">
                <div class="flex space-x-3">
                    <a href="https://myproject.com" class="bg-white/20 p-2 rounded-full hover:bg-white/30 transition-colors duration-300">
                        <i class="fas fa-external-link-alt"></i>
                    </a>
                    <a href="https://github.com/username/project" class="bg-white/20 p-2 rounded-full hover:bg-white/30 transition-colors duration-300">
                        <i class="fab fa-github"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="p-6">
        <h3 class="text-xl font-semibold mb-2 text-purple-300">My Awesome Project</h3>
        <p class="text-gray-300 mb-4">A full-stack web application that does amazing things...</p>
        <div class="flex flex-wrap gap-2">
            <span class="bg-purple-600/30 text-purple-300 px-3 py-1 rounded-full text-sm">React</span>
            <span class="bg-purple-600/30 text-purple-300 px-3 py-1 rounded-full text-sm">Node.js</span>
            <span class="bg-purple-600/30 text-purple-300 px-3 py-1 rounded-full text-sm">MongoDB</span>
        </div>
    </div>
</div>
```

### 3. Images

**Profile Pictures:**
- Replace the profile image URL in the hero section
- Use high-quality images (recommended: 300x300px minimum)

**Project Images:**
- Use screenshots or mockups of your projects
- Recommended size: 600x400px for best quality
- Use services like Pexels, Unsplash for placeholder images

**Image Sources:**
- [Pexels](https://pexels.com) - Free stock photos
- [Unsplash](https://unsplash.com) - Free high-quality images

### 4. Colors and Styling

The portfolio uses a purple/blue gradient theme. To change colors:

**CSS Custom Properties (in the `<style>` sections):**
- `.gradient-text`: Change gradient colors
- Background gradients: Modify `from-slate-900 via-purple-900 to-slate-900`
- Button colors: Update `from-purple-600 to-blue-600`

### 5. Contact Information

**Update contact details in:**
- Email links: Replace `your.email@example.com`
- Phone numbers: Replace `+1 (555) 123-4567`
- Location: Replace `Your City, Country`
- Social media links in the about section

## 🚀 Getting Started

1. **Clone or download** this repository
2. **Open `index.html`** in your browser to view the site
3. **Edit the files** according to the customization guide above
4. **Test responsiveness** by resizing your browser window
5. **Deploy** to your preferred hosting service

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font)

## 📋 Features Included

### Home Page:
- Hero section with profile picture and introduction
- About section with personal story
- Skills section with progress bars
- Contact section with contact information

### Works Page:
- Project grid layout
- Category filtering (All, Web Development, Mobile Apps, UI/UX Design)
- Hover effects and animations
- Project links (demo and GitHub)

### JavaScript Features:
- Mobile menu toggle
- Smooth scrolling navigation
- Project filtering
- Scroll animations
- Form validation (if contact form is added)
- Responsive design helpers

## 🎯 SEO Tips

1. **Update page titles** in the `<title>` tags
2. **Add meta descriptions** for better search engine visibility
3. **Use descriptive alt text** for all images
4. **Optimize images** for faster loading
5. **Add structured data** if needed

## 🚀 Deployment Options

- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Easy deployment with form handling
- **Vercel**: Fast deployment with great performance
- **Traditional hosting**: Upload files via FTP

## 📞 Support

If you need help customizing your portfolio:

1. **Check the comments** in the code for guidance
2. **Review this README** for detailed instructions
3. **Test changes** in small increments
4. **Use browser developer tools** to debug issues

## 🎨 Design Credits

- Design inspiration from modern portfolio trends
- Icons by Font Awesome
- Fonts by Google Fonts
- Images from Pexels (for examples)

---

**Happy coding! 🚀**

Remember to replace all placeholder content with your actual information and projects.
