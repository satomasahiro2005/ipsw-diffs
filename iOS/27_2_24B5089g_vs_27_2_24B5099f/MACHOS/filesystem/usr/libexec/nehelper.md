## nehelper

> `/usr/libexec/nehelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2588c` | `0x265d4` | **`+0xd48`** |
| `__TEXT.__oslogstring` | `0x4ac1` | `0x4d0a` | **`+0x249`** |
| `__DATA_CONST.__const` | `0xcf0` | `0xd90` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x7f8` | `0x894` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x5ff2` | `0x606f` | **`+0x7d`** |
| `__TEXT.__objc_methname` | `0x1fc7` | `0x1fed` | **`+0x26`** |
| `__DATA_CONST.__cfstring` | `0x51c0` | `0x51e0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2a80` | `0x2aa0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x410` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xb40` | `0xb48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2365.40.1.0.0
+2365.40.3.0.1

-  Functions: 248
+  Functions: 254

-  CStrings:  1707
+  CStrings:  1725
CStrings:
+ "%@ sent an app replacement request without both bundle identifiers"
+ "(none)"
+ "App replacement failed: %@"
+ "App replacement succeeded, sending reply"
+ "Calling [NEHelperConfigurationManager handleAppReplacementFromBundleID:toBundleID:completionHandler:] for app replacement"
+ "Failed to load configurations for app replacement: %@"
+ "Failed to save configuration %@ after app replacement: %@"
+ "Handling app replacement from %@ to %@"
+ "Skipping cellular usage configuration during app replacement"
+ "Source persona: %@, destination persona: %@"
+ "Successfully updated configuration %@ for app replacement from %@ to %@"
+ "destination-bundle-id"
+ "destination-persona"
+ "handle-app-replacement"
+ "replaceProviderBundleIdentifier:with:"
+ "source-bundle-id"
+ "source-persona"
+ "v20@?0B8@\"NSError\"12"
```
