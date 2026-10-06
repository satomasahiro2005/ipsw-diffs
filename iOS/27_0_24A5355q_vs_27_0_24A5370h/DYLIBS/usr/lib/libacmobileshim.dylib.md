## libacmobileshim.dylib

> `/usr/lib/libacmobileshim.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cad8` | `0x3caac` | **`-0x2c`** |

### Other Changes

```text
Functions:
~ -[ACMSystemInfo MACAddress] : 232 -> 228
~ -[ACFCryptograph clearKey:] : 124 -> 132
~ -[ACMExternalAppleConnectImpl twoSVTransportControllerCancelFetchingImages:] : 272 -> 268
~ _ACFMakeRandomData : 168 -> 176
~ _ACFMakeRandomString : 204 -> 212
~ _ACFDecodeBase32 : 764 -> 760
~ _ACFEncodeBase16 : 272 -> 268
~ _ACFSHA1AsString : 160 -> 156
~ _ACFSHA256AsString : 160 -> 156
~ _ACFEncodeObscuredString : 272 -> 268
~ _ACFDecodeObscuredString : 168 -> 172
~ -[ACFHTTPMethodInvocation invoke] : 1064 -> 1060
~ _ACFDataCreateByteString : 160 -> 176
~ -[ACMKeychainTGTStoragePolicy searchTokenWithPrincipal:] : 300 -> 296
~ -[ACMKeychainTGTStoragePolicy allTokensWithPrincipal:service:] : 520 -> 516
~ -[ACMKeychainTGTStoragePolicy performRemoveTokenWithPrincipal:service:] : 948 -> 944
~ -[ACFKeychainManager dumpResults:printAttributes:] : 536 -> 532
~ -[ACFKeychainManager searchItemWithInfo:] : 1096 -> 1092
~ -[ACMiTunesSignInDialog_Legacy handleRotation] : 572 -> 568
~ -[ACC2SVController trustedDevicesFromResponse:withContext:] : 836 -> 832
~ -[ACFHTTPTransport requestString:] : 404 -> 396
~ -[ACFHTTPTransport performRequest] : 804 -> 800
~ -[ACM2SVTrustedDevicesViewController sizeOfString:withFont:widthConstraints:] : 356 -> 352
~ -[ACMSignInDialogSimple_Modern buildWidgetContentGroupVerticalConstraints] : 712 -> 708
~ -[ACMSignInDialogSimple_Modern disableControls:] : 304 -> 300
~ +[ACMBaseLocale setupUsingPreferredLanguages] : 356 -> 352
```
