# Privacy Policy for Swagger UI Enhancement

**Last Updated: October 21, 2025**

## Overview

Swagger UI Enhancement ("the Extension") is committed to protecting your privacy. This privacy policy explains how the Extension handles data.

## Data Collection and Storage

### What Data is Stored

The Extension stores the following data **locally on your device only**:

1. **JWT Tokens**: Authentication tokens you manually save with custom names
2. **Favorite APIs**: API endpoints you mark as favorites
3. **Request Bodies**: API request body templates you save per endpoint
4. **User Preferences**: 
   - Table of Contents width and collapse state
   - Tour completion status
   - First-time user flag
5. **Enabled Domains**: List of domains where you manually activated the extension

### Where Data is Stored

All data is stored locally in your browser using:
- `localStorage` for tokens, favorites, request bodies, and preferences
- `chrome.storage.local` for enabled domains list

**No data is ever transmitted to external servers or third parties.**

## Data Transmission

### What We DO NOT Do

- ❌ We do NOT collect any personal information
- ❌ We do NOT transmit any data to remote servers
- ❌ We do NOT share data with third parties
- ❌ We do NOT use analytics or tracking
- ❌ We do NOT sell or monetize your data
- ❌ We do NOT access data from other websites

### External Resources

The Extension loads Font Awesome icons from a CDN (https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css) for UI styling purposes only. This is a CSS stylesheet and does not execute JavaScript or collect any data.

## Permissions Usage

### activeTab
Used only when you click the extension icon to manually activate it on a page. Allows us to check if Swagger UI exists and inject enhancement features.

### scripting
Used to inject CSS and JavaScript files into Swagger UI pages to provide enhancement features. All code is bundled with the extension.

### storage
Used to save your tokens, favorites, request bodies, preferences, and enabled domains locally in your browser.

### Host Permissions
Used to make extension resources accessible on Swagger UI pages. The extension only activates on pages containing Swagger UI elements.

## Data Control

### Your Rights

You have complete control over your data:

- **View Data**: All data is stored in your browser's localStorage and can be viewed in Developer Tools
- **Delete Data**: Clear extension data by:
  - Removing individual tokens, favorites, or request bodies through the extension UI
  - Clearing browser data for the extension
  - Uninstalling the extension (removes all stored data)
- **Export Data**: You can manually export data from localStorage if needed

### Data Retention

Data is retained locally until you:
- Manually delete it through the extension
- Clear your browser data
- Uninstall the extension

## Security

- All data remains on your device
- No data transmission means no interception risk
- No server-side storage means no data breach risk
- You control all data through browser settings

## Children's Privacy

The Extension does not knowingly collect any information from children under 13. The Extension is designed for software developers and API documentation users.

## Changes to Privacy Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last Updated" date. Continued use of the Extension after changes constitutes acceptance of the updated policy.

## Open Source

This extension is open source. You can review the complete source code to verify our privacy practices:
[GitHub Repository URL - Add your repo URL here]

## Contact

If you have questions about this privacy policy or the Extension's privacy practices, please:
- Open an issue on our GitHub repository
- Contact: [Your email or contact method]

## Compliance

This Extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR) principles
- California Consumer Privacy Act (CCPA) principles

## Summary

**In Plain English:**
- Everything stays on your computer
- We don't collect, transmit, or sell anything
- You control all your data
- We don't track you
- We don't use analytics
- Your privacy is 100% protected

---

**By using Swagger UI Enhancement, you acknowledge that you have read and understood this Privacy Policy.**
