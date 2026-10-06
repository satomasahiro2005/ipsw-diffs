## CoreIDVShared

> `/System/Library/PrivateFrameworks/CoreIDVShared.framework/CoreIDVShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x241430` | `0x241db4` | **`+0x984`** |
| `__TEXT.__oslogstring` | `0x4930` | `0x4a00` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x169fe` | `0x169de` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2220` | `0x2210` | **`-0x10`** |
| `__DATA.__data` | `0x6e88` | `0x6e78` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x9378` | `0x9370` | **`-0x8`** |

### Other Changes

```diff

-9.36.0.0.0
+9.38.0.0.0

-  Functions: 13945
-  Symbols:   4070
-  CStrings:  2625
+  Functions: 13943
+  Symbols:   4069
+  CStrings:  2629
Symbols:
- _symbolic ______p s19_HasContiguousBytesP
CStrings:
+ "CIDVRGB.simulate-disk-full"
+ "COSE_Sign1 binary decode failed, attempting hex decode: %@"
+ "COSE_Sign1 decoded from binary payload"
+ "COSE_Sign1 decoded from hex-encoded payload"
+ "COSE_Sign1 hex decode also failed: %@"
+ "full_name"
+ "init(fromHexOrBinaryData:)"
- "Could not parse HEX Data"
- "debug.enable-text-understanding-verbose-logging"
- "init(fromHexData:)"
```
