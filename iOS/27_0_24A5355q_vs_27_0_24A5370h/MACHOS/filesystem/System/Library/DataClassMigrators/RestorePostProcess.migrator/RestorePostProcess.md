## RestorePostProcess

> `/System/Library/DataClassMigrators/RestorePostProcess.migrator/RestorePostProcess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x1400` | `0x15a0` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x2b4` | `0x1ec` | **`-0xc8`** |
| `__DATA.__objc_data` | `0x4e0` | `0x580` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xc8c` | `0xcec` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x25a0` | `0x2600` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x2e2b` | `0x2e81` | **`+0x56`** |
| `__DATA_CONST.__cfstring` | `0xf00` | `0xec0` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0xaf0` | `0xab0` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x639` | `0x669` | **`+0x30`** |
| `__TEXT.__text` | `0x11c48` | `0x11c1c` | **`-0x2c`** |
| `__DATA.__objc_selrefs` | `0xc80` | `0xca8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x588` | `0x568` | **`-0x20`** |
| `__TEXT.__cstring` | `0x373b` | `0x371b` | **`-0x20`** |
| `__TEXT.__objc_classname` | `0x187` | `0x1a7` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x78` | `0x88` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x270` | `0x268` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3033.0.0.0.0
+3036.0.0.0.0

-  Functions: 327
-  Symbols:   295
-  CStrings:  922
+  Functions: 334
+  Symbols:   294
+  CStrings:  934
Symbols:
+ _OBJC_CLASS_$_MBAtomicBool
+ _OBJC_CLASS_$_MBAtomicULong
+ _OBJC_METACLASS_$_MBAtomicBool
+ _OBJC_METACLASS_$_MBAtomicULong
- _ACAccountStoreDidChangeNotification
- _CFNotificationCenterPostNotificationWithOptions
- _CFPreferencesAppSynchronize
- _CFPreferencesSetAppValue
- _objc_retain_x27
CStrings:
+ "@20@0:8B16"
+ "AB"
+ "AQ"
+ "MBAtomicBool"
+ "MBAtomicULong"
+ "Q24@0:8Q16"
+ "TB,N"
+ "TQ,R,N"
+ "exchange:"
+ "fetchAdd:"
+ "increment"
+ "initWithInitialValue:"
+ "setValue:"
+ "v20@0:8B16"
+ "value"
- "IsEnabled"
- "com.apple.MobileBackup"
- "enableBackupInPreferences"
```
