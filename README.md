# CoastSafe 🌊

Admin dashboard for real-time coastal hazard monitoring and operations.

## Highlights ✨

- 🗺️ Live map with reports and zones
- ✅ Admin verification workflow
- 🧭 Geofenced monitoring tools
- ☁️ Supabase-backed data sync

## Tech stack 🧰

- React 19 + TypeScript
- Vite
- Material UI
- Leaflet + Google Maps
- Supabase
- Socket.io client

## Quick start 🚀

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Env setup 🔐

Create `.env.local` in this folder:

```env
VITE_GOOGLE_MAPS_API_KEY=your-google-maps-api-key
VITE_SUPABASE_URL=https://your-project.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key
```

## Docs 📚

- [QUICK_START.txt](QUICK_START.txt)
- [GEOFENCING_README.md](GEOFENCING_README.md)
- [GEOFENCING_SYSTEM.md](GEOFENCING_SYSTEM.md)
- [LANDMARK_GUIDE.md](LANDMARK_GUIDE.md)
- [LEAFLET_DRAW_SETUP.md](LEAFLET_DRAW_SETUP.md)
