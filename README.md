# 🏃 MobiTrack — Lower Body Mobility Trainer

A browser-based AI exercise tracker using MediaPipe Pose. No installation needed — just open in a browser.

**[▶ Launch App](https://YOUR_USERNAME.github.io/mobitrack)**

---

## Exercises Tracked
| # | Exercise | Reps | Scoring |
|---|---|---|---|
| 1 | 🔄 Hip Circles | 10 each side | Circle size |
| 2 | 🦵 Quad Stretch | 20s hold each leg | Knee bend depth |
| 3 | 🏋️ Mini Squats | 12 reps | Depth + knee alignment |
| 4 | 👟 Heel Raises | 15 reps | Lift height |

## Features
- ✅ Real-time pose detection in the browser (MediaPipe JS)
- ✅ Rep counting with form quality scoring (0–10 per rep)
- ✅ Live coaching cues for incomplete or poor movements
- ✅ Exercise routine sidebar with progress tracking
- ✅ Hold timer for quad stretch
- ✅ Session summary on completion

## How to Deploy (GitHub Pages)

1. Create a new GitHub repository (e.g. `mobitrack`)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages → Source → main branch / root**
4. Your app is live at `https://YOUR_USERNAME.github.io/mobitrack`

## How to Run Locally
Just open `index.html` in Chrome or Edge. No server needed.

> ⚠️ Camera access requires HTTPS or localhost. GitHub Pages provides HTTPS automatically.

## Tips for Best Results
- Stand **2–3 metres** from the camera
- Ensure **good lighting** — face a window or lamp
- Wear **fitted clothing** for accurate landmark detection
- Camera should see your **full body**
- Use **Chrome or Edge** for best MediaPipe performance
