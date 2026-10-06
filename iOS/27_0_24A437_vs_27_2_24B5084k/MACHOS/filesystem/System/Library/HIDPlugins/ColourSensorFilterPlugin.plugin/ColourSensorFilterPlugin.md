## ColourSensorFilterPlugin

> `/System/Library/HIDPlugins/ColourSensorFilterPlugin.plugin/ColourSensorFilterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fd4c` | `0x40448` | **`+0x6fc`** |
| `__TEXT.__gcc_except_tab` | `0xe64` | `0xfbc` | **`+0x158`** |
| `__TEXT.__objc_stubs` | `—` | `0x100` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x14d0` | `0x1570` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x98` | `0x12b` | **`+0x93`** |
| `__DATA_CONST.__auth_got` | `0xa78` | `0xad0` | **`+0x58`** |
| `__DATA.__objc_selrefs` | `—` | `0x40` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xfb8` | `0xff0` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x298` | `0x2b0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2300.2.9.0.0
+2300.40.37.0.0

-  Functions: 1316
-  Symbols:   448
-  CStrings:  633
+  Functions: 1320
+  Symbols:   466
+  CStrings:  641
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_NSUserDefaults
+ _interpolate_value_in_table
+ _load_mapping_table_from_defaults
+ _mapping_table_is_valid
+ _objc_alloc
+ _objc_claimAutoreleasedReturnValue
+ _objc_enumerationMutation
+ _objc_msgSend
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_release_x25
+ _objc_release_x8
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x19
+ _objc_retain_x20
+ _save_mapping_table_to_defaults
CStrings:
+ "arrayForKey:"
+ "count"
+ "countByEnumeratingWithState:objects:count:"
+ "floatValue"
+ "initWithSuiteName:"
+ "objectAtIndexedSubscript:"
+ "setObject:forKey:"
+ "synchronize"
```
