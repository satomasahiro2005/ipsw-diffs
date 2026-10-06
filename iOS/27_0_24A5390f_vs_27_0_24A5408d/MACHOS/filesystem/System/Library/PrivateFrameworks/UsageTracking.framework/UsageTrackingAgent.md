## UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0xdc0` | `0xe60` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1854` | `0x18d4` | **`+0x80`** |
| `__TEXT.__text` | `0x73810` | `0x73854` | **`+0x44`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-406.0.0.0.0
+407.0.0.0.0

-  CStrings:  1479
+  CStrings:  1484
Functions:
~ sub_10000d538 : 3280 -> 3348
CStrings:
+ "events.budgetedApplications"
+ "events.budgetedCategories"
+ "events.budgetedWebDomains"
+ "events.exemptApplications"
+ "events.exemptWebDomains"
```
