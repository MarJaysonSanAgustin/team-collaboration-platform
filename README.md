# Team Collaboration Platform: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL

This is a repository for a discord-like team collaboration platform using Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL, etc.

Features:

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

### Demo:

[Click this demo link 🡥](https://discord-clone-production-41b9.up.railway.app/)

### Screenshots

Chat UI
![Channels](screenshots/channels.png)

Video/Audio Channels
![Video Channels](screenshots/video-channels.png)

System/Light/Dark Mode
![Light and Dark Mode](screenshots/light.png)

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/MarJaysonSanAgustin/discord-clone
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `dev`   | Starts a development instance of the app |

### Learning Material

- [@CodeWithAntonio](https://www.youtube.com/@codewithantonio)
- [Video tutorial](https://www.youtube.com/watch?v=ZbX4Ok9YX94)
