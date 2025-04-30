# Engine 6.0 Website

A modern, visually striking landing page website for Engine 6.0 Roblox Executor with Stripe payment integration.

## Features

- Three pricing plans: Weekly, Monthly, and Lifetime
- Stripe checkout integration
- Modern UI with animations and microinteractions
- Custom cursor
- Responsive design for all screen sizes

## Setup and Installation

1. Clone this repository
2. Install dependencies:

```bash
npm install
```

3. Start the server:

```bash
npm start
```

The server will run on port 3000 by default (http://localhost:3000).

## Stripe Integration

The website uses Stripe Checkout to process payments. The following plans are available:

- Weekly Plan: $2.50/week
- Monthly Plan: $5.00/month
- Lifetime Plan: $15.00 (one-time payment)

## File Structure

- `index.html` - Main landing page
- `style.css` - CSS styles
- `script.js` - Frontend JavaScript
- `server.js` - Express server for handling Stripe integration
- `success.html` - Success page after payment

## Dependencies

- Express.js - Web server framework
- Stripe - Payment processing
- CORS - Cross-origin resource sharing middleware 