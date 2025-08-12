# DarkModeSports (DMS)

![Vercel](https://therealsujitk-vercel-badge.vercel.app/?app=darkmodesports)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

`// Null spoilers. All suspense.`

Tired of spoiler exceptions crashing your day? DarkModeSports provides a clean, sandboxed environment to view your favorite sports schedules. We keep the final results hidden as private variables until you're ready to execute the peek command.

This project is built for the modern, tech-savvy sports fan who records games or watches on-demand and demands a spoiler-free experience.

## ✨ Core Features

- **Spoiler-Free by Default:** Scores and results are always hidden on load.
- **"Peek" at Scores:** Tap and hold a game to temporarily reveal the score.
- **Dynamic Date Selection:** Navigate between days to see past or future schedules.
- **Live Data Reload:** Re-fetch the day's data to get the latest updates.
- **Sport Filtering:** Toggle which sports you want to see on the schedule.
- **Installable PWA:** Add DMS to your phone's home screen for an app-like experience with offline support.
- **Dev-Themed UI:** A minimalist, code-editor aesthetic featuring monospaced fonts and syntax-highlighting-inspired colors.

## 🚀 Tech Stack

- **Framework:** [Astro.js](https://astro.build/) (in SSR mode)
- **UI Library:** [React](https://reactjs.org/) (via Astro Islands)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) + [DaisyUI](https://daisyui.com/)
- **Deployment:** [Vercel](https://vercel.com/) / [Netlify](https://www.netlify.com/)

## 🛠️ Local Development

To get a local copy up and running, follow these simple steps.

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

    ```sh
    git clone [https://github.com/your-username/darkmodesports.git](https://github.com/your-username/darkmodesports.git)
    ```

2. Navigate to the project directory:

    ```sh
    cd darkmodesports
    ```

3. Install NPM packages:

    ```sh
    npm install
    ```

4. Set up your environment variables. Create a new file named `.env` in the root of the project and add your API key.

    ```env
    # .env
    THESPORTSDB_API_KEY=YOUR_API_KEY_HERE
    ```

5. Run the development server:

    ```sh
    npm run dev
    ```

    Your project will be available at `http://localhost:4321`.

## 🗺️ Roadmap

The backlog contains several epics for future development, including:

- **User Customization:** Allow users to save their favorite sports and default view preferences.
- **Native App Distribution:** Package the app using **Capacitor** for submission to the Apple App Store and Google Play Store.

## 📄 License

This project is distributed under the MIT License. See `LICENSE.txt` for more information.
