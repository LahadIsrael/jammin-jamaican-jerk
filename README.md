<!-- Jammin Jamaican Jerk!

Why did I build this site? The purposes of building this site is to go first hand real world experience. The client was in need of a website for his business and I needed the experience, so he agreed to let me create the website for him.

Goal? To provide the client with a sleek, fast, and interactive website.

Bugs fixed:
#1. Ran into an issue to where the video was not playing when loading the website. 
FIX: Identified that the file path was incorrect. The video file was stored within video and images subdirectory, but the src attribute was looking in the root directory. Updated path to video and images/1000008147.mp4 and added the muted attribute to satisfy browser autoplay req and per client req to remove bg noise. 

#2. Issue to where browser was not detecting image even when the image is in the correct folder.
FIX: Simplified file name from long interger strings to basic character strings. EX: From 1000008742.jpg to test.jpg

#3. Git commit rejected due to missing user identity.
FIX: Configured global Git user identity (email and name) to allow for authenticated version control commits.

#4. Issue with git push due to 'origin' not appearing to be a git repository.
FIX: Added the remote address from my Github repo within the terminal

Features implemented:

#1. Implemented cash app payment button; added the clients username, ensuring that mobile users are directed straight to the client's profile.

#2. Implemented Venmo payment button; utilized Venmo's /u/ URL scheme for deep-linking, ensuring that mobile users are directed straight to the client's profile within the native app for fast results

#3. Implemented Zelle payment button; assigned a modal to allow pop up for the QR code.
-->