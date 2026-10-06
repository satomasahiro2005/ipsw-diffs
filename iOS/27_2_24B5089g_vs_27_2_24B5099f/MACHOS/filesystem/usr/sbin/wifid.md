## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c40e0` | `0x1c4388` | **`+0x2a8`** |
| `__TEXT.__cstring` | `0x75dc8` | `0x75e30` | **`+0x68`** |
| `__TEXT.__ustring` | `0x63e` | `0x5e6` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x45b0` | `0x45b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2029.6.0.0.0
+2029.9.0.0.0

-  Functions: 8779
+  Functions: 8819

-  CStrings:  17384
+  CStrings:  17387
CStrings:
+ "%s: hosted network %@ channel -> %d"
+ "6GHz Network Not Supported"
+ "Connect to “%@” to set up Home Theater."
+ "MusicHandoffScan"
+ "WiFiManager-2029.9 Sep 27 2026 23:38:55"
+ "WiFiManager-2029.9 Sep 27 2026 23:40:00"
+ "__WiFiDeviceManagerUpdateHostedNetworkChannel"
- "5GHz Network Required"
- "Home Theater requires a 5GHz Wi-Fi connection. Connect to “%@”, or use TV speakers."
- "WiFiManager-2029.6 Sep 14 2026 20:58:14"
- "WiFiManager-2029.6 Sep 14 2026 20:59:13"
```
