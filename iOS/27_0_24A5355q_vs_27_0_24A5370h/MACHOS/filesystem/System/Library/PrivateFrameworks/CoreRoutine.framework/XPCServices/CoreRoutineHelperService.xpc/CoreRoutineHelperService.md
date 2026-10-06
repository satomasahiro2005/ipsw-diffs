## CoreRoutineHelperService

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/XPCServices/CoreRoutineHelperService.xpc/CoreRoutineHelperService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc21fc` | `0xc2af8` | **`+0x8fc`** |
| `__TEXT.__oslogstring` | `0x30d4` | `0x31a2` | **`+0xce`** |
| `__TEXT.__cstring` | `0x3ad91` | `0x3addf` | **`+0x4e`** |
| `__DATA_CONST.__cfstring` | `0x1fec0` | `0x1ff00` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0xc0` | `0xf0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xfc8` | `0xff0` | **`+0x28`** |
| `__DATA_CONST.__objc_doubleobj` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xf30` | `0xf40` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x3d11` | `0x3d07` | **`-0xa`** |
| `__DATA_CONST.__auth_got` | `0x7b0` | `0x7b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x10d8` | `0x10e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0

-  Functions: 1202
-  Symbols:   493
-  CStrings:  6312
+  Functions: 1203
+  Symbols:   494
+  CStrings:  6317
Symbols:
+ _objc_retain_x28
CStrings:
+ "%@, hashedApToModelMappingDataURL, %@, size, %.1f (kB), footprint, %.4f MB"
+ "%@, step 1: compile CoreML model, coremlModelURL, %@, tempCompiledModelURL, %@, error, %@, footprint, %.4f MB"
+ "%@, step 2: save compiled model, before, %@, after, %@, error, %@, footprint, %.4f MB"
+ "%@, step 3: delete CoreML model, %@, error, %@, footprint, %.4f MB"
+ "%@, step 4: saved tile metadata, %@, footprint, %.4f MB"
+ "%@, tile path, %@, error, %@, tile, %{sensitive}@, footprint, %.4f MB"
+ "%@.%@.%@.invocation"
+ "%@.%@.%@.reply"
+ "v24@?0@\"RTLocalBluePOIResult\"8@\"NSError\"16"
+ "v56@0:8@\"NSString\"16@\"NSString\"24Q32Q40@?<v@?@\"NSError\">48"
+ "v56@0:8@16@24Q32Q40@?48"
- "%@, hashedApToModelMappingDataURL, %@, size, %.1f (kB)"
- "%@, step 1: compile CoreML model, coremlModelURL, %@, tempCompiledModelURL, %@, error, %@"
- "%@, step 2: save compiled model, before, %@, after, %@, error, %@"
- "%@, step 3: delete CoreML model, %@, error, %@"
- "v56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32q40@?<v@?@\"NSError\">48"
- "v56@0:8@16@24@32q40@?48"
```
