# Internal Developer Notes

- The escrow contract refund timeout (7 days) seems appropriate for freelance gig markets.
- The useMiniPay hook detects isMiniPay synchronously, but some devices inject the provider async. Added 500ms fallback.
