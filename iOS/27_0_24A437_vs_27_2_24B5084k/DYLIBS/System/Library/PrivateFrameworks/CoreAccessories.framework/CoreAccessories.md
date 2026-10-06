## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26e4c` | `0x27350` | **`+0x504`** |
| `__TEXT.__oslogstring` | `0x4146` | `0x41b3` | **`+0x6d`** |
| `__TEXT.__objc_methlist` | `0x19bc` | `0x19cc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa60` | `0xa70` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x2368` | `0x2370` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xf58` | `0xf60` | **`+0x8`** |

### Other Changes

```diff

-1216.2.2.0.0
+1219.40.5.0.0

-  Functions: 832
-  Symbols:   1897
-  CStrings:  879
+  Functions: 836
+  Symbols:   1900
+  CStrings:  881
Symbols:
+ -[ACCHWComponentAuth signTouchControllerChallenge:completionHandler:componentIndex:]
+ ___84-[ACCHWComponentAuth signTouchControllerChallenge:completionHandler:componentIndex:]_block_invoke
+ ___84-[ACCHWComponentAuth signTouchControllerChallenge:completionHandler:componentIndex:]_block_invoke_2
CStrings:
+ "Signing touch controller challenge... (completionHandler: %s)"
+ "signed touch controller challenge authError %d"
```
