<!-- Jammin Jamaican Jerk!

Why did I build this site? The purposes of building this site is to go first hand real world experience. The client was in need of a website for his business and I needed the experience, so he agreed to let me create the website for him.

Goal? To provide the client with a sleek, fast, and interactive website.

Challenges faced:

#1. Ran into an issue to where the video was not playing when loading the website.

Fix: Identified that the file path was incorrect. The video file was stored within video and images subdirectory, but the src attribute was looking in the root directory. Updated path to video and images/1000008147.mp4 and added the muted attribute to satisfy browser autoplay req and per client req to remove bg noise. 

Features implemented:

#1. Implemented cash app payment button; added the clients username, ensuring that mobile users are directed straight to the client's profile.

#2. Implemented Venmo payment button; utilized Venmo's /u/ URL scheme for deep-linking, ensuring that mobile users are directed straight to the client's profile within the native app for fast results

#3. Implemented Zelle payment button; assigned a modal to allow pop up for the QR code.
-->