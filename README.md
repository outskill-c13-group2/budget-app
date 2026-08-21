# budget-app

Lovable-synced front end for the AI budget negotiator.

## Boundary

- Consume the versioned fixture contract from `budget-platform`.
- Use Supabase only through its public client/API surface.
- Never include service-role or OpenAI credentials in this repository.

The initial UI may use a copied mock fixture so Track A can build without waiting for backend deployment.
