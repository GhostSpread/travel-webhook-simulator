# Travel Webhook Simulator

Simulate webhook responses for travel booking platforms to test integrations and event handling.

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"booking_id":"BK123456","event":"booking_confirmed","timestamp":"2025-04-24T14:01:21Z"}'
