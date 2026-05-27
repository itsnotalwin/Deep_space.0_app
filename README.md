# ✦ Ephemeral Constellation – A Living, Shared Star Map

An interactive, real‑time constellation where every star is a thought, a wish, or a memory. Stars age naturally, ephemeral stars appear daily with poetic quotes, and all changes sync across everyone who visits.

[Live Demo](https://your-demo-link.com) · [Report Bug](https://github.com/yourusername/ephemeral-constellation/issues)

![Screenshot](screenshot.png)

---

## ✨ Features

- **Dynamic, organic sky** – dense star layers, colour‑shifting nebulae, a slow‑rotating spiral galaxy, and hundreds of flow particles.
- **Permanent stars** – create, edit, and delete stars. Each stores a text note and the creator’s name. Stars age over **real time** (blue → yellow → red), with distinct visuals for young stars, red giants, and white dwarfs.
- **Ephemeral stars** – 2–5 temporary stars appear every day, each with a random lifespan (1 day to 1 month). One **special star** per day gives +1 to your streak when clicked.
- **Constellations** – clusters of 3+ stars are auto‑named with poetic titles; you can rename them by tapping the cluster’s center. No ugly lines – only the name appears when zoomed in.
- **Streak & daily rewards** – a visible streak counter tracks consecutive visits. Daily notifications announce new ephemeral stars.
- **Real‑time sync** – all data lives in Firebase. Every change is instantly shared across all connected devices.
- **Full touch & mouse controls** – pan, zoom, tap to preview, double‑tap to edit, long‑press to follow a star.
- **Bloom & organic motion** – gentle glow post‑processing, and all moving elements drift with Simplex noise for a natural, living feel.

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge).
- (Optional) A Firebase project if you want to host your own instance – the included configuration uses a demo Firebase project that may be rate‑limited. For production, replace the `firebaseConfig` with your own.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ephemeral-constellation.git
