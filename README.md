# JWT Token Decoder - Security Notice

⚠️ **IMPORTANT SECURITY WARNING** ⚠️

## This tool is for DEVELOPMENT/TESTING only

### What this tool does:
- Decodes JWT bearer tokens from URL parameters
- Displays token content in JSON format
- **NEVER use with production tokens**

### Security Considerations:
1. **Tokens in URLs are logged everywhere** (server logs, browser history, analytics)
2. **Anyone with the URL can see the token**
3. **No authentication or access control**

### Safe Usage:
- ✅ Development/test tokens only
- ✅ Expired tokens for analysis
- ✅ Sample/demo tokens
- ❌ Never production tokens
- ❌ Never tokens with sensitive data
- ❌ Never share URLs containing tokens


## Usage
```
https://www.rickneeft.dev/jwt/?bearer=your_jwt_token_here
```

**Remember: Tokens are immediately cleared from URL but may still be logged by GitHub Pages, CDNs, or analytics tools.**