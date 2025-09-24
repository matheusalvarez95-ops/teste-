marketplace-tiktok-viral/
├─ README.md
├─ package.json
├─ .env.example
├─ next.config.js
├─ postcss.config.js
├─ tailwind.config.js
├─ prisma/ (opcional - ou migrations SQL)
│ └─ schema.prisma
├─ db/
│ └─ init.sql
├─ pages/
│ ├─ index.js
│ ├─ _app.js
│ ├─ product/[id].js
│ ├─ cart.js
│ ├─ checkout.js
│ └─ api/
│ ├─ products.js
│ ├─ checkout/create-session.js
│ ├─ webhooks/stripe.js
│ └─ webhooks/mercadopago.js
├─ components/
│ ├─ Header.js
│ ├─ Footer.js
│ ├─ ProductCard.js
│ └─ ProductDetail.js
├─ lib/
│ ├─ db.js
│ ├─ stripe.js
│ └─ fulfillmentQueue.js
├─ worker/
│ └─ fulfillmentWorker.js
├─ scripts/
│ └─ syncTikTokProducts.js
└─ public/
└─ (assets)
