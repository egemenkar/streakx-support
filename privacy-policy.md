# Privacy Policy - StreakX

## Overview

StreakX is a Chrome extension that helps you track YOUR personal daily activity on X (formerly Twitter). We are committed to protecting your privacy and being completely transparent about how our extension works. **This extension only accesses and displays YOUR own activity data - never other users' private information.**

## What StreakX Does

StreakX is designed to help you:
- Track YOUR daily posting consistency
- Monitor YOUR tweet and reply counts
- Visualize YOUR activity patterns with beautiful charts
- Set and achieve YOUR personal posting goals
- Build better social media habits for YOUR account

**Important: StreakX only shows YOUR own activity data. And only if you have X Premium. It cannot and does not access other users' private metrics or personal information.**

## Data We Access

### Your X Account Data

When you use StreakX while logged into X.com, we access:

- **Your Authentication Session**: We use your existing X.com login session to authenticate API requests
- **Your Activity Metrics**: We fetch YOUR daily tweet and reply counts using X's internal API
- **Your CSRF Token**: We read the security token from your browser to make authenticated requests
- **Page Navigation**: We detect when you're browsing X.com to show/hide the sidebar

### What We DO NOT Access

- ❌ Other users' private activity data or metrics
- ❌ Your X password or login credentials
- ❌ Your direct messages or private conversations
- ❌ Your followers' or following lists
- ❌ Your X account settings or personal information
- ❌ Your browsing activity outside of X.com
- ❌ Any data from other websites or applications

## Data We Store

### Local Storage Only

ALL data is stored **locally in your browser** using Chrome's secure storage system:

- **Your Activity Metrics**: Daily tweet and reply counts for YOUR account
- **Your Preferences**: Date range settings, daily goals, and display options
- **Temporary Cache**: Recent activity data to improve performance (auto-expires after 1 hour)
- **Onboarding Status**: Whether you've completed the initial setup

### What We DO NOT Store

- ❌ Your X username or password
- ❌ Your personal information or profile data
- ❌ Other users' data or activity
- ❌ Your authentication tokens (used temporarily and discarded)
- ❌ Any data on external servers or databases

## How We Use Your Data

### Display Your Analytics
- Show YOUR daily activity counts in the sidebar
- Generate YOUR personal contribution charts
- Calculate YOUR posting streaks and progress
- Track YOUR goal achievement

### Improve Performance
- Cache YOUR recent activity data to reduce loading times
- Remember YOUR preferred settings and date ranges
- Provide smooth, responsive user experience

### No External Use
- We never send your data to external servers
- We never share your data with third parties
- We never use your data for advertising or marketing
- We never analyze your data for commercial purposes

## Data Security

### Authentication Security
- **No Password Storage**: We never store your X password or login credentials
- **Session-Based**: We use your existing browser session, no separate login required
- **Token Handling**: Authentication tokens are used temporarily and immediately discarded
- **Secure Requests**: All API requests use HTTPS encryption

### Local Data Protection
- **Browser Security**: Data stored using Chrome's secure storage APIs
- **No Cloud Storage**: Everything stays on your device
- **User Control**: You can clear all data anytime via the extension popup
- **Automatic Cleanup**: Temporary cache data expires automatically

## Your Privacy Rights

### Complete Control
- **View Your Data**: All stored data is accessible via Chrome DevTools
- **Delete Your Data**: Use the "Clear Cache" button or uninstall the extension
- **Export Your Data**: Data is stored in standard JSON format for easy export
- **Control Access**: Enable/disable the extension at any time

### Transparency
- **Open Source**: Extension code is available for review
- **No Hidden Features**: All functionality is clearly described
- **Clear Permissions**: Only requests necessary browser permissions
- **Regular Updates**: Privacy policy updated with any changes

## Third-Party Services

### X (Twitter) API
- **Purpose**: Fetch YOUR activity metrics using X's internal GraphQL API
- **Authentication**: Uses your existing X.com login session
- **Data Scope**: Limited to YOUR public activity metrics (tweet/reply counts)
- **Compliance**: Respects X's rate limits and terms of service

