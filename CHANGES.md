# Recent Changes

## payment-service v2.4.0
- Increased DB connection pool limit from 10 to 50
- Added Stripe fallback gateway integration
- Modified retry logic for failed transactions

## auth-service v1.5.1
- Updated JWT expiry config to 86400s
- Added token refresh endpoint
- Fixed session timeout bug

## order-service v1.8.2
- Added null check in OrderValidator
- Fixed timeout on large cart orders
- Performance improvement on order lookup queries
