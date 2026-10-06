## CertUI

> `/System/Library/PrivateFrameworks/CertUI.framework/CertUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4200` | `0x41e8` | **`-0x18`** |

### Other Changes

```diff

-2054.0.0.0.0
+2055.0.0.0.0
Functions:
~ __CopyKeychainAccountForPrefixParticularDigest : 408 -> 404
~ +[CertUIPrompt(Private) stringForResponse:] : 200 -> 192
~ -[CertUIPrompt _sendablePropertiesFromProperties:] : 340 -> 336
~ -[CertUIPrompt _sendablePropertiesFromTrust:] : 340 -> 336
~ -[CertUIPrompt _propertyNamed:ofType:inProperties:] : 460 -> 456
```
