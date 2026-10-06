## appconduitd

> `/System/Library/PrivateFrameworks/AppConduit.framework/Support/appconduitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59a34` | `0x59b6c` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0xbe9a` | `0xbf49` | **`+0xaf`** |
| `__TEXT.__objc_stubs` | `0x7fc0` | `0x8060` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x14e7e` | `0x14efd` | **`+0x7f`** |
| `__TEXT.__oslogstring` | `0x1a0` | `0x1ea` | **`+0x4a`** |
| `__DATA_CONST.__cfstring` | `0x9380` | `0x93c0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x25e8` | `0x2610` | **`+0x28`** |
| `__DATA.__objc_const` | `0x8ae8` | `0x8b08` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3c74` | `0x3c8c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x12a0` | `0x1290` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x18f8` | `0x1900` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |
| `__TEXT.__const` | `0xc8` | `0xd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-405.0.0.0.0
+408.0.0.0.0

-  Functions: 1599
-  Symbols:   302
-  CStrings:  3653
+  Functions: 1602
+  Symbols:   303
+  CStrings:  3661
Symbols:
+ _OBJC_CLASS_$_ACXFeatureFlags
CStrings:
+ "ACX_isDeletable"
+ "ACX_isDeletableSystemApp"
+ "Failed to post restricted distributed notification %{public}@: %{public}@"
+ "Jul 10 2026"
+ "Posting restricted distributed notification %@ with payload %@"
+ "Posting unrestricted distributed notification %@ with payload %@"
+ "bundleContainerURL"
+ "com.apple.appconduit.remote-app-notifications.read"
+ "postNotificationName:object:userInfo:audience:entitlement:options:error:"
+ "restrictedDistributedNotificationsEnabled"
- "Jun 26 2026"
- "Posting distributed notification %@ with payload %@"
```
