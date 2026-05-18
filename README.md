# XECUREDLY ACADEMY - SETUP GUIDE

## 📁 FILES INCLUDED

1. **index.html** - Login page (main entry point)
2. **dashboard.html** - Student dashboard with 12 lessons

---

## 🔐 ACCESS CODE

**Default Access Code:** `AJIBOLA-26`

Students must enter this code to access the academy.

---

## 🚀 HOW TO DEPLOY

### Option 1: Local Testing
1. Put both files in the same folder
2. Open `index.html` in your browser
3. Enter access code: `AJIBOLA-26`
4. Start learning!

### Option 2: Web Hosting (Recommended)
1. Upload both files to your web hosting root directory
2. Make sure both files are in the same folder
3. Visit your domain (e.g., `yourdomain.com`)
4. Login page loads automatically
5. Share the URL with students

---

## 🎓 LESSON DURATIONS

All lessons are 2+ hours:
- Lesson 1: 2h 15min
- Lesson 2: 2h 30min
- Lesson 3: 3h 00min
- Lesson 4: 2h 45min
- Lesson 5: 2h 30min
- Lesson 6: 3h 15min
- Lesson 7: 2h 20min
- Lesson 8: 3h 00min
- Lesson 9: 2h 40min
- Lesson 10: 2h 30min
- Lesson 11: 2h 15min
- Lesson 12: 2h 00min

**Total Course Duration: 31+ hours**

---

## 🎥 YOUR VIDEOS

7 videos are already connected:
✅ Lesson 1: Introduction to SOC Operations
✅ Lesson 2: Security Logs & Analysis
✅ Lesson 3: Computer Networking Fundamentals
✅ Lesson 4: Cryptography Essentials
✅ Lesson 5: MITRE ATT&CK & Cyber Kill Chain
✅ Lesson 6: Phishing & DDoS Attack Labs
✅ Lesson 7: Advanced Phishing Analysis

**To add videos for lessons 8-12:**
Open `dashboard.html` and add your Google Drive URLs in the videoUrl field.

---

## 🔑 HOW IT WORKS

### Login Flow:
1. Student visits `index.html`
2. Enters access code: `AJIBOLA-26`
3. System validates code
4. Redirects to `dashboard.html`
5. Login persists (stays logged in)

### Logout Flow:
1. Click "Logout" button
2. Confirm logout
3. Session cleared
4. Redirects back to `index.html`

### Security:
- Access code required
- Session stored in browser
- Dashboard protected (can't access without login)
- All data saved locally

---

## ➕ ADDING MORE ACCESS CODES

To add more student codes, open `index.html` and find line ~175:

```javascript
const validAccessCodes = [
    'AJIBOLA-26',
    'AJIBOLA26',
];
```

Add new codes:
```javascript
const validAccessCodes = [
    'AJIBOLA-26',
    'AJIBOLA26',
    'STUDENT-01',
    'TEACHER-99',
    'NEWCODE-50',
];
```

---

## 🎨 FEATURES

### Login Page:
- ✅ Beautiful animated background
- ✅ Secure access code system
- ✅ Auto-formatting (adds hyphen)
- ✅ Real-time validation
- ✅ Professional design

### Dashboard:
- ✅ 12 comprehensive lessons
- ✅ Progress tracking
- ✅ Completion badges
- ✅ Video player integration
- ✅ Smooth animations
- ✅ Mobile responsive
- ✅ Auto-save progress

---

## 📱 MOBILE FRIENDLY

Both pages work perfectly on:
- Desktop computers
- Tablets
- Mobile phones

---

## 🆘 TROUBLESHOOTING

**Problem:** Can't login
**Solution:** Make sure you're typing `AJIBOLA-26` exactly (case doesn't matter)

**Problem:** Videos not showing
**Solution:** Check that your Google Drive videos are shared publicly

**Problem:** Dashboard shows "Please login"
**Solution:** Clear browser cache and login again

**Problem:** Progress not saving
**Solution:** Don't use incognito/private mode

---

## 💡 TIPS

1. **For best experience:** Use Chrome, Firefox, or Safari
2. **Video hosting:** Make sure all Google Drive videos are set to "Anyone with link can view"
3. **Testing:** Test on multiple devices before sharing with students
4. **Backup:** Keep copies of both files in a safe place

---

## 📞 SUPPORT

For technical support or questions, contact the administrator.

---

**Built with ❤️ for Xecuredly Academy**
Professional Cybersecurity Training Platform
