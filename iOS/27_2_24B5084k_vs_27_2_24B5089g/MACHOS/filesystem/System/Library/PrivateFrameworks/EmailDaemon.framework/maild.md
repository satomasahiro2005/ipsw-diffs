## maild

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/maild`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1528f8` | `0x152748` | **`-0x1b0`** |
| `__TEXT.__objc_methname` | `0x1ce75` | `0x1cef5` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x196a4` | `0x1962c` | **`-0x78`** |
| `__DATA.__objc_const` | `0x12de0` | `0x12e18` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x164c0` | `0x164e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6f50` | `0x6f38` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0xae34` | `0xae24` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x7000` | `0x7008` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1840` | `0x1848` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb90` | `0xb94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 5875
+  Functions: 5874

-  CStrings:  7514
+  CStrings:  7516
CStrings:
+ "ServerSearch"
+ "T@\"<EMVIPManager>\",R,V_vipManager"
+ "initWithDelegate:vipManager:mailboxes:searchContext:"
+ "initWithMessagePersistence:vipManager:"
+ "initWithVIPManager:"
+ "mailServerSideCriterionWithVIPManager:"
- "MobileMail"
- "allVIPEmailAddressesCriterion"
- "initWithDelegate:mailboxes:searchContext:"
- "mailServerSideCriterion"
```
