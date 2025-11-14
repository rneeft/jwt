# JWT Bearer Token Decoder

A modern, user-friendly web tool for decoding JWT (JSON Web Token) bearer tokens with real-time syntax highlighting and color-coded output.

⚠️ **IMPORTANT SECURITY WARNING** ⚠️

## This tool is for DEVELOPMENT/TESTING only

### What this tool does:
- **Real-time JWT decoding** - Paste tokens and instantly see decoded content
- **Color-coded input** - Visual highlighting of header, payload, and signature sections
- **Separated output** - Individual textareas for header, payload, and signature
- **Bootstrap 5 styling** - Modern, responsive design
- **Backward compatibility** - Still supports URL parameter method
- **Client-side only** - No server-side processing, tokens never leave your browser

### Key Features:
- 🎨 **Color-coded sections**: Blue (header), Purple (payload), Green (signature)
- ⚡ **Real-time decoding**: No buttons needed - decode as you type
- 📱 **Responsive design**: Works on desktop and mobile devices
- 🔒 **Privacy-focused**: All processing happens in your browser
- 📋 **Easy copying**: Separate textareas for each JWT component
- 🎯 **Error handling**: Clear error messages for invalid tokens

### Security Considerations:
1. **Always use development/test tokens only**
2. **Never use with production tokens containing sensitive data**
3. **URL method logs tokens** (if using backward compatibility feature)
4. **No authentication or access control**

### Safe Usage:
- ✅ Development/test tokens only
- ✅ Expired tokens for analysis
- ✅ Sample/demo tokens
- ✅ Learning JWT structure
- ❌ Never production tokens
- ❌ Never tokens with sensitive data
- ❌ Never share URLs containing tokens

## Usage

### Primary Method:
1. Open the web tool
2. Paste your JWT token in the input area
3. View the color-coded, decoded output in real-time

### Input Features:
- **Automatic "Bearer " prefix handling** - Paste with or without the prefix
- **Visual highlighting** - Each JWT section is color-coded as you type
- **Smart paste handling** - Maintains plain text formatting

### Output Display:
- **Header Section** (Blue): JWT algorithm and token type information
- **Payload Section** (Purple): Claims and user data (main content)
- **Signature Section** (Green): Token verification signature

## Technical Details:
- Built with vanilla JavaScript and Bootstrap 5
- Uses contenteditable div for smooth text highlighting
- Responsive CSS Grid layout with proper viewport handling
- Base64URL decoding with proper padding handling
- XSS protection through HTML escaping

**Privacy Note: All JWT processing happens entirely in your browser. Tokens are never sent to any server.**