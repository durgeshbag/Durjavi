# Will You Be My Valentine? 💕

A romantic and interactive website to ask that special someone to be your Valentine! This project features a fun interaction where the "No" button runs away when clicked, and the "Yes" button grows bigger!

## 🌟 Features

- Beautiful pink gradient design
- Interactive buttons (the "No" button moves away!)
- Cute animated GIF
- Responsive design (works on mobile and desktop)
- Special "Thank You" page when they say yes
- Floating hearts animation

## 📁 Project Structure

```
valentine-project/
├── index.html          # Main page with the question
├── thankyou.html       # Thank you page shown after clicking "Yes"
├── css/
│   └── valentine.css   # Styling for the main page
```

## 🚀 Quick Deployment to GitHub Pages

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign Up"
3. Follow the registration (takes 2 minutes)

### Step 2: Create a New Repository
1. Click the "+" icon (top right)
2. Select "New repository"
3. Repository name: `valentine`
4. Select: ✓ Public
5. Click "Create repository"

### Step 3: Upload Files
1. Click "uploading an existing file"
2. Drag and drop ALL files:
   - index.html
   - thankyou.html
   - css/valentine.css
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to Settings (top menu)
2. Click "Pages" (left sidebar)
3. Under "Source": Select "main" branch
4. Click "Save"
5. WAIT 2-3 MINUTES ⏰

### Step 5: Get Your Link 💕
Your website will be at:
```
https://YOUR-GITHUB-USERNAME.github.io/valentine/
```

Example: If your username is "johnsmith", the link is:
```
https://johnsmith.github.io/valentine/
```

**SHARE THIS LINK WITH YOUR VALENTINE! ❤️**

---

## 🎨 Customization

### Change the Question Text
Edit [index.html](index.html#L7):
```html
<div id="valentineQuestion"><b>Your custom question here</b></div>
```

### Change the "No" Button Text
Edit [index.html](index.html#L12):
```html
<button class="answerButton" id="noButton">Custom text here</button>
```

### Change Colors
Edit [css/valentine.css](css/valentine.css):
```css
background: linear-gradient(135deg, #ffeef8 0%, #ffe0f0 100%);
/* Change these hex color codes to your preferred colors */
```

### Change the GIF
The default GIF URLs are already included from Giphy. To use a different GIF:

1. Go to https://giphy.com
2. Find a cute GIF you like
3. Click "Share" → Copy the GIF Link
4. Edit [index.html](index.html#L14) and replace the `src` URL:
```html
<img src="YOUR-NEW-GIF-URL" alt="cat asking question" class="responsive" />
```

---

## 📱 Alternative Deployment Options

### Option 2: Netlify (Also FREE!)
1. Go to https://netlify.com
2. Sign up for free
3. Drag your folder onto the page
4. Get instant link: `https://random-name.netlify.app`

### Option 3: Vercel (Also FREE!)
1. Go to https://vercel.com
2. Sign up with GitHub
3. Import your repository
4. Get your link instantly

---

## ✅ Checklist Before Deploying

- [ ] All files created (index.html, thankyou.html, css/valentine.css)
- [ ] Links between pages work when tested locally
- [ ] GIFs are loading properly
- [ ] Tested on mobile view
- [ ] Repository is set to PUBLIC (not private)

---

## 🐛 Troubleshooting

**Q: The website isn't showing up?**
- Check that your repository is PUBLIC
- Wait 5 minutes and refresh (GitHub Pages needs time to deploy)
- Check the "Actions" tab in your repository for deployment status

**Q: The "No" button isn't moving?**
- Clear your browser cache
- Make sure JavaScript is enabled in your browser

**Q: GIFs aren't loading?**
- The GIF URLs from Giphy might have changed
- Use a direct Giphy link or upload a `.gif` file to the repository

**Q: How do I update the website?**
- Edit the files in your GitHub repository
- Commit the changes
- GitHub Pages will automatically update (takes 1-2 minutes)

---

## 💡 Pro Tips

- Send the link with a romantic message
- Time it for a special moment
- Use QR codes to share (QR code generators online)
- Customize the message on the thank you page
- Mobile-friendly by default!

---

## 📄 License

Free to use for personal romantic purposes! ❤️

Good luck! May your Valentine say YES! 💕