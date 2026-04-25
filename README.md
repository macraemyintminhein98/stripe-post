# Stripe Post

Stripe Post is an ultra-minimalist micro-blogging platform where users pay $1 to publish a short, anonymous, and ephemeral thought. Posts are visible for 24 hours and then disappear. No accounts, no commitments - just instant gratification for sharing a fleeting message.

## Features:
- **Anonymous Posting**: Share thoughts without creating an identity.
- **Ephemeral Content**: Posts self-destruct after 24 hours.
- **Stripe Payments**: Simple, secure $1 payment per post.
- **Ultra-Minimalist UI**: Focus on publishing and viewing.

## How to Use:
1. Enter your thought in the text area.
2. Click 'Publish Anonymously'.
3. Complete the $1 payment via Stripe.
4. Your thought appears instantly and is visible to everyone for 24 hours.

## Development Setup (Conceptual):
- **Frontend**: HTML, Tailwind CSS, JavaScript (Stripe.js).
- **Backend**: (e.g., Flask, Node.js/Express with Vercel/similar deployment).
- **Database**: Simple ephemeral storage (e.g., SQLite, JSON file, or in-memory cache with persistence).
- **Payment**: Stripe Checkout for session creation and payment handling.

This `index.html` file provides the basic static frontend. A backend would be required to handle Stripe checkout session creation, post storage, and retrieval with expiration logic.