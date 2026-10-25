# BerEditor Menu Guide


## File

| Menu item | Description |
| --- | --- |
| New | Opens a new BerEditor window. |
| Open... | Opens a BER file. |
| Open Certificate | Opens a certificate file. |
| Open CRL | Opens a certificate revocation list (CRL) file. |
| Open CSR | Opens a certificate signing request (CSR) file. |
| Open PrivateKey | Opens a private key file. |
| Open PublicKey | Opens a public key file. |
| Open CMS | Opens a CMS file. |
| Save / Save As... | Saves the current data or saves it under another name. |
| Recent Files | Reopens a recently used file. Up to 10 entries are maintained. |
| Print / Print Preview | Prints the current content or previews it before printing. |
| Quit | Exits BerEditor. |

## Edit

| Menu item | Description |
| --- | --- |
| Copy Information | Copies the contents of the current selection to the clipboard. |
| Copy As Hex | Copies the selected value in hexadecimal format. |
| Copy As Base64 | Copies the selected value in Base64 format. |
| Expand All / Expand Node | Expands all nodes in the BER tree or the selected node. |
| Collapse All / Collapse Node | Collapses all nodes in the BER tree or the selected node. |
| Previous Node / Next Node | Moves to the previous or next node in the tree. |
| Find | Searches for a node in the BER data. |

## Tool

| Menu item | Description |
| --- | --- |
| Decode BER | Decodes BER data. |
| Data Converter | Converts data character encodings or representations. |
| Num Converter | Converts numeric representations. |
| OID Information | Looks up Object Identifier (OID) information. |
| Make BER | Creates BER data. |
| Check BER | Checks the format and validity of BER data. |
| Get BER from URI | Retrieves BER data from a URI. |
| BER Compare | Compares two BER data values. |
| Binary View / Text View | Opens data in binary or text view. |

## Cryptography

| Menu item | Description |
| --- | --- |
| Key Manage | Provides key derivation and key encryption/decryption functions. |
| Hash | Generates a hash value. |
| Message Authentication Code | Generates a message authentication code (MAC). |
| Encrypt/Decrypt | Encrypts or decrypts data. |
| Sign/Verify | Creates or verifies a digital signature. |
| PubKey Encrypt/Decrypt | Encrypts or decrypts data using a public key. |
| Key Agreement | Performs DH or ECDH key agreement. |
| PKCS7 | Creates and validates PKCS#7 messages. |
| Shamir Secret Sharing | Splits a key or combines key shares. |
| Certificate Path Validation | Validates a certificate path. |
| OTP Generator | Generates a one-time password (OTP). |
| VID | Generates and validates VID values. |
| BN Calculator | Performs big number calculations. |
| Make PrivateKey | Generates a private key. |

## Service

| Menu item | Description |
| --- | --- |
| KeyPair Manage | Lists and manages asymmetric key pairs. |
| Certificate Manage | Lists and manages certificates and keys. |
| Key List | Lists and manages symmetric keys. |
| SSL Check | Checks SSL/TLS protocol connections. |
| X509 Compare | Compares X.509 information. |
| Document Signer | Provides document digital signing functions. |
| PDF Signer | Provides PDF digital signing functions. Availability depends on build options. |
| CAVP | Provides cryptographic algorithm validation functions. |

## Protocol

| Menu item | Description |
| --- | --- |
| OCSP client | Checks certificate status using OCSP. |
| TSP client | Processes Time-Stamp Protocol (TSP) requests. |
| CMP client | Processes Certificate Management Protocol (CMP) requests. |
| SCEP client | Processes SCEP certificate enrollment requests. |
| ACME client | Processes ACME protocol requests. |
| EST client | Processes EST protocol requests. |

## KMIP

| Menu item | Description |
| --- | --- |
| Decode TTLV | Decodes KMIP TTLV messages. |
| Make TTLV | Creates KMIP TTLV messages. |
| TTLV Encoder | Encodes TTLV messages. |
| TTLV Client | Runs the KMIP TTLV client. |

## Help

| Menu item | Description |
| --- | --- |
| Settings | Configures the application environment. |
| Clear Log | Clears messages in the Log tab. |
| Log | Pauses or resumes logging. |
| Content | Displays PKI-related information. |
| License Information | Displays license and registration information. |
| Bug or Issue Report | Reports bugs or issues. |
| Q and A | Opens question-and-answer information. |
| About BerEditor | Displays information about BerEditor. |

## Menu Shortcuts

Shortcut notation may vary by operating system. The following combinations are based on those assigned in the source code.

| Menu item | Shortcut |
| --- | --- |
| Open | Ctrl+O |
| Open Certificate / CRL / CSR | F2 / F3 / F4 |
| Save / Save As | Ctrl+S / Ctrl+Shift+S |
| Print | Ctrl+P |
| Copy Information | Ctrl+C |
| Copy As Hex / Base64 | Ctrl+X / Ctrl+B |
| Expand All / Expand Node | F5 / F6 |
| Collapse All / Collapse Node | F7 / F8 |
| Previous Node / Next Node | Ctrl+← / Ctrl+→ |
| Find | Ctrl+F |
| Clear Log / Log | F9 / F10 |
| Content / About BerEditor | F11 / F1 |

> Note: Menu names follow the English UI labels. Check the running application for the exact translations, platform-specific shortcuts, and availability under your license.