### Chrome Extension APIs
- **Storage API**: For local data persistence in your browser
- **Scripting API**: To inject the sidebar interface into X.com pages
- **Tabs API**: To extract authentication tokens from your X.com session
- **ActiveTab API**: To detect when you're viewing X.com

### No Other Services
- ❌ No analytics or tracking services
- ❌ No advertising networks
- ❌ No social media widgets
- ❌ No external databases or servers

## Data Retention

### Automatic Cleanup
- **Activity Cache**: Cleared automatically after 1 hour
- **Session Data**: Cleared when browser is closed
- **Temporary Files**: Cleaned up automatically by browser

### User-Controlled Data
- **Settings**: Stored until you change them or uninstall
- **Preferences**: Persistent across browser sessions
- **Complete Removal**: Uninstalling removes ALL stored data

## Children's Privacy

StreakX is designed for general audiences and does not knowingly collect personal information from children under 13. The extension only works with existing X.com accounts, which require users to be at least 13 years old per X's terms of service.

## International Users

### Data Location
- All data remains on your local device
- No international data transfers
- Compliant with GDPR, CCPA, and other privacy regulations

### Your Rights
- **Access**: View all stored data via browser tools
- **Rectification**: Modify settings and preferences anytime
- **Erasure**: Delete all data via clear cache or uninstall
- **Portability**: Export data in standard JSON format

## Updates and Changes

### Policy Updates
- Privacy policy changes will be clearly versioned and dated
- Significant changes will require explicit user consent
- Users will be notified of material policy updates
- Previous versions available for reference

### Extension Updates
- All updates maintain the same privacy standards
- No degradation of privacy protections
- New features include appropriate privacy notices
- Continuous improvement of security measures

## Contact and Support

### Questions About Privacy
If you have questions about this privacy policy or our data practices:

- 📧 **GitHub Issues**: [Create an issue](https://github.com/egemenkar/streakx-support/issues)
- 🐦 **Developer Contact**: [@egmndev](https://x.com/egmndev) on X, or email <egemn.dev@gmail.com>

### Exercising Your Rights
To access, modify, or delete your data:

1. **View Data**: Use Chrome DevTools → Application → Storage → Local Storage
2. **Clear Data**: Click "Clear Cache" in the extension popup
3. **Delete All**: Uninstall the extension to remove all stored data
4. **Export Data**: Data is stored in JSON format for easy backup

## Technical Details

### Security Measures
- **Content Security Policy (CSP)**: Prevents malicious code injection
- **Minimal Permissions**: Only requests necessary browser permissions
- **Secure Communication**: All requests use HTTPS encryption
- **Token Protection**: Authentication tokens never logged or stored
- **Regular Security Updates**: Continuous security improvements

### Data Format
All stored data uses standard JSON format and can be inspected at:
1. Open Chrome DevTools (F12)
2. Navigate to Application → Storage → Local Storage
3. Find entries with "StreakX" prefix
4. All data is human-readable JSON

## Compliance

### Legal Basis (GDPR)
- **Legitimate Interest**: Providing the core functionality you requested
- **Consent**: You explicitly install and enable the extension
- **Transparency**: This policy explains all data practices clearly

### Standards Compliance
- ✅ Chrome Web Store privacy requirements
- ✅ Manifest V3 security standards
- ✅ GDPR privacy-by-design principles
- ✅ CCPA consumer privacy rights
- ✅ Open-source transparency standards

## Summary

**StreakX is privacy-first by design:**
- Only shows YOUR own activity data
- Never accesses other users' private information
- Stores everything locally in your browser
- No external servers or data collection
- Full user control over all data

**Your privacy is our priority. StreakX helps you track your own X activity while keeping your data completely private and secure.**

---

_This privacy policy is effective as of the date last updated above. By using StreakX, you acknowledge that you have read and understood this policy. For the most current version, please check our GitHub repository._
