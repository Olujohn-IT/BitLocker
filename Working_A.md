# How Bitlocker works

BitLocker uses a specialized chip called a **Trusted Platform Module (TPM)**
TPM stores Rivest-Shamir-Adleman encryption keys specific to the host system for hardware authentication.

https://www.techtarget.com/searchenterprisedesktop/definition/BitLocker

## How to Enable Bitlocker
- Enabling BitLocker using hardware-based encryption
  - Check if your device has TPM support to enable BitLocker
  - Enable BitLocker

- Enabling BitLocker using software-based encryption (without TPM support)
  - Activate startup authentication with Local Group Policy Editor
  - Enable BitLocker

[How to](https://superops.com/blog/bitlocker-encryption-windows-10)
