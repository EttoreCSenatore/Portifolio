# Ettore's LCARS Personal Portfolio

Welcome to my personal portfolio! This project is a fully responsive, multi-page web application designed with an immersive **Star Trek LCARS** (Library Computer Access/Retrieval System) user interface.

It serves as a creative demonstration of my full-stack development journey, past missions (work experience), and active communication channels.

## 🚀 Features

- **Authentic LCARS Interface:** Built using the "Nemesis Blue" LCARS CSS framework with custom modifications for an authentic sci-fi aesthetic.
- **Ambient Audio & SFX:** Features an endless loop of ambient TNG Bridge noise and interactive LCARS beep sound effects upon navigation.
- **Responsive Layouts:** Utilizes an "Ultra" layout for the homepage and a "Standard" data-cascade layout for the sub-pages, fully responsive across desktop and mobile devices.
- **Optimized Architecture:** Built with clean vanilla HTML, CSS, and JavaScript following strict asset management best practices.

## 📂 Project Structure

```text
Portifolio/
├── index.html         # Homepage (Ultra Layout)
├── projects.html      # Projects / Work Demonstrations
├── missions.html      # Captain's Log (Experience & Education)
├── comms.html         # Transmission Channels (Contact Info)
│
├── assets/
│   ├── audio/         # Interface SFX and ambient background audio
│   ├── fonts/         # Custom Antonio web fonts
│   └── images/        # Profile pictures and logos
│
├── css/
│   └── nemesis-blue.css # Core styling and LCARS grid systems
│
└── js/
    └── lcars.js       # Audio routing, UI interactions, and scroll handling
```

## 🛠️ How to Run Locally

Since this project uses modern web features (and to satisfy browser auto-play policies for the ambient audio), it is highly recommended to run this portfolio via a local web server rather than opening the HTML files directly.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EttoreCSenatore/Portifolio.git
   cd Portifolio
   ```

2. **Start a local development server:**
   If you have VS Code, simply install the **Live Server** extension and click "Go Live" on `index.html`.

   Alternatively, if you have Python installed, you can serve the directory from your terminal:
   ```bash
   python -m http.server 5500
   ```

3. **Open hailing frequencies:**
   Navigate your browser to `http://localhost:5500` (or whatever port your server provides) and interact with the screen to initialize the ambient audio.

## 👨‍💻 About the Author

**Ettore Ciambra Senatore**  
*Full Stack Developer going where no developer has gone before!!!*

- **GitHub:** [EttoreCSenatore](https://github.com/EttoreCSenatore)
- **LinkedIn:** [ettoresenatore](https://www.linkedin.com/in/ettoresenatore/)

---
*LCARS Inspired Website Template originally by www.TheLCARS.com*
