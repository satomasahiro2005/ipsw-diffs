## locationd

> `/usr/libexec/locationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b31fd0` | `0x1b32530` | **`+0x560`** |
| `__TEXT.__oslogstring` | `0x29376c` | `0x29395c` | **`+0x1f0`** |
| `__TEXT.__gcc_except_tab` | `0xdaaf0` | `0xdab38` | **`+0x48`** |
| `__TEXT.__cstring` | `0x2115ae` | `0x2115de` | **`+0x30`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  85429
+  CStrings:  85434
Functions:
~ sub_100037940 : 5324 -> 5832
~ sub_10015c838 -> sub_10015ca34 : 1344 -> 1796
~ sub_100c291f4 -> sub_100c295b4 : 1448 -> 1864
CStrings:
+ "#CoreLocationAgent ignoring a disconnection from a connection that does not hold the agent slot"
+ "#CoreLocationAgent rejecting an unentitled connection"
+ "21:38:13"
+ "21:44:54"
+ "Oct 13 2026"
+ "Oct 13 2026 21:41:52"
+ "com.apple.private.locationd.corelocationagent"
+ "{\"msg%{public}.0s\":\"#CoreLocationAgent ignoring a disconnection from a connection that does not hold the agent slot\", \"UserName\":%{public, location:escape_only}s, \"Connection\":%{public, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#CoreLocationAgent rejecting an unentitled connection\", \"Connection\":%{public, location:escape_only}s, \"PID\":%{public}d}"
- "01:48:49"
- "02:00:00"
- "Oct 10 2026"
- "Oct 10 2026 01:54:15"
```
