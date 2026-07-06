# GRIFFIN_Desktop_Encryptor
Secure Encryptor designed for protecting files at rest using modern authenticated encryption

Griffin Desktop Encryptor is an offline desktop file encryptor designed for protecting files at rest using modern authenticated encryption. It is intended for local storage and file transfer, not real-time communication.
=================================================================================================================
ChaCha20-Poly1305 was selected to work better across cpu's,  has a limit of 12 byte nonce in standard version though risk of a collision is low.
Argon2id for 256 bit keys.
Security assumption is that there is no malware on the desktop.
Ui is built to be simple. 
Free for any use and available for peer review on Github.
