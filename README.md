# Project Title
ISATMA Adaptive Music Controller 

---

## 📌 Features

This is an accessibility-focused instrument designed for people with physical disabilities (including quadriplegia). Instead of using hands, you control it with your head — specifically by moving your nose in front of a webcam to play music. The idea here is that you have an extension sort of like a wand that you can use moving your forehead.  With feedback and discussion maybe it could be a useful tool and maybe there could be ways to configure it. Thanks for taking time to check out these explorations.
The 3D Scene
The main canvas shows a simple 3D character — a glowing wireframe skull with a yellow stick coming out of its mouth, representing a mouth stick (a real assistive device used by people with limited hand mobility). The tip of that stick is a small red ball, and that's your "pointer." As you move your head, the skull tilts and the red tip moves across the screen.
The Note Pads (The Arc)
Arranged in a curved arc across the screen are colored rectangular pads — one for each note in your chosen scale, spread across a rainbow of colors. When the red wand tip touches a pad, that note plays. Move your nose left or right to select different notes; dip down to trigger them. You can adjust how wide the arc spans and how far out it sits using sliders in the sidebar.
Two Ways to Make Sound
Sound mode — plays audio directly in the browser using Tone.js, with a choice of synth types (sine, sawtooth, piano-like, etc.), reverb, and volume controls.
MIDI mode — sends MIDI signals out via the Web MIDI API to a virtual cable, so notes go straight into your DAW (Ableton, Reaper, etc.) and play through any instrument plugin.
The Sidebar
A collapsible panel on the left with sections for: Scale & Mode (12 scales to choose from), Webcam preview, Arc configuration, Sound Engine settings, MIDI settings, and a Preset system where you can save and reload your favorite configurations as named presets — and even download them as a JSON file.
The MIDI Monitor
A small floating panel in the top-right that logs every note being sent in real time — with timestamps and note names. You can copy or email the log directly from the panel.
The Countdown
When you click Activate, a 5-second countdown gives you time to position yourself and look straight ahead. That moment sets your "center point" — everything is relative to where you were looking at zero.

## 🚀 Getting Started

### Prerequisites
List anything users need before starting:
- Browser

### Installation
Steps to install:

