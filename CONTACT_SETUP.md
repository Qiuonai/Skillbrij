# Contact Form Setup Instructions

## Email Configuration

To enable the contact form email functionality, you need to set up the following environment variables in your Cosmic Dashboard:

### Required Environment Variables

1. **EMAIL_USER** - Your email address (e.g., your-email@gmail.com)
2. **EMAIL_PASS** - Your email app password (for Gmail, generate an app password)
3. **ADMIN_EMAIL** - Email address where contact form submissions will be sent

### Gmail Setup (Recommended)

1. Enable 2-factor authentication on your Gmail account
2. Generate an app password:
   - Go to Google Account settings
   - Security → 2-Step Verification → App passwords
   - Generate a password for "Mail"
3. Use this app password as EMAIL_PASS

### Environment Variables Example

```
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-16-character-app-password
ADMIN_EMAIL=admin@skillbridge.org
```

## Features

- **Interactive Contact Form** - Fully functional form with validation
- **Email Notifications** - Sends emails to both admin and form submitter
- **Success/Error Feedback** - Real-time status updates
- **Responsive Design** - Works on all device sizes
- **Accessibility** - Proper form labels and ARIA attributes

## Usage

The contact form is available on:
- Main page: `/` (integrated in the contact section)
- Dedicated contact page: `/contact`

The form includes fields for:
- Full Name
- Email Address
- Subject
- Message

Both the admin and the person submitting the form will receive confirmation emails.