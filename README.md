Dad Feelings Spinner
Welcome to the Dad Feelings Spinner, a fun and interactive tool designed for dads to check in with their mental health and share proud dad moments! This animated spinning wheel is perfect for the Dad Tip Tuesday TikTok series, encouraging dads to reflect on their emotions and engage with the community. Built with HTML, CSS, and JavaScript, it’s Notion-ready and optimized for vibrant, professional visuals.
Features

Interactive Wheel: Spin to land on feelings like "Proud," "Stressed," "Joyful," "Tired," or "Grateful."
Animated Design: Includes confetti effects, smooth spin transitions, and a game-show-style tick sound.
Dad-Themed: Tailored for dads with bold colors, Poppins font, and TikTok-friendly prompts (e.g., "#ProudDadMoments").
Notion-Compatible: Easily embed in your Notion workspace for content planning or public sharing.
TikTok-Ready: Encourages duets, stitches, and comments to boost engagement.

Demo
[Insert hosted URL after deployment, e.g., https://yourusername.github.io/dad-feelings-spinner/]
Getting Started
Prerequisites

A GitHub account (free).
A Notion account (free tier works).
Optional: A TikTok account to integrate with your Dad Tip Tuesday series.

Installation

Clone or Download the Repository:
git clone https://github.com/yourusername/dad-feelings-spinner.git

Or download the ZIP file from GitHub.

File Structure:

dad_feelings_spinner.html: The main HTML file containing the spinner code.
No external dependencies beyond CDNs (JSConfetti, Google Fonts).


Host the Spinner:

GitHub Pages (Recommended):
Push the repository to GitHub.
Go to the repository’s Settings > Pages.
Set the source to the main branch and / (root) folder.
Save, and get your URL (e.g., https://yourusername.github.io/dad-feelings-spinner/).


Alternative: Netlify:
Sign up for a free Netlify account.
Drag and drop the dad_feelings_spinner.html file into Netlify’s dashboard.
Deploy to get a public URL (e.g., https://your-netlify-site.netlify.app/).




Embed in Notion:

Open your Notion page (e.g., your Dad Tip Tuesday planner).
Type /embed and select “Embed.”
Paste the hosted URL (from GitHub Pages or Netlify).
Resize the widget to fit (e.g., 400px wide).
Optional: Add a Notion header like “Dad Feelings Spinner 🛠️” for branding.



Usage in TikTok
The Dad Feelings Spinner is designed to boost engagement in your Dad Tip Tuesday series:

Video Idea: Record your screen (using OBS Studio, free) showing the spinner. Spin the wheel, react to the result (e.g., “Proud? My kid’s first soccer goal!”), and add text: “Spin it, dads!” Use a trending TikTok sound.
Hook: “Dads, what’s your vibe today? Spin to find out!”
Call to Action: “Spin the wheel on my Notion page [link in bio] and duet your result! #DadFeelingsSpinner”


Editing Tools (Free):
CapCut: Add text overlays (e.g., “How do YOU feel?”) and auto-subtitles.
Canva: Create a thumbnail with a dad and kid high-fiving.
Veed.io: Generate subtitles for accessibility.


Engagement:
Prompt: “Spin the wheel and comment your feeling! What’s your proudest dad moment?”
Duet Challenge: Ask dads to duet their spin result with a story (e.g., “Landed on ‘Stressed’—here’s my stress tip!”).
Live Session: Host a TikTok Live to spin the wheel and react to dads’ comments.



Customization
To make the spinner your own:

Change Feelings:
Edit the segments array in the <script> section of dad_feelings_spinner.html (e.g., add “Overwhelmed”).
Update the messages object to match with new TikTok prompts.


Add More Segments:
For 6 feelings, adjust CSS angles in the conic-gradient to 60deg (360 / 6).
Update div:nth-child rotations in the CSS (e.g., 0deg, 60deg, 120deg, ...).


Change Colors:
Modify the conic-gradient colors in the CSS (e.g., replace #ef4444 with another hex code).


Extra Animations:
Add a starburst effect by extending the CSS with @keyframes starburst.
Contact me for additional animation code if needed!



Troubleshooting

Spinner Not Loading in Notion: Ensure the hosted URL starts with https://. Test it in a browser first.
Animations Laggy: Reduce the confettiNumber in the JSConfetti script (e.g., from 50 to 30).
TikTok Link Issues: Use a free Super.so account to turn your Notion page into a public website for bio linking.

Contributing
Want to add new features like kid-friendly feelings or more animations? Fork this repository, make changes, and submit a pull request. Let’s make this spinner even more awesome for dads!
License
This project is licensed under the MIT License. Feel free to use and modify for your Dad Tip Tuesday series.
Acknowledgments

Built with love for dads everywhere.
Uses JSConfetti for confetti effects.
Inspired by the Dad Tip Tuesday TikTok series for mental health and proud dad moments.

Contact
Questions or ideas? Reach out on TikTok (@yourusername) or submit feedback via a Google Form linked in your TikTok bio.
Spin it, share it, and let’s keep the dad community strong! #DadFeelingsSpinner
