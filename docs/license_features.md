# BerEditor Features by License Status

This page summarizes the feature differences between the unlicensed and licensed versions of BerEditor. It reflects the application menus and license checks in the source code; available actions can also vary by build and platform.

## Feature comparison

| Area | Without a license | With a license |
| --- | --- | --- |
| BER files | Open and inspect BER data in the main tree, subject to the 10,000-byte unlicensed limit. | Open larger BER files. |
| BER operations | Decode BER. | Create, check, compare, and edit BER data; insert, delete, and change nodes. |
| Search and views | Binary view and BER information pane; Find and Text View are disabled. | Find BER values; use XML, Text, JSON, and Log views. |
| General converters | Data converter and numeric converter. | Data converter and numeric converter remain available. |
| Certificate and CSR details | Open certificate and CSR information dialogs and inspect basic fields. | Additional validation and management controls. |
| Cryptography and keys | Cryptographic menu operations and key management are disabled. | Key management and key-pair management; hashing, MAC, encryption/decryption, signing/verification, public-key operations, key agreement, PKCS#7/CMS, secret sharing, OTP, big-number calculator, and private-key generation. |
| Certificate and service tools | Licensed service actions are disabled. | SSL Check, X.509 Compare, document signing, CAVP, and certificate/key management tools. |
| Protocol clients | OCSP, TSP, CMP, SCEP, ACME, EST, and KMIP TTLV actions are disabled. | OCSP, TSP, CMP, SCEP, ACME, and EST clients; KMIP TTLV decode, create, encode, and client tools. |

## License and access comparison

| Item | Without a license | With a license |
| --- | --- | --- |
| Application status | Identified as unlicensed in the window title and About dialog. | Identified as a licensed version in the license information. |
| License management | Can open License Information and request a license. | Can review, import, update, or renew a license. |
| Free license | The application includes a free-license request flow; eligibility and request details are provided in the app. | Available according to the terms shown in the app. |
| Applying a change | A newly issued or imported license may require a restart. | Restart BerEditor when prompted to apply a changed license. |
| Settings | Some advanced settings are disabled. | License-gated settings are enabled, including hash defaults, file-read size, certificate path, key-pair support, and related certificate options. |

Core file and navigation actions remain available in the unlicensed interface. Feature availability can also vary by build and platform.

## License status and activation

BerEditor labels the unlicensed application in its window title and About dialog. You can review license status and request, import, update, or renew a license from the License Information interface. The application includes a free-license request flow; check the current in-app instructions for eligibility and request details. Restart BerEditor when prompted to apply a changed license.

## Notes

- A license unlocks application features; it does not guarantee that a particular operation will succeed. Results still depend on input data, configuration, and the relevant protocol or cryptographic requirements.
- This document describes the license gates present in the codebase. Consult the documentation or the running version for any release-specific changes.
