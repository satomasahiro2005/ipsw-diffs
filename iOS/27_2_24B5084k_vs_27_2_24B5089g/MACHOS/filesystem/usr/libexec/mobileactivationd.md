## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c2ac` | `0x34c2bc` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.40.4.0.0
+1145.40.5.0.0
Functions:
~ _X509ExtensionParseBasicConstraints : 208 -> 212
~ _X509ChainBuildPathPartial : 488 -> 500
CStrings:
+ "1145.40.5"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.40.5 built on Sep 13 2026 at 20:09:15)"
+ "iOS Device Activator (MobileActivation-1145.40.5)"
- "1145.40.4"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-1145.40.4 built on Sep  4 2026 at 20:39:10)"
- "iOS Device Activator (MobileActivation-1145.40.4)"
```
