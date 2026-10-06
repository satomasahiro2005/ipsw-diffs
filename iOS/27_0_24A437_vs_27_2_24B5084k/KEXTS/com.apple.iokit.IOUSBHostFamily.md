## com.apple.iokit.IOUSBHostFamily

> `com.apple.iokit.IOUSBHostFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x95a18` | `0x95b08` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xa2b9` | `0xa2ff` | **`+0x46`** |
| `__DATA.__common` | `0x970` | `0x980` | **`+0x10`** |

### Other Changes

```diff

-1617.0.12.0.0
+1617.40.9.0.0

-  CStrings:  1151
+  CStrings:  1153
Functions:
~ sub_fffffff00a602f50 -> sub_fffffff00a6c63e0 : 1928 -> 1916
~ sub_fffffff00a6036fc -> sub_fffffff00a6c6b80 : 144 -> 188
~ sub_fffffff00a60378c -> sub_fffffff00a6c6c3c : 164 -> 196
~ sub_fffffff00a603ac0 -> sub_fffffff00a6c6f90 : 48 -> 56
~ sub_fffffff00a603af0 -> sub_fffffff00a6c6fc8 : 60 -> 64
~ sub_fffffff00a630f5c -> sub_fffffff00a6f4438 : 1580 -> 1560
~ sub_fffffff00a6349b8 -> sub_fffffff00a6f7e80 : 832 -> 864
~ sub_fffffff00a63921c -> sub_fffffff00a6fc704 : 1004 -> 1036
~ sub_fffffff00a6657e8 -> sub_fffffff00a728cf0 : 264 -> 324
~ sub_fffffff00a6659bc -> sub_fffffff00a728f00 : 264 -> 324
CStrings:
+ "1211111212221212112222222122222222222222222222222222222222222222222222222222212211111222211121122222222222111221121111111111111"
+ "kPortStatUSB3LinkFailureCount"
+ "kPortStatUSB3LinkFailureCountForDevice"
- "121111121222121211222222212222222222222222222222222222222222222222222222222221221111122221112112222222222111221121111111111111"
```
