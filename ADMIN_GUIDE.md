# 📖 UNSW PPE Society Website - Admin Guide

**For Future Executive Teams - No Coding Required!**

---

## 🌐 Website URL
**Live Site:** https://unswppesociety.github.io/unsw-ppe-society/

**GitHub Repository:** https://github.com/unswppesociety/unsw-ppe-society

---

## 👥 Getting Access

### Step 1: Get Added as a Collaborator
1. Ask the current President or Webmaster for access
2. They go to: https://github.com/unswppesociety/unsw-ppe-society
3. Settings → Collaborators → Add people
4. Enter your GitHub username
5. Accept the email invitation

### Step 2: Create a GitHub Account (if you don't have one)
1. Go to: https://github.com/signup
2. Sign up with your email
3. Verify your email
4. Share your username with the President

---

## ✏️ How to Edit the Website (No Code Knowledge Needed!)

### **The Easy Way: Edit on GitHub.com**

1. **Go to:** https://github.com/unswppesociety/unsw-ppe-society
2. **Click on the file** you want to edit (e.g., `events.html`)
3. **Click the pencil icon** ✏️ ("Edit this file")
4. **Make your changes** (like editing a document)
5. **Scroll down** and add a description (e.g., "Added new event")
6. **Click "Commit changes"**
7. **Wait 2 minutes** - your changes are live! ✨

---

## 📋 Common Tasks

### ➕ **Adding a New Event**

**File to edit:** `events.html`

1. Open `events.html` on GitHub
2. Click the pencil icon ✏️
3. Find this section (around line 60):
   ```html
   <div class="col-md-6">
       <div class="card event-card h-100">
           <div class="card-body">
               <div class="d-flex justify-content-between align-items-start mb-3">
                   <div class="event-date">
                       <i class="far fa-calendar-alt"></i> Date TBA
                   </div>
                   <span class="badge bg-primary">Upcoming</span>
               </div>
               <h4 class="card-title">Event Title</h4>
               <p class="text-muted mb-2">
                   <i class="far fa-clock"></i> Time | 
                   <i class="fas fa-map-marker-alt"></i> Location
               </p>
               <p class="card-text">Event description goes here.</p>
           </div>
       </div>
   </div>
   ```

4. **Copy this entire block**
5. **Paste it below** the existing events
6. **Change the text:**
   - Replace "Date TBA" with your date (e.g., "March 15, 2026")
   - Replace "Event Title" with your event name
   - Replace "Time" and "Location" with actual details
   - Replace description text
7. **Commit changes**

---

### 👤 **Updating Executive Team**

**File to edit:** `about.html`

1. Open `about.html` on GitHub
2. Click the pencil icon ✏️
3. Find the "Executive Team" section (around line 100)
4. Look for cards like this:
   ```html
   <h5 class="card-title">Name Here</h5>
   <p class="text-muted">Position</p>
   ```
5. **Change the name and position**
6. To add more members, copy an entire card and paste it
7. **Commit changes**

---

### 📝 **Adding a Blog Post**

**File to edit:** `blog.html`

1. Open `blog.html` on GitHub
2. Click the pencil icon ✏️
3. Find an existing blog post card (around line 50)
4. **Copy the entire card:**
   ```html
   <div class="col-md-6 col-lg-4">
       <div class="card blog-card h-100">
           <div class="card-body">
               <div class="mb-3">
                   <span class="badge bg-primary">Category</span>
                   <span class="text-muted ms-2"><i class="far fa-calendar"></i> Date</span>
               </div>
               <h4 class="card-title">Post Title</h4>
               <p class="card-text">Post description...</p>
               <a href="#" class="btn btn-outline-primary">Read More</a>
           </div>
       </div>
   </div>
   ```
5. **Change:**
   - Category badge (Politics/Philosophy/Economics)
   - Date
   - Title and description
6. **Commit changes**

---

### 📧 **Changing Contact Email**

**File to edit:** `contact.html`

1. Open `contact.html`
2. Search for: `mailto:contact@unswppesoc.com`
3. Replace with your new email
4. Commit changes

---

### 🔗 **Updating Social Media Links**

**Files to edit:** All pages (footer section)

1. Open any HTML file
2. Find the footer section (bottom of file)
3. Look for links like:
   ```html
   <a href="https://www.facebook.com/UNSWPPESoc" target="_blank">
   <a href="https://www.instagram.com/unswppesoc/" target="_blank">
   ```
4. Replace URLs with updated links
5. Repeat for all pages OR ask someone to do it with code

---

## 🎨 Changing Colors/Styles

**File to edit:** `css/style.css`

1. Open `css/style.css`
2. At the top, you'll see:
   ```css
   :root {
       --primary-blue: #5B9DBD;
       --secondary-green: #7FB69E;
       --gold-accent: #F4C430;
   }
   ```
3. **Change the color codes** (use a color picker online)
4. Commit changes

**Free Color Picker Tool:** https://htmlcolorcodes.com/color-picker/

---

## 🖼️ **Changing the Logo**

1. **Prepare your new logo:**
   - Save it as `logo.png`
   - Recommended size: 500x500 pixels

2. **Upload to GitHub:**
   - Go to the `images/` folder
   - Click "Add file" → "Upload files"
   - Drag your `logo.png` (it will replace the old one)
   - Commit changes

---

## ⚠️ **Important Tips**

### ✅ DO:
- Make small changes and test them
- Write clear commit messages (e.g., "Added March event")
- Ask for help if unsure
- Keep backups of important info

### ❌ DON'T:
- Delete entire sections of code unless you're sure
- Forget to commit your changes
- Edit multiple files at once when learning

---

## 🆘 **If Something Breaks**

Don't panic! GitHub keeps a history of all changes.

### To Undo Changes:
1. Go to the file on GitHub
2. Click "History" (clock icon)
3. Find the last working version
4. Click "..." → "Revert this commit"

OR ask someone with coding experience to help restore it.

---

## 📱 **Quick Reference Links**

| Task | File to Edit |
|------|--------------|
| Add events | `events.html` |
| Update team | `about.html` |
| Add blog post | `blog.html` |
| Change contact info | `contact.html` |
| Edit home page | `index.html` |
| Update resources | `resources.html` |
| Change colors | `css/style.css` |

---

## 🎓 **Training New Execs**

### Handover Checklist:
- [ ] Add new execs as GitHub collaborators
- [ ] Show them how to edit a file on GitHub
- [ ] Walk through adding a test event together
- [ ] Share this guide document
- [ ] Give them the society email login for Google Search Console

### Recommended Roles:
- **President:** Full access, overall oversight
- **VP/Secretary:** Can edit events, blog posts
- **Publications Officer:** Blog posts, content updates
- **IT Officer (optional):** Handles technical issues

---

## 💡 **Want to Learn More?**

### Free Resources:
- **GitHub Basics:** https://docs.github.com/en/get-started
- **HTML Tutorial:** https://www.w3schools.com/html/
- **YouTube:** "How to edit a website on GitHub" tutorials

### Need Help?
- Ask in the exec Discord channel
- Email previous webmaster/president
- Post in UNSW CS/IT society forums

---

## 🎉 **You've Got This!**

Remember: The website is designed to be simple. You don't need to be a programmer to update content. Just follow this guide, make small changes, and test them. Future execs will thank you for keeping the website updated!

**Questions?** Contact the current IT officer or previous exec team.

---

*Last Updated: January 2026*
*Created by: UNSW PPE Society 2025/26 Executive Team*

 