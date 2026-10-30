# HarshGuruJi Instant Payment Portal

Official payment desk for **HarshGuruJi** services and AI Premium Model upgrades ([https://payment.webguruji.online](https://payment.webguruji.online)).

## Features
- **No Navigation Bar**: Clean, distraction-free transaction environment.
- **Inquiry Verification**: Directly checks Supabase database (`contact_messages`) to ensure user submitted an AI upgrade inquiry before claiming payment.
- **Anti-Fraud Security**: Rejects payment attempt if user did not first submit an inquiry via AI contact.
- **Interactive Full-Size QR Scanner**: Dynamic UPI QR generator for `harshguruji01@gmail.com` with real-time laser sweep animation.
- **Instant Model Activation**: Automatically updates `user_ai_limits` and persists activation tokens across browser sessions and mobile apps.
- **Automated Dispatch**: Sends payment confirmation notifications from `info@webguruji.online`.
