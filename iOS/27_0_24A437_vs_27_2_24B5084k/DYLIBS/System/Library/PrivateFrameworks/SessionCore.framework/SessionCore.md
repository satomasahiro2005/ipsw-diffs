## SessionCore

> `/System/Library/PrivateFrameworks/SessionCore.framework/SessionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d664` | `0x14f458` | **`+0x1df4`** |
| `__DATA.__bss` | `0x2100` | `0x2280` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x7914` | `0x7a54` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x3700` | `0x3818` | **`+0x118`** |
| `__TEXT.__const` | `0x5552` | `0x5612` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x60e0` | `0x6198` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x1da8` | `0x1de8` | **`+0x40`** |
| `__DATA.__data` | `0x19d0` | `0x1a10` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3572` | `0x35b2` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xec4` | `0xefc` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2640` | `0x2678` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x878` | `0x8a8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2ca7` | `0x2cd7` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x467c` | `0x46a8` | **`+0x2c`** |
| `__TEXT.__swift5_fieldmd` | `0x2d08` | `0x2d30` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x2dcf` | `0x2df5` | **`+0x26`** |
| `__DATA_DIRTY.__data` | `0x70d8` | `0x70f8` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xc9c0` | `0xc9d8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x364` | `0x370` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x298` | `0x29c` | **`+0x4`** |

### Other Changes

```diff

-312.100.0.0.0
+313.2.3.0.0

-  Functions: 3557
-  Symbols:   1751
-  CStrings:  839
+  Functions: 3579
+  Symbols:   1756
+  CStrings:  846
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _associated conformance 11SessionCore20AuthorizationManagerC0cD5ErrorOSHAASQ
+ _symbolic Say_____G 11ActivityKit04LiveA17ApplicationRecordV
+ _symbolic _____ 11SessionCore20AuthorizationManagerC0cD5ErrorO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11ActivityKit04LiveD17ApplicationRecordV
CStrings:
+ "Failed to encode live activity application records: %@"
+ "NSLiveActivityDisplayName"
+ "New bundle ID %{public}s does not support Live Activities"
+ "Replacing %{public}s with %{public}s"
+ "The requesting process is not entitled to make this request"
+ "The requesting process is not entitled to replace bundle IDs"
+ "The requesting process is not entitled to request live activity records"
+ "com.apple.private.activitykit.bundleIDReplacer"
- "The requesting process is not entitled to set activities authorization"
```
