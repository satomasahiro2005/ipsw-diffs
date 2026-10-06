## AFKUser

> `/System/Library/PrivateFrameworks/AFKUser.framework/AFKUser`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67e4` | `0x6af8` | **`+0x314`** |
| `__TEXT.__oslogstring` | `0x8cc` | `0x998` | **`+0xcc`** |
| `__DATA_CONST.__const` | `0x1d8` | `0x188` | **`-0x50`** |
| `__TEXT.__cstring` | `0x25d` | `0x27c` | **`+0x1f`** |
| `__TEXT.__gcc_except_tab` | `0x92c` | `0x910` | **`-0x1c`** |
| `__DATA.__data` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x268` | `0x258` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `—` | `0x10` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x348` | `0x340` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-743.40.3.0.0
+743.40.4.0.0

-  CStrings:  86
+  CStrings:  89
Symbols:
+ _AFKUserRegistryFromSerializedServices
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSMutableDictionary
+ ___block_descriptor_40_e8_32s_e46_v32?0"AFKEndpointInterface"8"NSString"1624ls32l8
+ _objc_retain_x24
- _CFRelease
- _IOCFUnserializeWithSize
- ___block_descriptor_48_e8_32r40r_e15_v32?08Q16^B24lr32l8r40l8
- ___block_descriptor_48_e8_32s40r_e15_v32?08Q16^B24lr40l8s32l8
- ___block_descriptor_48_e8_32s40s_e15_v32?08Q16^B24ls32l8s40l8
CStrings:
+ "0x%llx: IOCFUnserializeBinary failed"
+ "0x%llx: Timeout waiting for endpoint cancellation"
+ "0x%llx: registry capture held no AFKRootService"
+ "0x%llx: registry service children is a %{public}@, expected an array"
+ "0x%llx: registry service unserialized as %{public}@, expected a dictionary"
+ "v32@?0@\"AFKEndpointInterface\"8@\"NSString\"16@24"
- "0x%llx: IOCFUnserializeBinary failed:%@"
- "0x%llx: IOCFUnserializeWithSize:%@"
- "v32@?0@8Q16^B24"
```
