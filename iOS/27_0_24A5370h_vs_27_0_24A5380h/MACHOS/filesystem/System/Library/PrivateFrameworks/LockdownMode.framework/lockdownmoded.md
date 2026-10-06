## lockdownmoded

> `/System/Library/PrivateFrameworks/LockdownMode.framework/lockdownmoded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f490` | `0x3f620` | **`+0x190`** |
| `__TEXT.__cstring` | `0x10e1` | `0x11a1` | **`+0xc0`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x4a0` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x1520` | `0x1510` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x928` | `0x938` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xaa0` | `0xa98` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-128.0.3.0.0
+128.0.4.0.0

-  Functions: 773
-  Symbols:   606
-  CStrings:  668
+  Functions: 774
+  Symbols:   603
+  CStrings:  670
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_willThrowTypedImpl
CStrings:
+ "CONTACT_NAME_FORMAT"
+ "Wraps a single contact display name with locale-appropriate honorifics (e.g. Japanese 「さん」, Korean 「씨」, Vietnamese 「anh/chị」), if any"
```
