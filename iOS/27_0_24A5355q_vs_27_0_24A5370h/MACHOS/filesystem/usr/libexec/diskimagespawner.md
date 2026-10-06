## diskimagespawner

> `/usr/libexec/diskimagespawner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methtype` | `0x482` | `0x4a8` | **`+0x26`** |
| `__TEXT.__objc_methname` | `0xae0` | `0xaff` | **`+0x1f`** |
| `__TEXT.__text` | `0x2509c` | `0x250b0` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x42c` | `0x43c` | **`+0x10`** |
| `__DATA.__objc_const` | `0x840` | `0x848` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x368` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-588.0.0.0.2
+593.0.0.0.1

-  CStrings:  351
+  CStrings:  353
Functions:
~ sub_100004434 : 316 -> 312
~ sub_100004570 -> sub_10000456c : 264 -> 260
~ sub_100010794 -> sub_10001078c : 400 -> 392
~ sub_100010c3c -> sub_100010c2c : 648 -> 616
~ sub_100011938 -> sub_100011908 : 560 -> 576
~ sub_100011bb4 -> sub_100011b94 : 556 -> 564
~ sub_1000193e8 -> sub_1000193d0 : 472 -> 484
~ sub_10001ac98 -> sub_10001ac8c : 56 -> 60
~ sub_10001acd0 -> sub_10001acc8 : 56 -> 60
~ sub_100020bd4 -> sub_100020bd0 : 564 -> 568
~ sub_1000237a8 : 124 -> 128
~ sub_100023df4 -> sub_100023df8 : 180 -> 176
~ sub_100023ee8 : 576 -> 592
~ sub_100024128 -> sub_100024138 : 624 -> 628
CStrings:
+ "v24@0:8@?<v@?@\"NSError\">16"
+ "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSString\"@\"NSError\">24"
+ "waitForSLACompletionWithReply:"
- "v32@0:8@\"DIAttachParams\"16@?<v@?@\"DIDeviceHandle\"@\"NSError\">24"
```
