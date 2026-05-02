# Claimly - Ad-Supported Settlement Discovery Platform

A fully functional web application that helps users discover active lawsuits and settlements they may qualify for, completely free.

## Features

✅ **Settlement Discovery**
- Browse active lawsuits and class action settlements
- Filter by category (Privacy, Auto, Finance, Health, Consumer Products)
- Search by company or product name
- View potential payouts and deadlines

✅ **Eligibility Checker**
- Interactive modal with quick qualification questions
- Instant eligibility assessment
- Direct links to official claim forms

✅ **My Claims Dashboard**
- Save claims you're interested in
- Persistent storage using browser localStorage
- Track claims across sessions

✅ **Ad-Supported Model**
- 100% free for users
- Display advertising
- Sponsored settlement listings
- Law firm lead generation partnerships

✅ **Responsive Design**
- Mobile-friendly layout
- Tailwind CSS styling
- Smooth animations and transitions

## Getting Started

### Quick Start (Static HTML)

1. Open `index.html` directly in a web browser, or
2. Serve locally with Python:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
3. Open `http://localhost:8000` in your browser

### Using a Local Server (Recommended)

For development and testing, use any HTTP server:

**Node.js (http-server)**
```bash
npm install -g http-server
http-server .
```

**Python**
```bash
python -m http.server 8000
```

**Live Server in VS Code**
- Install "Live Server" extension
- Right-click `index.html` → "Open with Live Server"

## Project Structure

```
claimly/
├── index.html              # Main application file (all-in-one)
├── README.md               # This file
└── .github/
    └── copilot-instructions.md  # Development guidelines
```

## How It Works

1. **Discover** - Browse settlements and filter by category
2. **Search** - Find specific settlements by company or product
3. **Check Eligibility** - Answer quick questions to see if you qualify
4. **File Claim** - Get linked to the official claim administrator
5. **Get Paid** - Receive compensation (in the real app)

## Data Persistence

- Submitted claims are saved to browser localStorage
- Data persists between sessions
- Clear browser data to reset claims

## Demo Features

- 6 sample settlements with realistic data
- Interactive eligibility questionnaires
- Category filtering system
- Search functionality
- Ad revenue model explanation

## Legal Notice

This is a demonstration application. In production, it would:
- Connect to a real settlement database
- Verify user eligibility through official channels
- Direct users to licensed attorneys and settlement administrators
- Display genuine advertisements and sponsored content

See footer for full legal disclaimer.

## Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile browsers: Responsive design

## Revenue Model

Claimly generates revenue through:
1. **Display Advertising** - Banner ads in sidebar
2. **Sponsored Listings** - Law firms pay to feature their settlements
3. **Lead Generation** - Referral partnerships with credit monitoring and legal marketing services

Users pay nothing. Ever.

## Future Enhancements

- User authentication and accounts
- Real settlement API integration
- Email notifications for new eligible settlements
- PDF claim form generation
- Payment tracking dashboard
- Mobile app version
- Multi-language support

## License

Created for demonstration purposes in 2026.

---

**Questions?** This is a prototype built to showcase the Claimly platform concept.
