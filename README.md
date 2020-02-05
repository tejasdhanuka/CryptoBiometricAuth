# CryptoBiometricAuth

An iOS mobile application that protects an asymmetric cryptography key using the biometric authentication provided by the platform.

The target platform is iOS 10.1 and it uses touch id to authenticate the encryption and decryption of the key.

On launch of application you need to enter the text to be encrypted in the topmost text field "Enter Text" and click on the "Encrypt & Sign Text" button below it. The app will prompt you to authorize the encryption using your touch ID. Similar is for the "Decrypt & Verify Sign" button.

On decryption success, It will show the original decrypted text in the "Decrypted Text" field and success or failure in "Verification Result" field.
