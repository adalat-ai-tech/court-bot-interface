# 🚀 Frontend Deployment Guide

## Quick Deployment Steps

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com)
2. Click "New repository"
3. Repository name: `court-bot-interface`
4. Organization: `adalat-ai-tech`
5. Make it **Public**
6. Don't initialize with README (we already have one)
7. Click "Create repository"

### 2. Push Code to GitHub
```bash
# In the frontend directory
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" in the left sidebar
3. Source: "Deploy from a branch"
4. Branch: `main`
5. Folder: `/ (root)`
6. Click "Save"

### 4. Your Public URL
After deployment (takes 2-3 minutes):
```
https://adalat-ai-tech.github.io/court-bot-interface/
```

## 🎯 What This Interface Does

- **Beautiful Chat UI**: Modern, responsive design
- **Real API Connection**: Connects to your deployed bot
- **Fallback Mode**: Works even if API is offline
- **Example Queries**: Quick test buttons
- **Status Monitoring**: Shows connection status
- **Mobile Friendly**: Works on all devices

## 🔧 Features

- ✅ **Auto-connects** to your Cloud Run service
- ✅ **Fallback responses** if API is unavailable
- ✅ **Real-time status** indicator
- ✅ **Example queries** for testing
- ✅ **Message history** tracking
- ✅ **Error handling** with user-friendly messages

## 📱 Team Testing

Once deployed, share this URL with your team:
```
https://adalat-ai-tech.github.io/court-bot-interface/
```

They can:
- Test case status queries
- Check defect status
- View cause lists
- Send general inquiries
- See real bot responses

## 🔒 Security

- **No sensitive data** exposed
- **CORS enabled** for safe API calls
- **Public interface** for team testing
- **Private backend** remains secure

---

**Ready to deploy!** 🚀 