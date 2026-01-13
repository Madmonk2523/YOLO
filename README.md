# YOLO Yogurt & Desserts - Website

An amazing, modern website for YOLO Yogurt & Desserts, located in the historic section of Roslyn, NY.

## 🍦 Features

- **Stunning Hero Section** - Eye-catching animated gradient background with compelling call-to-action
- **Responsive Design** - Perfect viewing experience on desktop, tablet, and mobile devices
- **Interactive Menu** - Showcasing frozen yogurt, gelato, crepes, acai bowls, coffee & tea
- **Special Highlights** - Featuring the exclusive self-serve Acai Berry machine
- **Gallery Section** - Visual showcase with placeholder areas for your actual photos
- **Location Info** - Hours, outdoor dining information, and map integration ready
- **Contact Form** - Fully functional contact form with validation
- **Smooth Animations** - Scroll effects, hover animations, and fade-in transitions
- **Mobile Navigation** - Hamburger menu for seamless mobile experience
- **Back to Top Button** - Easy navigation on long pages
- **Social Media Integration** - Facebook link and placeholder for Instagram/Twitter
- **Easter Egg** - Hidden surprise for visitors who click the logo 5 times!

## 🎨 Color Scheme

- **Primary Pink:** #FF6B9D
- **Secondary Purple:** #C060A1
- **Accent Yellow:** #FEC260
- **Accent Blue:** #4ECDC4
- **Accent Green:** #95E1D3

## 📁 File Structure

```
YOLO/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # Interactive JavaScript features
├── README.md          # This file
└── assets/
    └── images/        # Place your photos here
```

## 🚀 Getting Started

1. **Open the website:**
   - Simply open `index.html` in any modern web browser
   - Or use a local server for best experience

2. **Add Your Images:**
   - Place your yogurt, crepe, and cafe photos in the `assets/images/` folder
   - Update the gallery section in `index.html` to use your actual images

3. **Update Contact Information:**
   - Edit phone numbers in `index.html` (search for "(516) XXX-XXXX")
   - Update email address (search for "info@yoloyogurt.com")
   - Add your actual business hours

4. **Customize Content:**
   - Update business hours in the Location section
   - Add/modify menu items as needed
   - Adjust any text to match your branding

## 📸 Adding Real Images

To replace the placeholder images in the gallery:

1. Save your images in `assets/images/` folder
2. In `index.html`, find the gallery section
3. Replace the `gallery-placeholder` divs with actual `<img>` tags:

```html
<div class="gallery-item">
    <img src="assets/images/your-photo.jpg" alt="Description">
</div>
```

## 🌟 Special Features

### Dynamic Greeting
The hero subtitle changes based on the time of day:
- Morning: "Start Your Morning Sweet"
- Afternoon: "Perfect Afternoon Treats"
- Evening: "Evening Delights"
- Late Night: "Late Night Sweet Cravings"

### Easter Egg
Click the YOLO logo 5 times to trigger a confetti animation and reveal a special promo code!

### Smooth Scrolling
All navigation links smoothly scroll to their respective sections.

### Mobile Responsive
The website automatically adapts to all screen sizes with a mobile-friendly hamburger menu.

## 🔧 Customization Tips

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #FF6B9D;
    --secondary-color: #C060A1;
    /* etc. */
}
```

### Adding More Menu Items
Copy and paste a menu-item div in the menu section and update the content.

### Modifying Hours
Update the hours-list section in the Location area of `index.html`.

## 📱 Social Media

- **Facebook:** [YOLO Yogurt NY](https://www.facebook.com/YOLOYOGURTNY/)
- **Instagram:** Add your Instagram handle
- **Twitter:** Add your Twitter handle

## 🎯 SEO Optimized

The website includes:
- Proper meta tags for search engines
- Semantic HTML structure
- Descriptive alt attributes (add to your images)
- Fast loading times

## 💡 Tips for Going Live

1. **Get a Domain Name:** Register a domain like `yoloyogurtny.com`
2. **Choose Hosting:** Use services like Netlify, Vercel, or traditional web hosting
3. **Add Google Maps:** Replace the map placeholder with an embedded Google Maps iframe
4. **Set Up Email:** Configure the contact form to actually send emails
5. **Add Analytics:** Consider adding Google Analytics to track visitors
6. **Connect Social Media:** Update all social media links with your actual profiles

## 🆘 Support

For questions or assistance with customization:
- Review the code comments in each file
- Check browser console for any JavaScript errors
- Ensure all files are in the correct directory structure

## 📄 License

This website was custom-built for YOLO Yogurt & Desserts.

---

**Made with ❤️ for YOLO Yogurt & Desserts**

*You Only Live Once - Make it Sweet!* 🍦🍨🥞☕
