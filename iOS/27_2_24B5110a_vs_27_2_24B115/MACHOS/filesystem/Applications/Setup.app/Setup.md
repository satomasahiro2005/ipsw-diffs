## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25cd64` | `0x25cdf4` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x41276` | `0x412b6` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x159c9` | `0x1599f` | **`-0x2a`** |
| `__TEXT.__objc_stubs` | `0x29860` | `0x29880` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c50` | `0x1c60` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xce60` | `0xce68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa228` | `0xa230` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5411.2.4.0.0
+5411.2.5.0.0

-  Symbols:   1548
+  Symbols:   1550
Symbols:
+ _BYPrivacySubscriptionBundleIdentifier
+ _OBJC_CLASS_$_AMSAcknowledgePrivacyTask
Functions:
~ sub_100004e28 : 24 -> 328
~ sub_100111838 -> sub_100111968 : 764 -> 612
~ sub_1001592dc -> sub_100159374 : 348 -> 340
CStrings:
+ "Oct 12 2026"
+ "acknowledgementNeededForPrivacyIdentifier:account:"
+ "ams_isBundleOwner"
- "Enabling D&U submission for seed build..."
- "Oct  4 2026"
- "setBoolValue:forSetting:"
```
