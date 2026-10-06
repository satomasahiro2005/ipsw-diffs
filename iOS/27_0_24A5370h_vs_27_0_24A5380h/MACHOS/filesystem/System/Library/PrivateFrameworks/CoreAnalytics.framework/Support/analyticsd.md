## analyticsd

> `/System/Library/PrivateFrameworks/CoreAnalytics.framework/Support/analyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1ace1` | `0x1adf9` | **`+0x118`** |
| `__TEXT.__cstring` | `0x153e9` | `0x154cb` | **`+0xe2`** |
| `__TEXT.__text` | `0x1338d0` | `0x1338fc` | **`+0x2c`** |
| `__TEXT.__gcc_except_tab` | `0x14558` | `0x14564` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x7d60` | `0x7d68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-559.0.0.502.1
+562.0.0.0.0

-  Functions: 6043
+  Functions: 6046

-  CStrings:  4025
+  CStrings:  4029
CStrings:
+ "CREATE INDEX IF NOT EXISTS IX_modify_eventdefs_modify_event_name ON modify_eventdefs(modify_event_name); CREATE INDEX IF NOT EXISTS IX_config_modify_eventdefs_modify_eventdef_id ON config_modify_eventdefs(modify_eventdef_id);"
+ "[Config Store] DATABASE INITIALIZATION: modifying for V12 schema - restoring modify-event lookup indices dropped in V9"
+ "[Config Store] ERROR: Failed to restore modify-eventdef lookup indices; %s"
+ "[Config Store] ERROR: Failed to restore modify-eventdef lookup indices[null database]"
```
