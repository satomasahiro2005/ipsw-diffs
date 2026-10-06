## iCloudWebData

> `/System/Library/PrivateFrameworks/iCloudWebData.framework/iCloudWebData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x217b8` | `0x21bb4` | **`+0x3fc`** |
| `__TEXT.__oslogstring` | `0x426` | `0x466` | **`+0x40`** |
| `__TEXT.__const` | `0x12b8` | `0x12a8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x40` | `0x48` | **`+0x8`** |

### Other Changes

```diff

-71.1.0.0.0
+71.3.0.0.0

-  CStrings:  41
+  CStrings:  42
Symbols:
+ _objc_retain_x20
- _objc_release_x23
Functions:
~ sub_2b7b4dc68 -> sub_2b9371c68 : 1804 -> 2824
~ sub_2b7b5914c -> sub_2b937d548 : 104 -> 248
~ ___swift_closure_destructor -> sub_2b937d640 : 204 -> 224
~ sub_2b7b59280 -> sub_2b937d720 : 252 -> 136
~ sub_2b7b5937c -> sub_2b937d7a8 : 248 -> 104
~ sub_2b7b59474 -> ___swift_closure_destructor : 224 -> 204
~ ___swift_closure_destructor.3 -> sub_2b937d8dc : 56 -> 252
~ sub_2b7b5958c -> ___swift_closure_destructor.3 : 184 -> 56
~ sub_2b7b59644 -> sub_2b937da10 : 136 -> 184
CStrings:
+ "ModelContainer init failed, purging store and retrying: %@"
```
