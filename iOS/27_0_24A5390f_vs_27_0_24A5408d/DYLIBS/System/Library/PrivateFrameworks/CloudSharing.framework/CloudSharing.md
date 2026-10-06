## CloudSharing

> `/System/Library/PrivateFrameworks/CloudSharing.framework/CloudSharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38d94` | `0x39bd8` | **`+0xe44`** |
| `__TEXT.__oslogstring` | `0xee4` | `0x1054` | **`+0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b0` | `0x438` | **`+0x88`** |
| `__TEXT.__cstring` | `0xb7` | `0xf7` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4f8` | `0x530` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x410` | `0x430` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x518` | `0x528` | **`+0x10`** |
| `__DATA.__data` | `0x178` | `0x188` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe8` | `0xf8` | **`+0x10`** |
| `__TEXT.__const` | `0x37c` | `0x38c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x443` | `0x453` | **`+0x10`** |

### Other Changes

```diff

-236.0.0.0.0
+240.0.0.0.0
+  - /System/Library/Frameworks/Accounts.framework/Accounts

+  - /System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs

+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreAudio.dylib

-  Functions: 865
-  Symbols:   273
-  CStrings:  81
+  Functions: 875
+  Symbols:   286
+  CStrings:  87
Symbols:
+ +[CSCloudSharing isManagedAppleAccountOwnerForFileOrFolderURL:]
+ +[CSCloudSharing isManagedAppleAccountOwnerForShare:containerSetupInfo:]
+ _OBJC_CLASS_$_ACAccountStore
+ _OBJC_CLASS_$_BRAccountDescriptor
+ __CLASS_METHODS__TtC12CloudSharing15InitiateSharing
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_CloudSharing
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_CloudSharing
+ _objc_retain_x2
+ _swift_arrayInitWithCopy
+ _symbolic SSSg
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
CStrings:
+ "containerOverride.accountID"
+ "containerOverride.altDSID"
+ "isManagedAppleAccountOwner: %{bool}d (source: %s, accountResolved: %{bool}d)"
+ "isManagedAppleAccountOwner: false (source: containerOverride, no accountID or altDSID)"
+ "isManagedAppleAccountOwner: false (source: none, no owner handle or container override)"
+ "isManagedAppleAccountOwner: owner handle not resolvable on device; trying container override"
```
