# 🎂 Arpita's 23rd Birthday Surprise Gift Website ✈️

A multi-page birthday surprise gift website crafted for best friend **Arpita Mahapatra**, celebrating her 23rd birthday on **8 October**.

Designed with pure best-friend energy, zero romantic vibes, soft pastel aesthetics, travel & weather motifs, and mobile-first responsiveness.

---

## 🌟 Architecture & Technical Structure
- **Single File (`index.html`):** Fully self-contained HTML5, CSS3, and JavaScript ready to host instantly on GitHub Pages, Vercel, or Netlify.
- **Multi-Page Hash Routing:** Smooth transitions between 7 dedicated page views:
  - `#home`: Opening gift box unwrap & hero welcome
  - `#story`: How we met timeline & Instagram DM chat
  - `#why`: 6 flip cards & unlimited Biryani rain
  - `#arcade`: 3 mobile touch-locked arcade mini games
  - `#journey`: Distance flight boarding pass & travel bucket list
  - `#letter`: Handwritten airmail letter card with staggered reveal
  - `#finale`: Plane ticket, grand surprise modal & celebration fireworks
- **Seamless History & Browser Back Button:** Switching pages updates `window.location.hash`, allowing the browser back and forward buttons to work seamlessly without reloading.
- **Uninterrupted Background Music:** Operatic "Happy Birthday" plays continuously across all page transitions, with a floating 🎵 / 🔇 toggle button and Web Audio API synthesizer fallback.
- **Responsive Navigation:** Fixed bottom tab bar on phones; elegant floating top nav on desktop. Each page also has a chronological "Next Page →" button at the bottom.

---

## 🎮 Arpita's Birthday Arcade
1. **Biryani Catcher 🍛☁️:** Drag plate left & right to catch Biryani (+1) and Cakes (+3) while dodging storm clouds ⛈️ (3 lives, 30s timer, score tiers).
2. **Weather Match ⛅:** 12-card memory matching game featuring 6 weather pairs (☀️ 🌧️ ⛈️ 🌈 ❄️ 🌪️) with move counter and timer.
3. **How Well Do You Know Me? 💬:** 5-question multiple choice bestie quiz with instant feedback and score tiers.

---

## 🚀 Running Locally
Simply open `index.html` directly in any web browser, or launch the lightweight Node server:
```bash
node server.js
```
Then visit `http://localhost:3000/`.

---

## 🌐 Free Hosting via GitHub Pages
1. Push to your repository on GitHub.
2. In the repository, go to **Settings** > **Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**.
4. Select `main` branch and `/ (root)` folder, then click **Save**.
5. Your website will be live at:
   `https://<your-github-username>.github.io/<repo-name>/`
