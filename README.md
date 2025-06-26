# Quotifyyyy

> **Note:** Quotifyyyy is still in development stages. Features and design may change.

Quotifyyyy is a modern web application for discovering, sharing, and managing motivational quotes. It features user login, favorites, quote submission, sharing, feedback, and a full admin panel for moderation—all with a beautiful, responsive design.

## Features
- User login (local, per device)
- Browse, favorite, and navigate quotes (with Previous/Next buttons)
- Mark quotes as favorites and filter to show only favorites
- Share quotes (copy, Twitter, Instagram Story)
- Generate a shareable image of any quote
- Submit your own quotes for admin approval
- Submit feedback to the admin
- Switch between light and dark themes
- Fully responsive and mobile-friendly UI
- **Admin panel**: add/edit/remove quotes, moderate user-submitted quotes, review user feedback

## Files
- `index.html`: Main user interface for browsing, submitting, and sharing quotes
- `admin.html`: Admin panel for managing quotes, moderation, and feedback
- `css/styles.css`: Styles for both user and admin panels

## How to Use
1. **Open `index.html` in your web browser.**
   - Log in with any username (stored locally)
   - Browse and interact with quotes using the navigation and action buttons
   - Submit your own quotes or feedback for admin review
2. **Open `admin.html` for admin features.**
   - Log in with the admin password (default: `admin123`)
   - Add, edit, or remove quotes
   - Approve or reject user-submitted quotes
   - Review and remove user feedback

## Notes
- All data is stored in your browser's localStorage. Quotes, favorites, and feedback are not shared across devices unless a backend is added.
- For cross-device sharing, see the backend setup instructions (not included by default).

## Requirements
- Modern web browser (Chrome, Firefox, Edge, Safari)
- No installation or dependencies required for the frontend—just open the HTML files to get started!
