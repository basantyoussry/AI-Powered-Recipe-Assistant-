# AI-Powered-Recipe-Assistant-
 In the realm of cooking, beginners often face challenges with complex recipes lacking clear guidance. To address this, I've developed an AI-powered recipe assistant focused on simplicity, interactivity, and user-friendliness.
Are you a beginner in the kitchen looking for an easy way to follow recipes? I’ve built a project that simplifies cooking by combining AI text generation, voiceovers, and video creation to guide users step-by-step. Here’s how it works:

The Problem:
Cooking can be overwhelming for beginners, especially when recipes are hard to follow or lack visual and audio guidance. My project aims to make cooking simple, interactive, and beginner-friendly.

The Solution:
I created an AI-powered recipe assistant that:

Fetches Recipes Using AI (Spoonacular API):

Users can search for any recipe (e.g., "Italian Pizza").

The app uses the Spoonacular API to fetch detailed instructions, ingredients, and step-by-step guidance.

This ensures users get accurate and reliable recipes tailored to their search.

Generates Voiceovers for Each Step:

Once the recipe steps are fetched, the app uses Google Text-to-Speech (gTTS) to generate voiceovers for each step.

This helps users follow along without constantly looking at their screens.

Creates a Step-by-Step Video:

Using Stable Diffusion, the app generates images for each step of the recipe.

These images are combined with the voiceovers using MoviePy to create a seamless, easy-to-follow video.

The final video is saved as recipe_video.mp4, ready to guide users through the cooking process.

Key Techniques Used:
AI Text Generation: Spoonacular API for fetching recipes.

Voiceover Generation: gTTS for converting text instructions into audio.

Image Generation: Stable Diffusion for creating visuals for each step.

Video Creation: MoviePy for combining images and voiceovers into a video.

Why This Matters:
This project is designed to make cooking accessible and enjoyable for beginners. By providing visual, audio, and step-by-step guidance, it removes the guesswork and helps users build confidence in the kitchen.

What’s Next?
I’m excited to explore more features, like:

Adding multilingual support for voiceovers.

Integrating user feedback to improve recipe suggestions.

Expanding the recipe database for more diverse cuisines.

If you’re passionate about AI, cooking, or simplifying everyday tasks, I’d love to hear your thoughts! Let’s connect and discuss how we can make cooking even more fun and accessible. 
