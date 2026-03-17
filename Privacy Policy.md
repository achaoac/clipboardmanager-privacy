# Privacy Policy for ClipboardManager

**Last Updated**: March 15, 2026  
**Developer**: wangchao  
**Contact**: aclct@icloud.com  

---

## Overview

ClipboardManager ("the App") is committed to protecting your privacy. This Privacy Policy explains how we handle information when you use our clipboard management application for macOS.

## Information We Collect

**We do not collect any personal information.**

ClipboardManager is designed with privacy as a core principle:

- ✅ No personal data collection
- ✅ No analytics or tracking
- ✅ No user accounts required
- ✅ No internet connection needed
- ✅ No third-party services integrated

## Data Storage

### Local Storage Only

All clipboard history is stored **exclusively on your Mac**:

- Text content is saved in a local database
- Images are saved in your Mac's application support folder
- File paths are stored (not the actual files)
- All data remains on your device and never leaves it

### Data Location

```
~/Library/Application Support/ClipboardManager/
```

This folder contains:
- `clipboardItems.json` - Your clipboard history
- `Images/` - Saved clipboard images

### Data Retention

- The app stores a maximum of 20 clipboard items
- Older items are automatically deleted when the limit is reached
- Image files are automatically cleaned up after 30 days
- You can manually clear all history at any time through the app settings

## Permissions

### Required Permissions

The app requests the following macOS permissions:

1. **Clipboard Access**
   - **Purpose**: To monitor and save clipboard changes
   - **Scope**: Only monitors when the app is running
   - **Control**: Can be disabled by quitting the app

2. **File System Access** (Sandbox)
   - **Purpose**: To save clipboard images and history data
   - **Scope**: Limited to the app's own container
   - **Control**: Standard macOS app sandbox restrictions apply

### No Additional Permissions

The app does NOT request:
- ❌ Camera or microphone
- ❌ Location services
- ❌ Contacts or calendar
- ❌ Network access
- ❌ Full disk access

## Third-Party Services

**None.**

ClipboardManager does not integrate with any third-party services:

- No analytics frameworks
- No crash reporting services
- No advertising networks
- No social media integration
- No cloud storage services

## Data Sharing

**We never share your data** because we never collect it in the first place.

- No data is transmitted over the internet
- No data is shared with third parties
- No data is sold or monetized
- No data leaves your Mac

## Children's Privacy

ClipboardManager does not knowingly collect information from children. The app is rated 4+ and suitable for all ages. Since we collect no personal information, there is no special consideration needed for users under 13.

## Data Security

### Local Security

Your clipboard history is protected by:

- macOS app sandboxing
- Standard file system permissions
- Your Mac's user account security
- FileVault encryption (if enabled on your Mac)

### Best Practices

To protect your clipboard data:

1. Use a strong password for your Mac user account
2. Enable FileVault disk encryption
3. Keep your Mac and the app updated
4. Don't copy sensitive passwords (use a password manager instead)

## Your Rights

Since we don't collect any personal data, data subject rights under GDPR, CCPA, or other privacy laws don't apply. However, you have complete control over your data:

### Access Your Data

Your clipboard history is stored in plain text JSON format at:
```
~/Library/Application Support/ClipboardManager/clipboardItems.json
```

You can open this file with any text editor.

### Delete Your Data

To delete all your clipboard history:

1. **In the app**: Click "Clear History" in settings
2. **Manually**: Delete the folder:
   ```
   ~/Library/Application Support/ClipboardManager/
   ```
3. **Completely remove**: Uninstall the app and delete the folder above

### Export Your Data

Your clipboard history is stored in JSON format and can be easily exported by copying the `clipboardItems.json` file.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:

- Posting the new Privacy Policy on this page
- Updating the "Last Updated" date at the top
- Releasing an app update with a changelog

Continued use of the app after changes constitutes acceptance of the updated Privacy Policy.

## Contact Us

If you have questions about this Privacy Policy or the app's privacy practices, please contact:

**Email**: aclct@icloud.com  
**Developer**: wangchao  

We typically respond within 1-2 business days.

## Compliance

### GDPR Compliance

Under the General Data Protection Regulation (GDPR), we are compliant because:

- We process no personal data
- No data leaves your device
- No consent is required as we collect nothing

### CCPA Compliance

Under the California Consumer Privacy Act (CCPA), we are compliant because:

- We sell no personal information
- We collect no personal information
- No opt-out mechanisms are needed

### App Store Guidelines

This app complies with Apple's App Store Review Guidelines section 5.1.1 regarding data collection and privacy.

---

## Summary

**In Plain English:**

ClipboardManager is a simple tool that works entirely on your Mac. We don't collect, store, or transmit any of your data. Everything stays on your computer. We can't see what you copy, and we don't want to. Your privacy is guaranteed because we literally have no way to access your information.

---

**Privacy Policy Version**: 1.0  
**Effective Date**: March 15, 2026  
**Language**: English  

---

## 中文版隐私政策

[查看中文版](./Privacy-Policy-zh.md)
