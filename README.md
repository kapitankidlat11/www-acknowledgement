# WWR Acknowledgement Pages

This repository contains two simple HTML pages used for recording contractor acknowledgements via Zapier.

## 🔗 Pages
- `acknowledgement.html`: Processes and records acknowledgement data to Zapier.
- `thankyou.html`: Displays a confirmation message after submission.

## ⚙️ How It Works
1. The email link (sent via Monday.com) should look like:
    https://yourusername.github.io/wwr-acknowledgement/acknowledgement.html?email={{Email}}
2. The page automatically:
- Shows a thank-you message
- Sends the `email` to your Zapier webhook
- Redirects to `thankyou.html` after 3 seconds

## 🌍 Deployment
1. Go to **Settings → Pages**.
2. Under “Build and deployment”, select:
- **Source:** `Deploy from branch`
- **Branch:** `main` / `(root)`
3. Save and wait for your site to publish.

Your live site will appear at: 
    https://yourusername.github.io/wwr-acknowledgement/

You can now use links like:

    https://yourusername.github.io/wwr-acknowledgement/acknowledgement.html?email=test@example.com