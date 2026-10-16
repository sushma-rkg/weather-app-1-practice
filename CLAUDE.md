# Working rules
- I am a complete beginner. Explain everything in simple, non-technical words. Avoid jargon, and if you must use a technical word, explain it in one sentence.
- Work on ONE step at a time. Never build features I haven't asked for in the current message.
- Before writing code for any step, tell me your plan in 5 to 7 simple bullets and wait for me to say "go".
- When a step is done, STOP. Tell me what you changed, exactly what I should see on screen to check it works, and wait for my next instruction.
- Do not add placeholder code for future features.
- Never push to main and never switch to main. Do not merge branches yourself. I merge pull requests myself on GitHub. If I ask you to do something on main, treat it as a single action, then return to your working branch and tell me which branch you are on. 
- Before every commit and push, state which branch you are on. If it is main, stop and ask me.

# Project
A weather website. The user types a city name and the page shows the current weather for that city, using data from weatherapi.com.
- The code is stored on GitHub.
- The site will be deployed on Vercel, so keep it simple and compatible with Vercel hosting.
- The weatherapi.com API key is a secret. Never write it in the code, never show it on screen, and never ask me to paste it into the chat.
- The API key is stored on Vercel in an environment variable called WEATHER_API_KEY. I add it myself in the Vercel project settings.
- Never create a file that contains the key.
- The key must never be sent to the browser. The page should call a small server-side function on Vercel, and that function calls weatherapi.com.

# Requirements that always apply
- Show the temperature in Celsius.
- If the city is not found or the weather cannot be loaded, show a friendly message instead of an error.
- Show a simple "Loading..." message while the weather is being fetched.
- The API key must never appear in anything pushed to GitHub.
