<!-- Jammin Jamaican Jerk!

Why did I build this site? The purposes of building this site is to go first hand real world experience. The client was in need of a website for his business and I needed the experience, so he agreed to let me create the website for him.

Goal? To provide the client with a sleek, fast, and interactive website.


Local Development Setup (macOS)
This project was migrated from Windows to macOS March 4th, 2026. Followed these steps to set up the environment on a new machine.

1. Prerequisites

Homebrew: The package manager for macOS.
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Git & Github CLI:
brew install git gh

2. Environment Config

Shell PATH: Ensure Homebrew is added to .zprofile:
echo 'eval "$(/opt/homebrew/bin/brew
shellenv)"'>> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

Authentication: Authenticate via the Github CLI:
git auth login

3. Project install
git clone <repo url>
cd project name
-----------------------

Tools used to build website: 
Claude, Qodo