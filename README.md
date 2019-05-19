# mobiPass-password-manager
Smartphone bio-metrics based password manager for firefox


Porject proposal for a highly secure password manager leveraging Samsung Knox and smartphone bio-metrics.

Project structure:
1. Firefox plugin to detect login requests
2. Bluetooth, Wifi server on Android app to get requests from PC in offline mode
3. MQTT server to push request to smartphone (Online mode) 
4. Samsung Knox secure storage (Fingerprint secured) for storing credentials
