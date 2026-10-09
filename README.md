# MM Living Full E-commerce
Node.js 20+, SQLite, Express, Razorpay.

1. Copy `.env.example` to `.env`.
2. Add Razorpay Test keys and a strong admin password.
3. Run `npm install` then `npm start`.
4. Store: http://localhost:3000
5. Admin: http://localhost:3000/admin

Razorpay secrets stay server-side. Configure the webhook URL `/api/webhooks/razorpay` in Razorpay Dashboard for production. Use HTTPS and production keys before launch.