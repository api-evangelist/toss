# Toss

Toss is a Korean financial super-app operated by Viva Republica that provides REST APIs for payments, banking, credit scoring, identity verification, and financial services across the Toss ecosystem. The platform supports card payments, virtual accounts, mobile phone billing, bank transfers, and digital wallets (TossPay, KakaoPay, NaverPay, SamsungPay), serving over 30 million registered users across South Korea.

## APIs

- **Toss Payments API** - Core payment processing: create, authorize, retrieve, and cancel payments
- **Toss Pay API** - Legacy digital wallet payment transactions via pay.toss.im
- **Toss Payments Webhooks** - Real-time event notifications for payment lifecycle events
- **Toss Payments Payouts API** - Marketplace seller disbursement

## Developer Resources

- Developer Center: https://docs.tosspayments.com/en
- API Reference: https://docs.tosspayments.com/en/api-guide
- GitHub (Payments): https://github.com/tosspayments
- GitHub (Toss): https://github.com/toss
- Status Page: https://status.tosspayments.com
- Tech Blog: https://toss.tech

## Authentication

Toss Payments uses HTTP Basic Auth with a Base64-encoded secret key. Test keys are prefixed with `test_sk` or `test_gsk`; production keys with `live_sk` or `live_gsk`. Secret keys must only be used server-side.

## Support

- Email: support@tosspayments.com
- Phone: 1544-7772
- Technical Chat: https://techchat.tosspayments.com
