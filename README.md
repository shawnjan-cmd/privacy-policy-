Privacy Policy
​Last updated: May 04, 2026
​1. Information We Collect
We prioritize your privacy. The App does NOT collect, store, or transmit Personally Identifiable Information (PII) to our servers. We only process data required for core functionality:
​Device Pairing Data: Cryptographic tokens and connection statuses used to securely link your mobile device to your PC.
​Local Network Data: IP addresses and port numbers required for direct device-to-device communication.
​Push Notification Tokens: We collect anonymized device push tokens (via Expo) strictly to deliver task completion alerts and haptic feedback from your PC to your phone.
​System Telemetry: The App receives local system diagnostics (CPU, RAM, Disk usage, and process lists) directly from your paired PC.
​2. Required Permissions
The App requests the following permissions solely to function:
​Camera: Exclusively for scanning QR codes during the initial PC pairing process. No photos or videos are recorded or saved.
​Local Network / Wi-Fi: To discover and communicate directly with your PC over your local network.
​Notifications: To receive alerts when long-running PC scripts complete.
​3. How Data is Processed
​Local Execution: All PC commands, script executions, file transfers, and system telemetry are transmitted directly over your local network.
​Local AI Chat: Chat queries are sent directly to the local Ollama instance running on your PC. Your chat history is stored locally in an SQLite database on your machine.
​Knowledge Base Expansion: To improve AI answers, the PC server may anonymously forward technical queries to public search engines (like DuckDuckGo or Google) to download relevant automation scripts and tutorials. No user identity data is attached to these automated searches.
​4. Third-Party Services
While core execution is local, we utilize specific third-party infrastructure to facilitate connections:
​Supabase: Used strictly as backend infrastructure for managing the connection handshake and authentication state. Supabase DOES NOT have access to your local network traffic, command logs, or chat history.
​Expo Push API: Used to securely route notifications from your PC to your mobile device.
​5. Data Security
We implement self-healing HMAC tokens, automatic session locking, and secure WebSockets to protect your connection. Your PC server will auto-lock to your specific device ID upon pairing. However, the security of your local Wi-Fi network remains your responsibility.
​6. User Rights & Deletion
Since we do not store personal data or user accounts remotely, there is no account deletion process. You can revoke the App's permissions at any time via your device settings, and you can clear all chat history and synced data directly via the PC server dashboard or by deleting the local .butler_server_v6.db file on your computer.
​7. Changes to This Policy
We may update this Privacy Policy periodically. Continued use of the App after changes indicates your acceptance of the updated terms.
​8. Contact
If you have questions about these privacy practices, please contact the developer via the standard support channels provided in the app store, or at: andrejsladkovic1992@gmail.com.
