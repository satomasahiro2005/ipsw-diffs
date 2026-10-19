## activity

> `/System/Library/Assistant/Plugins/activity.assistantBundle/activity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c54` | `0x6400` | **`+0x7ac`** |
| `__DATA.__objc_const` | `0x1ac8` | `0x1f68` | **`+0x4a0`** |
| `__TEXT.__objc_methname` | `0x1181` | `0x12da` | **`+0x159`** |
| `__TEXT.__objc_stubs` | `0x18e0` | `0x1a20` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x400` | `0x4c0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x8be` | `0x955` | **`+0x97`** |
| `__TEXT.__objc_methlist` | `0x3e4` | `0x44c` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x708` | `0x768` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x231` | `0x250` | **`+0x1f`** |
| `__TEXT.__objc_classname` | `0x11e` | `0x137` | **`+0x19`** |
| `__DATA_CONST.__auth_got` | `0x168` | `0x180` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA.__objc_ivar` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x3db` | `0x3df` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`

### Other Changes

```diff

-  Functions: 79
-  Symbols:   154
-  CStrings:  351
+  Functions: 90
+  Symbols:   162
+  CStrings:  376
Symbols:
+ _OBJC_CLASS_$_ASRecordLocationActivity
+ _OBJC_CLASS_$_SARecordLocationActivity
+ _OBJC_CLASS_$__DKLocationApplicationActivityMetadataKey
+ _OBJC_METACLASS_$_ASRecordLocationActivity
+ _OBJC_METACLASS_$_SARecordLocationActivity
+ __os_log_debug_impl
+ _objc_opt_new
+ _objc_storeStrong
CStrings:
+ "%s "
+ "-[ASRecordLocationActivity recordLocationActivityWithCompletion:]"
+ ".cxx_destruct"
+ "/app/locationActivity"
+ "@\"ASRecordActivity\""
+ "ASRecordLocationActivity"
+ "Default"
+ "HomePod"
+ "Public"
+ "T@\"ASRecordActivity\",&,N,V_recordActivityCommand"
+ "_activityFromLocation:sourceType:"
+ "_locationMetadataFromLocation:"
+ "_recordActivityCommand"
+ "_recordActivityCommandFromLocation:sourceType:"
+ "com.apple.siri"
+ "com.apple.siri.homepod"
+ "location"
+ "locationName"
+ "recordActivityCommand"
+ "recordLocationActivityWithCompletion:"
+ "setActivity:"
+ "setRecordActivityCommand:"
+ "setVisibility:"
+ "sourceType"
+ "v24@0:8@16"
```
