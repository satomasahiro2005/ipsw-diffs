## terminusd

> `/usr/libexec/terminusd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2016ac` | `0x2017fc` | **`+0x150`** |
| `__TEXT.__cstring` | `0x52a43` | `0x52a9a` | **`+0x57`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-914.40.22.0.0
+914.40.23.0.0

-  Functions: 3908
+  Functions: 3909

-  CStrings:  11629
+  CStrings:  11630
CStrings:
+ "%s%.30s:%-4d Not marking %@ as my distributee: link type is Infra Relay"
+ "%s%.30s:%-4d Not marking %@ as my distributee: we are locally on %@ infrastructure Wi-Fi or Infra Relay"
+ "20:18:05"
+ "914.40.23"
+ "Sep 13 2026"
- "%s%.30s:%-4d Not marking %@ as my distributee: we are locally on %@ infrastructure Wi-Fi"
- "20:54:24"
- "914.40.22"
- "Sep  9 2026"
```
