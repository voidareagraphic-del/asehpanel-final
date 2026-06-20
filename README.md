# Aseh Panel

وب‌سایت رسمی آسه پنل — ساخته‌شده با Next.js 14، TypeScript، Tailwind CSS، و Three.js.

## راه‌اندازی

```bash
npm install
npm run dev
```

## متغیرهای محیطی

یک فایل `.env.local` در ریشه پروژه بسازید:

```env
SMTP_HOST=smtp.your-mailserver.com
SMTP_PORT=587
SMTP_SECURE=false
SMTP_USER=your@email.com
SMTP_PASS=your-password
```

## اسکریپت‌ها

| دستور | توضیح |
|---|---|
| `npm run dev` | اجرای محیط توسعه |
| `npm run build` | ساخت نسخه production |
| `npm run start` | اجرای نسخه production |
| `npm run lint` | بررسی کد |

## تکنولوژی‌ها

- [Next.js 14](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Three.js](https://threejs.org/) + [@react-three/fiber](https://github.com/pmndrs/react-three-fiber)
- [Framer Motion](https://www.framer.com/motion/)
- [GSAP](https://greensock.com/gsap/)
