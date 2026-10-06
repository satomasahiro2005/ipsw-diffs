## afktool

> `/usr/bin/afktool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x839c` | `0x795c` | **`-0xa40`** |
| `__TEXT.__auth_stubs` | `0x7f0` | `0x710` | **`-0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x1004` | `0xf84` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0x408` | `0x398` | **`-0x70`** |
| `__TEXT.__cstring` | `0xf9f` | `0xff5` | **`+0x56`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x250` | **`-0x50`** |
| `__TEXT.__objc_methname` | `0x5a2` | `0x55f` | **`-0x43`** |
| `__DATA_CONST.__cfstring` | `0xa80` | `0xac0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x800` | `0x7c0` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x330` | `0x300` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x2d` | `0x3` | **`-0x2a`** |
| `__DATA_CONST.__got` | `0x148` | `0x120` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x200` | `0x1f0` | **`-0x10`** |
| `__TEXT.__const` | `0x30` | `0x28` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-743.40.3.0.0
+743.40.4.0.0

-  Functions: 86
-  Symbols:   176
-  CStrings:  233
+  Functions: 81
+  Symbols:   157
+  CStrings:  231
Symbols:
+ _AFKUserRegistryFromSerializedServices
+ _IOCFUnserializeBinary
+ _kAFKEventCancel
- _CFArrayAppendValue
- _CFArrayCreateMutable
- _CFDataCreate
- _CFDictionaryCreateMutable
- _CFDictionarySetValue
- _CFNumberCreate
- _CFRelease
- _CFRetain
- _CFSetAddValue
- _CFSetCreateMutable
- _CFStringCreateWithBytes
- _IOCFUnserializeWithSize
- __os_log_fault_impl
- _kCFBooleanFalse
- _kCFBooleanTrue
- _kCFTypeArrayCallBacks
- _kCFTypeDictionaryKeyCallBacks
- _kCFTypeDictionaryValueCallBacks
- _kCFTypeSetCallBacks
- _malloc_type_calloc
- _objc_storeStrong
- _syslog
CStrings:
+ "AppleFirmwareKit ToolvRC_ProjectBuildVersion Sep 27 2026 20:36:23"
+ "Could not build a registry from the captured services"
+ "Could not open an AFK Endpoint Interface"
+ "ERROR! Unserialize registry dump for service:0x%llx type:%@"
+ "Registry dump did not unserialize to a dictionary"
+ "setEventHandler:"
+ "v32@?0@\"AFKEndpointInterface\"8@\"NSString\"16@24"
- "0x%llx: AFKIOCFUnserializeWithSize failed"
- "AFKRootService"
- "AppleFirmwareKit ToolvRC_ProjectBuildVersion Sep 12 2026 04:49:29"
- "ERROR! Unserialize registry dump for service:0x%llx error:%@"
- "FIXME: IOUnserialize has detected a string that is not valid UTF-8, \"%s\"."
- "enumerateObjectsUsingBlock:"
- "objectAtIndexedSubscript:"
- "setObject:atIndexedSubscript:"
- "v32@?0@8Q16^B24"
```
