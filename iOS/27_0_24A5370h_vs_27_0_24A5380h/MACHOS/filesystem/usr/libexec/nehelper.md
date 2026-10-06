## nehelper

> `/usr/libexec/nehelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24a70` | `0x255e8` | **`+0xb78`** |
| `__TEXT.__objc_stubs` | `0x2980` | `0x2a60` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x4a13` | `0x4a97` | **`+0x84`** |
| `__DATA_CONST.__const` | `0xcb0` | `0xd10` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1f5a` | `0x1f9c` | **`+0x42`** |
| `__DATA.__objc_selrefs` | `0xb00` | `0xb38` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x398` | `0x3b8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x10a0` | `0x10b0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x5f34` | `0x5f44` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x860` | `0x868` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3f0` | `0x3e8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2315.0.0.0.2
+2322.0.0.0.1

-  Functions: 245
-  Symbols:   380
-  CStrings:  1690
+  Functions: 247
+  Symbols:   382
+  CStrings:  1700
Symbols:
+ _OBJC_CLASS_$_NSMutableData
+ ___NSDictionary0__struct
+ _qsort_b
- _OBJC_CLASS_$_NSPropertyListSerialization
CStrings:
+ "Failed to build the binary UUID cache"
+ "Failed to write the binary UUID cache to disk"
+ "allObjects"
+ "appendBytes:length:"
+ "appendData:"
+ "buildBinaryCacheFromDictionary: missing os-version or boot-uuid"
+ "buildBinaryCacheFromDictionary: total size %u exceeds MAX_CACHE_SIZE"
+ "data"
+ "dataWithCapacity:"
+ "i24@?0r^v8r^v16"
+ "mutableBytes"
+ "set"
+ "sortedArrayUsingSelector:"
- "Failed to serialize the cache plist: %@"
- "Failed to write the serialized cache to disk"
- "dataWithPropertyList:format:options:error:"
```
