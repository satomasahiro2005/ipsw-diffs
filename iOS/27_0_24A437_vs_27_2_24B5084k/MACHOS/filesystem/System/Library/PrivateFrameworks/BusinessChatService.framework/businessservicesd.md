## businessservicesd

> `/System/Library/PrivateFrameworks/BusinessChatService.framework/businessservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d064` | `0x1fb58` | **`+0x2af4`** |
| `__TEXT.__oslogstring` | `0x8ce` | `0xb3e` | **`+0x270`** |
| `__TEXT.__eh_frame` | `0x1010` | `0xee0` | **`-0x130`** |
| `__DATA_CONST.__const` | `0xa60` | `0xab0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x32c` | `0x374` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x761` | `0x78b` | **`+0x2a`** |
| `__TEXT.__const` | `0xcb0` | `0xcd0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6b8` | `0x698` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x11f0` | `0x1200` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x80` | `0x74` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x900` | `0x908` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x60` | `0x58` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x64` | `0x60` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-30123.30.6.2.1
+30123.31.8.11.3

-  Functions: 468
-  Symbols:   471
-  CStrings:  353
+  Functions: 469
+  Symbols:   472
+  CStrings:  360
Symbols:
+ _objc_retain_x27
CStrings:
+ "Asset found in cache. Returning cached data."
+ "Failed to fetch asset of type %ld for brandURI %{private}s from local cache using SIM %{private}s"
+ "Failed to fetch asset of type %ld for brandURI %{private}s from remote source using SIM %{private}s"
+ "Fetching assetData for brandURI %s with URL %{private}s of type %ld"
+ "No network data source found for brand %{private}s"
+ "Successfully fetched asset of type %ld for brandURI %{private}s from remote source of size %ld using SIM %{private}s"
+ "Successfully saved asset of type %ld for brandURI %{private}s to local cache of size %ld using SIM %{private}s"
+ "assetData() The brand %s is using the URL scheme which is not supported. URL: %{private}s"
+ "assetData() called with no audit token. URL: %{private}s"
+ "assetData() called with no entitlement. URL: %{private}s"
- "Fetching assetData for brandURI %s with URL %s of type %ld"
- "Successfully fetched asset of type %ld from remote source of size %ld using SIM %s"
- "assetData() The brand %s is using the URL scheme which is not supported. URL: %s"
```
