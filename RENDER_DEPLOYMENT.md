# Render Deployment Instructions

## Your project is ready for Render deployment!

### Required Environment Variables in Render:
```
NODE_ENV=production
DPS_USERNAME=your_portal_username
DPS_PASSWORD=your_portal_password
GMAIL_EMAIL=your_gmail@gmail.com
GMAIL_APP_PASSWORD=your_16_character_app_password
```

### Render Service Settings:
- **Build Command**: `npm install && npm run build`
- **Start Command**: `npm start`
- **Environment**: Node.js
- **Plan**: Free tier works fine

### Your Gmail App Password:
1. Go to myaccount.google.com
2. Security → 2-Step Verification (enable if needed)
3. Security → App passwords → Generate new
4. Use the 16-character password (not your regular Gmail password)

### Files Ready for Deployment:
- ✅ package.json (with correct build scripts)
- ✅ All source code organized
- ✅ Production build configuration
- ✅ Environment variable setup
- ✅ Render configuration files

### Next Steps:
1. Add environment variables in Render dashboard
2. Connect your GitHub repository
3. Deploy with the settings above
4. Your DPS Event Notifier will be live!

The app will automatically:
- Monitor DPS portal for new events
- Send email notifications
- Generate PDF exports
- Support WhatsApp notifications