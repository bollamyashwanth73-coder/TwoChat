# TwoChat Direct

A two-person private chat app that needs **no Supabase, SQL, API key, or `.env` file**.

It uses WebRTC through PeerJS for the connection. One person creates a room and shares the 6-character code; the other joins with that code. Messages and wallpaper changes are sent directly between the two browsers.

## Run

```powershell
npm install
npm run dev
```

Open the Vite URL shown in the terminal.
