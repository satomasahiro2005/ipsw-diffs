## GenerativeModels

> `/System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcc3d0` | `0xce85c` | **`+0x248c`** |
| `__TEXT.__oslogstring` | `0x2e63` | `0x3263` | **`+0x400`** |
| `__DATA.__bss` | `0xc500` | `0xc280` | **`-0x280`** |
| `__DATA_DIRTY.__bss` | `0x6080` | `0x6300` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0x7eb0` | `0x7c40` | **`-0x270`** |
| `__TEXT.__cstring` | `0x27b3` | `0x29c3` | **`+0x210`** |
| `__DATA_DIRTY.__data` | `0x15f0` | `0x1798` | **`+0x1a8`** |
| `__AUTH.__objc_data` | `0x560` | `0x410` | **`-0x150`** |
| `__DATA_DIRTY.__objc_data` | `0xf8` | `0x248` | **`+0x150`** |
| `__TEXT.__swift5_capture` | `0xdf8` | `0xcf8` | **`-0x100`** |
| `__TEXT.__eh_frame` | `0x4f1c` | `0x4eac` | **`-0x70`** |
| `__DATA.__data` | `0x1a98` | `0x1a48` | **`-0x50`** |
| `__TEXT.__const` | `0xb354` | `0xb394` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2348` | `0x2378` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x2ed2` | `0x2efe` | **`+0x2c`** |
| `__TEXT.__constg_swiftt` | `0x211c` | `0x2144` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x2984` | `0x29ac` | **`+0x28`** |
| `__AUTH.__data` | `0x820` | `0x800` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa78` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x16c0` | `0x16d8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3160` | `0x3168` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x360` | `0x364` | **`+0x4`** |

### Other Changes

```diff

-284.0.7.0.0
+287.0.6.0.0

+  - /System/Library/Frameworks/Security.framework/Security

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 5807
-  Symbols:   248
-  CStrings:  474
+  Functions: 5834
+  Symbols:   255
+  CStrings:  492
Symbols:
+ _SecKeyCreateWithData
+ _SecKeyVerifySignature
+ _kSecAttrKeyClass
+ _kSecAttrKeyClassPublic
+ _kSecAttrKeyType
+ _kSecAttrKeyTypeRSA
+ _kSecKeyAlgorithmRSASignatureMessagePKCS1v15SHA256
+ _objc_retain_x23
+ _objc_retain_x26
+ _swift_unexpectedError
- _CFPreferencesCopyValue
- _getpwuid
- _kCFPreferencesCurrentHost
CStrings:
+ "Forced waitlist profile override has no attestation; rejecting"
+ "Forced waitlist profile override is set but payload is absent or not Data; rejecting"
+ "Forced waitlist profile override payload verified but is not a decodable WaitlistStatus.Value"
+ "Forced waitlist profile override signature invalid; rejecting"
+ "Forced waitlist profile override verified but value is not .accepted; ignoring"
+ "Forced waitlist profile override verified; honoring .accepted"
+ "MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAuuoHJarXiW7YiznhKWr4lYAasR4U+Npcx40Qmr7dR5vmOXFLKP4ivBqn8a5mtb7GIc9siLEqeBKCZBw0+eyQ9QKua5Uo5H+NguS9FWskFPuuZv/NjEWQ2s9FoqaA0t7s8X2FsKQCPAAE01HCCfm7HHjaWBqWtOguevYvZYc+/y54heeAXX407JBsDSqwiKTVN5hLxJXtpNDfjyrHIQZsluutsz5wqXdGNRTn3S1iWN55l30aOFR4MDgS2cprnuOcIu89W/4K2dIiZ7R1ttke4bRev+aWFBxtevgsjsRUXshHAdi1y+etcjNxwNkkeqvH2qxBIK8aSPzEzCjS797SeQIDAQAB"
+ "Migrating legacy forcedWaitlistStatus override → secureAvailabilityDomain (value=%{public}s)"
+ "Returning cached enhanced Siri availability."
+ "Returning cached enhanced Siri boot state."
+ "Returning cached enhancedSiriWasEverAvailable."
+ "Skipping legacy forcedWaitlistStatus override migration: failed to decode legacy data"
+ "com.apple.gms.availability.forcedWaitlistStatus.attestation"
+ "com.apple.gms.availability.secureForcedWaitlistStatusOverride"
+ "forcedWaitlistStatus: %{public}s (MDM profile)"
+ "forcedWaitlistStatus: %{public}s (gmstool override)"
+ "forcedWaitlistStatus: nil"
+ "setSecureForcedWaitlistStatusOverride: not allowed on non-internal builds"
```
