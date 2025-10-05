# 📋 Mopy - Smart Clipboard Manager

A beautiful Chrome extension for organizing and managing text snippets with modern glass UI design.

## ✨ Features

- 📁 **Folder Organization** - Create custom sections with icons
- ⚡ **One-Click Copy** - Instant clipboard access
- 🔍 **Smart Search** - Find snippets instantly
- 📤 **Import/Export** - Backup and share your data
- 🔐 **Secrets Management** - Secure storage for sensitive data
- �️ **Masked Values** - Click to reveal sensitive content safely
- �💾 **Auto Backup** - Never lose your snippets
- 🎨 **Glass UI Design** - Modern iPhone-style interface
- 💾 **Local Storage** - Your data stays private and secure
- 🔄 **Real-time Updates** - Seamless user experience

## 🚀 Try It Now

**Version 2.1** is now available with enhanced security features! You can try it immediately by downloading the extension:

### 📦 Download & Install

**Latest Version (v2.1)** - _Recommended_

1. **Download**: [mopy-v2.1.zip](https://github.com/bhargavraju49/mopy-public/raw/main/mopy-v2.1.zip)

**Previous Versions:**

- **v2.0**: [mopy-v2.0.zip](https://github.com/bhargavraju49/mopy-public/raw/main/mopy-v2.0.zip)
- **v1.1**: [mopy-v1.1.zip](https://github.com/bhargavraju49/mopy-public/raw/main/mopy-v1.1.zip)

### Installation Steps:

2. **Extract** the zip file
3. **Open Chrome** → Go to `chrome://extensions/`
4. **Enable** "Developer mode" (top right toggle)
5. **Click** "Load unpacked" → Select the extracted folder
6. **Done!** Click the Mopy icon in your toolbar

## 🆕 What's New in v2.1

- 👁️ **Masked Values** - Sensitive content is hidden by default, click to reveal safely
- 🔒 **Enhanced Security** - Better protection for your sensitive data
- 🛡️ **Privacy Improvements** - More secure handling of secrets

## 📋 Previous Updates (v2.0)

- 🔍 **Advanced Search** - Find any snippet instantly
- 📤 **Import/Export** - Backup your data or migrate between devices
- 🔐 **Secrets Vault** - Secure storage for passwords and sensitive data
- 💾 **Auto Backup** - Automatic data protection
- ⚡ **Performance Improvements** - Faster and more responsive

## 🎯 Perfect For

- Developers storing code snippets
- Content creators managing templates
- Professionals organizing responses
- Anyone boosting productivity

## 🔒 Privacy

- No data collection
- Local storage only
- No external servers
- [Privacy Policy](./privacy.html)

## 📱 Screenshots

_Coming soon - Chrome Web Store submission in progress_

---

**Made with ❤️ using React + Material-UI + Chrome Extension APIs**
import reactDom from 'eslint-plugin-react-dom'

export default defineConfig([
globalIgnores(['dist']),
{
files: ['**/*.{ts,tsx}'],
extends: [
// Other configs...
// Enable lint rules for React
reactX.configs['recommended-typescript'],
// Enable lint rules for React DOM
reactDom.configs.recommended,
],
languageOptions: {
parserOptions: {
project: ['./tsconfig.node.json', './tsconfig.app.json'],
tsconfigRootDir: import.meta.dirname,
},
// other options...
},
},
])

```

```
