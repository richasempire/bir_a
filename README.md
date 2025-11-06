# 🎂 The Trail of Apporv - Birthday Adventure

An interactive birthday experience that creates a personalized journey with AI-generated images based on user choices.

## ✨ Features

- **Interactive Trail**: Navigate through 6 waypoints making choices about terrain, weather, travel buddy, snack, and path
- **AI Image Generation**: Automatically generates a unique image using OpenAI's DALL-E 3 based on all choices made
- **Beautiful UI**: Gradient backgrounds, smooth animations, and responsive design
- **Personalized Experience**: Each combination of choices creates a different adventure and image

## 🎮 How It Works

1. Start the trail and begin your journey
2. Make choices at each waypoint:
   - 🏔 **Terrain**: Mountains or Desert
   - ☀️ **Weather**: Sunny or Stormy
   - 🐕 **Buddy**: Dog or Monkey
   - 🍟 **Snack**: Fries or Chocolate
   - 🚤 **Path**: Speedboat or Bridge
3. Reach the summit and see your choice analysis
4. Click to generate a unique AI image of your journey!

## 🔧 Setup

### Prerequisites
- OpenAI API key ([Get one here](https://platform.openai.com/api-keys))
- Vercel account (for deployment)

### Deployment to Vercel

1. **Fork or clone this repository**

2. **Import to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "Import Project"
   - Select your repository

3. **Add Environment Variable:**
   - In Vercel project settings → Environment Variables
   - Add: `OPENAI_API_KEY` = `your-api-key-here`
   - Click "Save"

4. **Deploy!**
   - Vercel will automatically deploy your project
   - Your API key stays secure on the server

### Local Development

To test locally:

1. Clone the repository:
```bash
git clone https://github.com/richasempire/bir_a.git
cd bir_a
```

2. Install Vercel CLI:
```bash
npm i -g vercel
```

3. Create `.env` file:
```bash
echo "OPENAI_API_KEY=your-api-key-here" > .env
```

4. Run locally:
```bash
vercel dev
```

5. Open http://localhost:3000 in your browser

## ⚠️ Important Security Note

**Before committing to a public repository:**
- Replace your actual API key with a placeholder
- Consider using environment variables or a backend server for production
- Set usage limits on your OpenAI account

## 🎨 Technologies Used

- HTML5
- CSS3 (Gradients, Animations, Flexbox, Grid)
- Vanilla JavaScript
- OpenAI DALL-E 3 API

## 📝 License

This is a personal birthday project. Feel free to use and modify for your own celebrations!

## 🎉 Credits

Created with ❤️ for Apporv's Birthday

