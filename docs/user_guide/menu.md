# BerEditor Menu Guide


## File

| Menu item | Description |
| --- | --- |
| New | Opens a new BerEditor window. |
| Open... | Opens a BER file. |
| [Open Certificate](CERT_INFO_DLG_EN.md) | Opens a certificate file. |
| [Open CRL](CRL_INFO_DLG_EN.md) | Opens a certificate revocation list (CRL) file. |
| [Open CSR](CSR_INFO_DLG_EN.md) | Opens a certificate signing request (CSR) file. |
| Open PrivateKey | Opens a private key file. |
| Open PublicKey | Opens a public key file. |
| [Open CMS](CMS_INFO_DLG_EN.md) | Opens a CMS file. |
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
| [Find](FIND_DLG_EN.md) | Searches for a node in the BER data. |

## Tool

| Menu item | Description |
| --- | --- |
| [Decode BER](decode_data_dlg.md) | Decodes BER data. |
| [Data Converter](data_converter_dlg.md) | Converts data character encodings or representations. |
| [Num Converter](num_converter_dlg.md) | Converts numeric representations. |
| [OID Information](oid_info_dlg.md) | Looks up Object Identifier (OID) information. |
| [Make BER](MAKE_BER_DLG_EN.md) | Creates BER data. |
| [Check BER](BER_CHECK_DLG_EN.md) | Checks the format and validity of BER data. |
| [Get BER from URI](GET_URI_DLG_EN.md) | Retrieves BER data from a URI. |
| [BER Compare](BER_COMPARE_DLG_EN.md) | Compares two BER data values. |
| [Binary View](BIN_VIEW_DLG_EN.md) / [Text View](TEXT_VIEW_DLG_EN.md) | Opens data in binary or text view. |

## Cryptography

| Menu item | Description |
| --- | --- |
| [Key Manage](KEY_MAN_DLG_EN.md) | Provides key derivation and key encryption/decryption functions. |
| [Hash](GEN_HASH_DLG_EN.md) | Generates a hash value. |
| [Message Authentication Code](GEN_MAC_DLG_EN.md) | Generates a message authentication code (MAC). |
| [Encrypt/Decrypt](ENC_DEC_DLG_EN.md) | Encrypts or decrypts data. |
| [Sign/Verify](SIGN_VERIFY_DLG_EN.md) | Creates or verifies a digital signature. |
| [PubKey Encrypt/Decrypt](PUB_ENC_DEC_DLG_EN.md) | Encrypts or decrypts data using a public key. |
| [Key Agreement](KEY_AGREE_DLG_EN.md) | Performs DH or ECDH key agreement. |
| [PKCS7](PKCS7_DLG_EN.md) | Creates and validates PKCS#7 messages. |
| [Shamir Secret Sharing](SSS_DLG_EN.md) | Splits a key or combines key shares. |
| [Certificate Path Validation](CERT_PVD_DLG_EN.md) | Validates a certificate path. |
| [OTP Generator](GEN_OTP_DLG_EN.md) | Generates a one-time password (OTP). |
| [VID](VID_DLG_EN.md) | Generates and validates VID values. |
| [BN Calculator](BN_CALC_DLG_EN.md) | Performs big number calculations. |
| [Make PrivateKey](MAKE_PRI_KEY_DLG_EN.md) | Generates a private key. |

## Service

| Menu item | Description |
| --- | --- |
| [KeyPair Manage](KEY_PAIR_MAN_DLG_EN.md) | Lists and manages asymmetric key pairs. |
| [Certificate Manage](CERT_MAN_DLG_EN.md) | Lists and manages certificates and keys. |
| [Key List](KEY_LIST_DLG_EN.md) | Lists and manages symmetric keys. |
| [SSL Check](SSL_CHECK_DLG_EN.md) | Checks SSL/TLS protocol connections. |
| [X509 Compare](X509_COMPARE_DLG_EN.md) | Compares X.509 information. |
| [Document Signer](DOC_SIGNER_DLG_EN.md) | Provides document digital signing functions. |
| [PDF Signer](PDF_SIGNER_DLG_EN.md) | Provides PDF digital signing functions. Availability depends on build options. |
| [CAVP](CAVP_DLG_EN.md) | Provides cryptographic algorithm validation functions. |

## Protocol

| Menu item | Description |
| --- | --- |
| [OCSP client](OCSP_CLIENT_DLG_EN.md) | Checks certificate status using OCSP. |
| [TSP client](TSP_CLIENT_DLG_EN.md) | Processes Time-Stamp Protocol (TSP) requests. |
| [CMP client](CMP_CLIENT_DLG_EN.md) | Processes Certificate Management Protocol (CMP) requests. |
| [SCEP client](SCEP_CLIENT_DLG_EN.md) | Processes SCEP certificate enrollment requests. |
| [ACME client](ACME_CLIENT_DLG_EN.md) | Processes ACME protocol requests. |
| [EST client](EST_CLIENT_DLG_EN.md) | Processes EST protocol requests. |

## KMIP

| Menu item | Description |
| --- | --- |
| [Decode TTLV](DECODE_TTLV_DLG_EN.md) | Decodes KMIP TTLV messages. |
| [Make TTLV](MAKE_TTLV_DLG_EN.md) | Creates KMIP TTLV messages. |
| [TTLV Encoder](TTLV_ENCODER_DLG_EN.md) | Encodes TTLV messages. |
| [TTLV Client](TTLV_CLIENT_DLG_EN.md) | Runs the KMIP TTLV client. |

## Help

| Menu item | Description |
| --- | --- |
| [Settings](SETTINGS_DLG_EN.md) | Configures the application environment. |
| Clear Log | Clears messages in the Log tab. |
| Log | Pauses or resumes logging. |
| [Content](CONTENT_MAIN_EN.md) | Displays PKI-related information. |
| [License Information](LCN_INFO_DLG_EN.md) | Displays license and registration information. |
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
