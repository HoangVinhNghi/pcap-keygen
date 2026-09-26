# PCAP Analyzer — Key Generator

Admin page that issues Gen Keys for the offline activation of PCAP Analyzer.

- Open: https://hoangvinhnghi.github.io/pcap-keygen/
- Admin sign-in required. The licence secret in this page is encrypted (PBKDF2-SHA256, 600 000 iterations → AES-256-GCM) and is only decrypted in the admin's browser with the admin password. Nothing is sent anywhere.
- Built from the private PCAP Analyzer repository (`npm run build:keygen:hosted`).
