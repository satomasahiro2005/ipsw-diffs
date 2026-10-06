## nanobackupd

> `/System/Library/PrivateFrameworks/NanoBackup.framework/nanobackupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bf68` | `0x1bf04` | **`-0x64`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff
Functions:
~ sub_100001f30 : 340 -> 336
~ sub_100002870 -> sub_10000286c : 272 -> 268
~ sub_100002a68 -> sub_100002a60 : 272 -> 268
~ sub_100004d60 -> sub_100004d54 : 356 -> 352
~ sub_100004ec4 -> sub_100004eb4 : 364 -> 360
~ sub_100005dac -> sub_100005d98 : 436 -> 432
~ sub_100005f60 -> sub_100005f48 : 304 -> 300
~ sub_100006b1c -> sub_100006b00 : 528 -> 524
~ sub_100006d40 -> sub_100006d20 : 528 -> 524
~ sub_1000084c0 -> sub_10000849c : 1224 -> 1220
~ sub_10000b4c4 -> sub_10000b49c : 1252 -> 1248
~ sub_10000e024 -> sub_10000dff8 : 612 -> 608
~ sub_10000e288 -> sub_10000e258 : 480 -> 476
~ sub_10001074c -> sub_100010718 : 1264 -> 1248
~ sub_100014d50 -> sub_100014d0c : 380 -> 376
~ sub_100015868 -> sub_100015820 : 528 -> 524
~ sub_100015a78 -> sub_100015a2c : 476 -> 472
~ sub_10001c5d4 -> sub_10001c584 : 284 -> 280
~ sub_10001c87c -> sub_10001c828 : 448 -> 444
~ sub_10001cc68 -> sub_10001cc10 : 316 -> 312
~ sub_10001ce64 -> sub_10001ce08 : 364 -> 360
~ sub_10001d0d0 -> sub_10001d070 : 308 -> 304
CStrings:
+ "Launching; \"NanoBackupDaemon-134\" \"1600\""
- "Launching; \"NanoBackupDaemon-134\" \"1105\""
```
