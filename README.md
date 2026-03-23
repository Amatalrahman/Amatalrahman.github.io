# Portfolio

## Folder Structure

```
portfolio/
│
├── index.html                               ← Your entire website
│
├── assets/
│   └── images/
│       ├── profile/
│       │   └── photo.jpg                    ← Your profile photo here
│       │
│       └── projects/
│           ├── p01-signal-viewer/
│           ├── p02-brain-tumor-classifier/
│           ├── p03-artery-stenosis-cfd/
│           ├── p04-anatomy-puzzle/
│           ├── p05-medical-image-viewer/
│           ├── p06-football-tracking/
│           ├── p07-ecg-dtw/
│           ├── p08-perisylvian-fmri/
│           ├── p09-bio-flow-regime/
│           ├── p10-covid-dashboard/
│           ├── p11-car-price-ai/
│           ├── p12-endoscope-room/
│           ├── p13-neuron-model/
│           ├── p14-biological-scaffold/
│           ├── p15-medical-image-classification/
│           ├── p16-brain-tumor-app/
│           └── p17-parkinsons-voice/
└── README.md
```

---

## Step 1 — Add Profile Photo

1. Copy your photo into `assets/images/profile/`
2. Open `index.html`, find: `const PROFILE_PHOTO = '';`
3. Change to: `const PROFILE_PHOTO = 'assets/images/profile/photo.jpg';`

---

## Step 2 — Add Project Images

Copy images into the matching subfolder, then edit `MEDIA_DATA` in `index.html`:

```js
10: [
  {type: 'img', src: 'assets/images/projects/p10-covid-dashboard/screenshot.png'},
  {type: 'img', src: 'assets/images/projects/p10-covid-dashboard/map.jpg'},
  {type: 'yt',  vid: 'YouTubeVideoID'},
],
```

Supported image formats: .jpg .jpeg .png .webp .gif

---

## Step 3 — Add YouTube Videos

Get the video ID from the YouTube URL (the part after `?v=`):
`https://youtube.com/watch?v=` **dQw4w9WgXcQ**

```js
{type: 'yt', vid: 'dQw4w9WgXcQ'}
```

---

## Step 4 — Deploy to Netlify (Free, 1 minute)

1. Go to https://app.netlify.com/drop
2. Drag the entire **`portfolio` folder** onto the page
3. Get a live URL instantly

> Always drag the whole **folder**, never just `index.html` alone.

---

## Step 5 — Deploy to GitHub Pages

1. New repository → `portfolio` → Public
2. Upload all files including the `assets/` folder
3. Settings → Pages → main branch → / (root) → Save
4. URL: `https://yourusername.github.io/portfolio`

---

## Project Folder Reference

| # | Folder | Project Name |
|---|--------|--------------|
| 1 | p01-signal-viewer | Signal Viewer Platform |
| 2 | p02-brain-tumor-classifier | Brain Tumor Classifier |
| 3 | p03-artery-stenosis-cfd | Artery Stenosis CFD |
| 4 | p04-anatomy-puzzle | 3D Anatomy Puzzle Game |
| 5 | p05-medical-image-viewer | Multi-Planar Image Viewer |
| 6 | p06-football-tracking | Football Tracking + Heatmap |
| 7 | p07-ecg-dtw | ECG Classification DTW |
| 8 | p08-perisylvian-fmri | Perisylvian Network fMRI |
| 9 | p09-bio-flow-regime | Bio-Flow Regime Analyzer |
| 10 | p10-covid-dashboard | COVID-19 Dashboard |
| 11 | p11-car-price-ai | AutoValuate Car Price AI |
| 12 | p12-endoscope-room | Endoscope Room 3D Model |
| 13 | p13-neuron-model | Neuron 3D Model |
| 14 | p14-biological-scaffold | Biological Scaffold 3D |
| 15 | p15-medical-image-classification | Medical Image Classification |
| 16 | p16-brain-tumor-app | Brain Tumor App |
| 17 | p17-parkinsons-voice | Parkinson's Voice Telemonitoring |
