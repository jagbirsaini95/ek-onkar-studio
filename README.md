# Ek Onkar Visualizer Studio

A cinematic, browser-only music visualizer that turns any track into a vertical, audio-reactive video with glowing motion, immersive backgrounds, and lyric-style subtitles. Built for creators who want a sacred, modern visual identity without needing a backend, a build step, or a complicated editing suite.

Open [Ek onkar.html](Ek%20onkar.html) in a browser and you have a fully working studio: craft the look, choose the music, add subtitles, and export a downloadable WebM video in minutes.

## Why this project feels special

Ek Onkar Visualizer Studio blends spiritual atmosphere with modern production tools. The experience is intentionally expressive: layered light, motion, soft gradients, and responsive audio pulses all work together to create a visual story around the sound rather than a generic waveform renderer.

This project is designed for:

- devotional and ambient music visuals
- song teasers and reels with a portrait format
- lyric-led performance visuals
- quick audio-to-video experiments with no cloud pipeline

## Core features

### Visualizer design

- Ready-made presets like Sacred Glow, Pulse, Minimal, Spectrum, Dream, Classic, Lightning, Falling Balls, and Soft Bounce
- Multiple ball shapes and waveform styles
- Tunable reactivity controls for bass, treble, beat intensity, and overall sensitivity
- Customizable glow, particles, trails, rings, and background pulses

### Color and atmosphere

- Six curated palettes: Golden, Rose, Ocean, Violet, Forest, and Ember
- Full primary and secondary color control
- Nine built-in backdrop themes with animated previews
- Custom background upload support with drag-and-drop
- Motion options including Slow Zoom, Ken Burns, Float, Pan, Pulse, Parallax, and Static

### Subtitles and text layers

- Add title and tagline text directly in the studio
- Auto-transcribe audio with the Gemini API in Punjabi, Hindi, English, or auto-detect
- Subtitle styles including Karaoke, Clean, Glow, Gold, Neon, and Outline
- Fine control for size, placement, color, highlight color, glow, and words-per-line
- Live subtitle preview while styling the look

### Recording and export

- Output quality presets for 720p and 1080p at 30/60 fps
- Live canvas + audio capture through the browser MediaRecorder API
- Pause, resume, and stop controls during recording
- In-app preview before download
- Export as a `.webm` file directly from the browser

### Experience and workflow

- Responsive setup and preview layout
- Persistent design settings saved in `localStorage`
- No backend processing for the visualizer itself
- Only transcript requests are sent externally when you explicitly trigger them

## Quick start

1. Open [Ek onkar.html](Ek%20onkar.html) in a modern browser such as Chrome or Edge.
2. Choose a visualizer preset, palette, background motion, and subtitle style.
3. Continue to the audio stage, select a track, and optionally generate subtitle text.
4. Press Start Recording, let the track play, and stop when complete.
5. Preview the finished result and download the video.

## Deployment

This is a static site. The configuration in [vercel.json](vercel.json) rewrites `/` to [Ek onkar.html](Ek%20onkar.html), so it can be deployed on Vercel or any static host without extra build steps.

## Requirements

- A modern browser with Web Audio API and MediaRecorder support
- An optional Gemini API key if you want automatic subtitle transcription

## Notes

This project is intentionally lightweight and portable: everything essential lives in a single HTML page, making it easy to open, tweak, and deploy in environments where a full app setup would be overkill.
