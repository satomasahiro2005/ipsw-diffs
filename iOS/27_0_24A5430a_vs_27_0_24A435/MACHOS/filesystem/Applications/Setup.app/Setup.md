## Setup

> `/Applications/Setup.app/Setup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24cefc` | `0x24cfc4` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x14eec` | `0x14ec2` | **`-0x2a`** |
| `__TEXT.__objc_methname` | `0x40a3e` | `0x40a5e` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x29420` | `0x29440` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c48` | `0x1c58` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xcd18` | `0xcd20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1535
+  Symbols:   1537
Symbols:
+ _BYPrivacySubscriptionBundleIdentifier
+ _OBJC_CLASS_$_AMSAcknowledgePrivacyTask
Functions:
~ sub_100004e70 : 24 -> 328
~ sub_1001105f0 -> sub_100110720 : 764 -> 612
~ sub_100157bd4 -> sub_100157c6c : 348 -> 340
~ sub_100178d48 -> sub_100178dd8 : 116 -> 124
~ sub_100179ad0 -> sub_100179b68 : 108 -> 116
~ sub_10017d38c -> sub_10017d42c : 116 -> 124
~ sub_10017e100 -> sub_10017e1a8 : 116 -> 124
~ sub_100218728 -> sub_1002187d8 : 1504 -> 1508
~ sub_100227634 -> sub_1002276e8 : 672 -> 676
~ sub_100229c80 -> sub_100229d38 : 1928 -> 1936
~ sub_10022a5f0 -> sub_10022a6b0 : 752 -> 756
~ sub_10022b69c -> sub_10022b760 : 360 -> 364
CStrings:
+ "acknowledgementNeededForPrivacyIdentifier:account:"
+ "ams_isBundleOwner"
- "Enabling D&U submission for seed build..."
- "setBoolValue:forSetting:"
```
