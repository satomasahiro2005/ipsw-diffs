## CoreHID

> `/System/Library/PrivateFrameworks/CoreHID.framework/CoreHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d9e8` | `0x3d6e8` | **`-0x300`** |
| `__TEXT.__const` | `0xa8d0` | `0xa8c0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa40` | `0xa38` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0xa30` | `0xa38` | **`+0x8`** |

### Other Changes

```diff

-2360.2.2.0.0
+2360.40.11.0.0

-  Symbols:   580
+  Symbols:   579
Symbols:
+ _swift_retain_x25
- _objc_release_x28
- _objc_retain_x28
Functions:
~ sub_25bbd979c -> sub_25f4bd79c : 1236 -> 416
~ sub_25bbd9c70 -> sub_25f4bd93c : 1176 -> 1236
~ sub_25bbda1fc -> sub_25f4bdf04 : 832 -> 608
~ sub_25bbdca6c -> sub_25f4c0694 : 44 -> 192
~ sub_25bbfe214 -> sub_25f4e1ed0 : 680 -> 692
~ sub_25bc093c0 -> sub_25f4ed088 : 8796 -> 8836
~ sub_25bc11728 -> sub_25f4f5418 : 588 -> 596
~ sub_25bc11bb0 -> sub_25f4f58a8 : 272 -> 280
```
