## DigitalAccess

> `/System/Library/PrivateFrameworks/DigitalAccess.framework/DigitalAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ae60` | `0x3af10` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x8d46` | `0x8d8e` | **`+0x48`** |

### Other Changes

```diff

-70.39.1.0.0
+71.7.0.0.0
Symbols:
+ +[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]
+ +[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]
+ -[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]
+ -[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]
+ -[KmlSettingsManager ignoreProcessedSourceIdentifierCheck]
+ ___257-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]_block_invoke
+ ___296-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]_block_invoke
- +[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]
- +[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]
- -[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]
- -[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]
- -[KmlSettingsManager ignoreProcessedSpotlightIdCheck]
- ___239-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]_block_invoke
- ___278-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]_block_invoke
Functions:
~ +[KmlManagerInterface interface] : 3648 -> 3652
~ +[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:] -> +[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:] : 452 -> 484
~ -[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:] -> -[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:] : 756 -> 792
~ +[DAManager(PendingPairing) createPendingPairingForOPURLString:] : 492 -> 540
~ +[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:] -> +[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:] : 328 -> 372
~ -[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:] -> -[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:] : 652 -> 664
CStrings:
+ "-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]"
+ "-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]_block_invoke"
+ "-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]"
+ "-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:messageIdentifier:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]_block_invoke"
- "-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]"
- "-[DAManager(PendingPairing) createPendingPairingForManufacturer:brand:pairingPassword:supportedTransports:ppid:pti:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:]_block_invoke"
- "-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]"
- "-[DAManager(PendingPairing) createPendingPairingForOPURL:pairingPasswordExpiration:vehicleName:userNotificationDate:spotlightDomain:spotlightUniqueId:spotlightBundle:sourceReceivedDate:sourceLanguage:alreadyProvisioned:simulateBiomeEvent:]_block_invoke"
```
