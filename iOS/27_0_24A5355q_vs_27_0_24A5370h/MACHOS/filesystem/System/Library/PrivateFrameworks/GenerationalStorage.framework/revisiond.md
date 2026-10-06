## revisiond

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/revisiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0xf30` | `0xf40` | **`+0x10`** |
| `__TEXT.__text` | `0x2841c` | `0x2840c` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x7a8` | `0x7b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-401.0.0.0.0
+402.0.0.0.0

-  Symbols:   337
+  Symbols:   338
Symbols:
+ _objc_release_x3
Functions:
~ sub_100002ed0 : 136 -> 132
~ sub_10000466c -> sub_100004668 : 560 -> 556
~ sub_1000049b0 -> sub_1000049a8 : 372 -> 380
~ sub_100005428 : 1660 -> 1684
~ sub_100005aa4 -> sub_100005abc : 136 -> 148
~ sub_100005c94 -> sub_100005cb8 : 876 -> 872
~ sub_10000804c -> sub_10000806c : 824 -> 816
~ sub_10000ab7c -> sub_10000ab94 : 560 -> 556
~ sub_10000b5f4 -> sub_10000b608 : 1540 -> 1544
~ sub_100010cc0 -> sub_100010cd8 : 84 -> 88
~ sub_100012e44 -> sub_100012e60 : 412 -> 408
~ sub_1000153f4 -> sub_10001540c : 308 -> 304
~ sub_100015528 -> sub_10001553c : 640 -> 636
~ sub_1000157a8 -> sub_1000157b8 : 612 -> 608
~ sub_10001829c -> sub_1000182a8 : 900 -> 896
~ sub_100018868 -> sub_100018870 : 692 -> 688
~ sub_100018f88 -> sub_100018f8c : 872 -> 884
~ sub_10001ba90 -> sub_10001baa0 : 384 -> 380
~ sub_10001c298 -> sub_10001c2a4 : 508 -> 504
~ sub_10001cb14 -> sub_10001cb1c : 252 -> 248
~ sub_10001dcc4 -> sub_10001dcc8 : 1036 -> 1052
~ sub_10001eeb0 -> sub_10001eec4 : 892 -> 888
~ sub_10001fc10 -> sub_10001fc20 : 380 -> 376
~ sub_1000208c0 -> sub_1000208cc : 752 -> 748
~ sub_100020d88 -> sub_100020d90 : 604 -> 600
~ sub_100021ef8 -> sub_100021efc : 932 -> 920
~ sub_100022474 -> sub_10002246c : 500 -> 496
~ sub_100024164 -> sub_100024158 : 676 -> 672
CStrings:
+ "17:36:55"
+ "Jun  9 2026"
- "08:03:08"
- "May 21 2026"
```
