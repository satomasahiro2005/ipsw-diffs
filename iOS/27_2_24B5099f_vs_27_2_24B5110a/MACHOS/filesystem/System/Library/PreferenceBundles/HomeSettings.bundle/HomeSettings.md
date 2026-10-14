## HomeSettings

> `/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a00` | `0x5b3c` | **`+0x13c`** |
| `__DATA_CONST.__cfstring` | `0x14a0` | `0x1560` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x128c` | `0x1312` | **`+0x86`** |
| `__TEXT.__objc_methname` | `0x2c25` | `0x2c76` | **`+0x51`** |
| `__TEXT.__objc_stubs` | `0x1920` | `0x1940` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x470` | `0x488` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x78` | `0x90` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xc58` | `0xc68` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xc24` | `0xc34` | **`+0x10`** |
| `__DATA.__objc_const` | `0xa20` | `0xa28` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x128` | `0x130` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1269.2.3.0.1
+1269.2.5.1.4

-  Symbols:   228
-  CStrings:  688
+  Symbols:   231
+  CStrings:  696
Symbols:
+ _HFPreferencesForceInstallationInstructionsKey
+ _HFPreferencesLocalExtensionNameMatchingKey
+ _HFPreferencesSkipInstalledExtensionKey
+ _OBJC_CLASS_$_HMAccessory
- ___NSArray0__struct
Functions:
~ sub_30c8 : 388 -> 424
~ sub_4bbc -> sub_4be0 : 6032 -> 6312
CStrings:
+ "%@"
+ "Extensibility"
+ "Force Installation Instructions"
+ "HOSHomeHubFooter_J490"
+ "HOSSensitiveStrings-J490"
+ "Local Extension Name Matching"
+ "Skip Installed Extension"
+ "hf_homeAccessoryProductName"
+ "homeDidSetHasOwnerAcknowledgedHomePodSiriOnboarding:"
- "HOSHomeHubFooter"
```
