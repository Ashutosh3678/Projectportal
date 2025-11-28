# Deployment Guide for Vercel

## Prerequisites
1. Ensure you have a Vercel account
2. Have your environment variables ready

## Environment Variables for Vercel
Set these in your Vercel dashboard:

```
NODE_ENV=production
MONGODB_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secure_jwt_secret
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
TWILIO_PHONE_NUMBER=your_twilio_phone
HUGGINGFACE_API_KEY=your_huggingface_key
```

## Deployment Steps
1. Push your code to GitHub
2. Connect your GitHub repo to Vercel
3. Add the environment variables in Vercel dashboard
4. Deploy!

## Project Structure
- Frontend: Static files served from `/frontend` directory
- Backend: API server from `/backend/server.js`
- API routes: Available at `/api/*`