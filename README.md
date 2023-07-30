# Messenger Project

Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher 프로젝트🎖

- **반드시 아래 Setup과 Development 부분을 읽어보세요.**
- 문의는 id4720@gmail.com

## Setup (사전 설치)

Install dependencies

```sh
npm install
```

Setup .env file

```sh
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

## Development (작업 방법)

Setup Prisma

```sh
npx prisma db push
```

Start the app

```sh
npm run dev
# Visit http://localhost:3000 from your browser (Chrome)
```



배포 사이트
1. [MESSENGER](https://messenger-1xim6hp5p-seungchaelee.vercel.app/)
