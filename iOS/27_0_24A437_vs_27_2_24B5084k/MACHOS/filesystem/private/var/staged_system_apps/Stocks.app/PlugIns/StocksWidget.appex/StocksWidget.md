## StocksWidget

> `/private/var/staged_system_apps/Stocks.app/PlugIns/StocksWidget.appex/StocksWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdb8a0` | `0xdc1a4` | **`+0x904`** |
| `__TEXT.__oslogstring` | `0x181f` | `0x1c0f` | **`+0x3f0`** |
| `__TEXT.__eh_frame` | `0x43e0` | `0x4298` | **`-0x148`** |
| `__TEXT.__cstring` | `0x2138` | `0x2188` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x4730` | `0x4770` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3448` | `0x3418` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x4290` | `0x42b8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x387b` | `0x389d` | **`+0x22`** |
| `__DATA_CONST.__auth_got` | `0x23a0` | `0x23c0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x518` | `0x538` | **`+0x20`** |
| `__DATA.__objc_const` | `0x39a8` | `0x39c0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1310` | `0x12f8` | **`-0x18`** |
| `__DATA.__bss` | `0xd440` | `0xd430` | **`-0x10`** |
| `__DATA.__data` | `0x7b88` | `0x7b78` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x1498` | `0x1488` | **`-0x10`** |
| `__TEXT.__const` | `0x9a44` | `0x9a34` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x2f4a` | `0x2f3a` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xba0` | `0xba8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xfc4` | `0xfcc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2028.1.0.0.0
+2056.0.0.0.0

-  Functions: 4623
+  Functions: 4617

-  CStrings:  1002
+  CStrings:  1012
CStrings:
+ ", cap AI-generated at "
+ "Dropping headline without source: %{public}s. id=%{public}s"
+ "Dropping headline without title: %{public}s. id=%{public}s"
+ "Filter step [%{public}s] kept %{public}ld of %{public}ld headlines; dropped=[%{public}s]. id=%{public}s"
+ "Filter step [%{public}s] kept all %{public}ld headlines. id=%{public}s"
+ "Only %{public}ld headlines after filtering (< maxCount %{public}ld); padding with %{public}ld press-release headlines to avoid blank slots. id=%{public}s"
+ "Prioritizing unseen headlines: %{public}ld unseen kept ahead of %{public}ld previously-seen (moved to end). movedToEnd=[%{public}s]. id=%{public}s"
+ "Selected %{public}ld candidate headlines (display up to %{public}ld after validation), ordered=[%{public}s]. id=%{public}s"
+ "Selecting headlines for symbol=%{public}s, maxCount=%{public}ld from %{public}ld mandatory + %{public}ld feed headlines. id=%{public}s"
+ "Selecting headlines for symbols=[%{public}s], totalMaxCount=%{public}ld, desiredPerStock=%{public}ld from %{public}ld favored + %{public}ld disfavored (overflow) headlines. id=%{public}s"
+ "drop duplicate/clustered/press-release articles"
+ "publisherGroupEngagement"
- "Dropping headline without source: %s. id=%s"
- "Dropping headline without title: %s. id=%s"
```
