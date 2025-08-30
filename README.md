# iPod Mini

A React-based iPod Mini simulator with music playback, coverflow, games, and customizable themes.

## Features
- iPod-like UI and navigation
- Play/pause/next/previous for songs
- Coverflow and games sections
- Change wallpapers and orientation
- Light/Dark theme toggle
- Responsive design

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- npm

### Installation
```bash
npm install
```

### Running the App
```bash
npm start
```

The app will run at `http://localhost:3000` by default.

### Build for Production
```bash
npm run build
```

## Project Structure
```
public/
	index.html
src/
	assets/
		css/
		images/
		songs/
	components/
		stateful/
			App.js
		stateless/
			Ipod.js
			Menu.js
			Display.js
			Controller.js
			Allsongs.js
	index.js
```

## Deployment
This project can be deployed to GitHub Pages using:
```bash
npm run deploy
```

## License
MIT

---

Made with ❤️ by Deep-Dubey
