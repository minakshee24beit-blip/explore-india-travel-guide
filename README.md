# 🌍 Explore India – Travel Guide Website

Explore India is a simple, responsive travel guide website that helps travellers discover India's destinations, history, culture, food and experiences. The site is tracked with **Google Analytics 4 (GA4)** to monitor visitors and engagement.

**🔗 Live Demo:** https://explore-india-travel-guide1.vercel.app

---

## 📸 Screenshots

| Homepage | Destinations |
|---|---|
| ![Homepage](home.png) | ![Destinations](destination.png) |

| GA4 Realtime Overview | Web Stream Details |
|---|---|
| ![GA4 Realtime](ss2.png) | ![Web Stream](ss4.png) |

---

## ✨ Features

- Hero section with a destination search box
- **Popular Destinations:** Goa, Kerala, Jaipur, Agra, Manali and Kashmir
- **Travel Tips:** Plan Ahead, Pack Smart and Travel Safely
- About section and Contact form
- Responsive layout with smooth in-page navigation (Home, Destinations, Travel Tips, About, Contact)
- Google Analytics 4 tracking

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| HTML, CSS, JavaScript | Website structure, styling and behaviour |
| Emergent AI | Website creation |
| GitHub | Source code hosting |
| Vercel | Deployment and hosting |
| Google Analytics 4 | Website analytics |

---

## 📁 Project Structure

```
explore-india-travel-guide/
├── index.html      # Complete website (HTML, CSS, JS and GA4 tag)
└── README.md       # Project documentation
```

---

## 🚀 Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/minakshee24beit-blip/explore-india-travel-guide.git
   ```
2. Open the folder and double-click `index.html` to view it in your browser.

No installation or build step is needed.

---

## ☁️ Deployment (Vercel)

1. Push the project to GitHub.
2. Sign in to [Vercel](https://vercel.com) and click **Add New → Project**.
3. Import the `explore-india-travel-guide` repository.
4. Click **Deploy**. Vercel gives you a live URL.

---

## 📊 Google Analytics 4 Setup

1. Create a GA4 property and a **Web data stream** using the Vercel URL.
2. Copy the **Measurement ID** (`G-4LZY6GEJLH`).
3. Paste the Google tag inside the `<head>` of `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-4LZY6GEJLH"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-4LZY6GEJLH');
</script>
```

4. Redeploy the site, open it, and check **Reports → Realtime** in GA4 to confirm visits are recorded.

### Key metrics to monitor

| Metric | Meaning |
|---|---|
| Active Users | People currently on, or interacting with, the site |
| Views | Total pages viewed |
| Sessions | Groups of interactions by a user in a time period |
| Engagement | How actively users interact with the site |
| Traffic Sources | Where visitors come from (Direct, Search, Social, Referral) |

---

## 🔮 Future Improvements

- Working destination search
- Individual pages for each destination
- Connect the contact form to a backend or email service
- Add more destinations and travel guides

---

## 👤 Author

**Minakshee Yadav**
Internship Task: *Website Analytics Setup and Monitoring*
