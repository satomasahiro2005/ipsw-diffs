## SecureSessionManagement

> `/System/Library/PrivateFrameworks/SecureSessionManagement.framework/SecureSessionManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3641c` | `0x36820` | **`+0x404`** |
| `__TEXT.__oslogstring` | `0x816` | `0x876` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x25e0` | `0x2590` | **`-0x50`** |
| `__TEXT.__const` | `0x12a8` | `0x12b8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xb28` | `0xb20` | **`-0x8`** |

### Other Changes

```diff

-206.1.0.0.0
+215.0.0.0.0

-  Symbols:   323
-  CStrings:  49
+  Symbols:   322
+  CStrings:  50
Symbols:
- _objc_release_x28
Functions:
~ sub_29b20b4a4 -> ___swift_allocate_value_buffer : 128 -> 100
~ ___swift_allocate_value_buffer -> ___swift_project_value_buffer : 100 -> 56
~ ___swift_project_value_buffer -> sub_29c69d540 : 56 -> 128
~ sub_29b20b710 -> sub_29c69d710 : 76 -> 72
~ sub_29b20c468 -> sub_29c69e464 : 2024 -> 2240
~ sub_29b20f948 -> sub_29c6a1a1c : 96 -> 124
~ sub_29b211b88 -> sub_29c6a3c78 : 280 -> 276
~ sub_29b213db8 -> sub_29c6a5ea4 : 300 -> 304
~ sub_29b2140bc -> sub_29c6a61ac : 300 -> 304
~ sub_29b216110 -> sub_29c6a8204 : 1068 -> 1072
~ sub_29b216650 -> sub_29c6a8748 : 1036 -> 1040
~ sub_29b217848 -> sub_29c6a9944 : 1016 -> 1004
~ sub_29b2180b8 -> sub_29c6aa1a8 : 7032 -> 6968
~ sub_29b219d60 -> sub_29c6abe10 : 6716 -> 6676
~ sub_29b21b89c -> sub_29c6ad924 : 7092 -> 7076
~ sub_29b21e2f4 -> sub_29c6b036c : 6732 -> 6668
~ sub_29b21fd40 -> sub_29c6b1d78 : 5136 -> 5172
~ sub_29b224070 -> sub_29c6b60cc : 1372 -> 1368
~ sub_29b2246fc -> sub_29c6b6754 : 924 -> 920
~ sub_29b224a98 -> sub_29c6b6aec : 932 -> 928
~ sub_29b224f4c -> sub_29c6b6f9c : 1624 -> 1628
~ sub_29b225bc8 -> sub_29c6b7c1c : 1052 -> 1048
~ sub_29b226114 -> sub_29c6b8164 : 596 -> 592
~ sub_29b226368 -> sub_29c6b83b4 : 604 -> 600
~ sub_29b228928 -> sub_29c6ba970 : 1640 -> 1644
~ sub_29b2290c0 -> sub_29c6bb10c : 1368 -> 1372
~ sub_29b229738 -> sub_29c6bb788 : 160 -> 176
~ sub_29b229e00 -> sub_29c6bbe60 : 1380 -> 1384
~ sub_29b22a870 -> sub_29c6bc8d4 : 2724 -> 2712
~ sub_29b22b448 -> sub_29c6bd4a0 : 2512 -> 2500
~ sub_29b22bf18 -> sub_29c6bdf64 : 3416 -> 3420
~ sub_29b22eb50 -> sub_29c6c0ba0 : 2512 -> 2500
~ sub_29b2316fc -> sub_29c6c3740 : 160 -> 176
~ sub_29b234764 -> sub_29c6c67b8 : 476 -> 480
~ sub_29b235b5c -> sub_29c6c7bb4 : 592 -> 588
~ sub_29b236130 -> sub_29c6c8184 : 472 -> 476
~ sub_29b23697c -> sub_29c6c89d4 : 1956 -> 2000
~ sub_29b237120 -> sub_29c6c91a4 : 628 -> 624
~ sub_29b237394 -> sub_29c6c9414 : 680 -> 700
~ sub_29b23763c -> sub_29c6c96d0 : 1280 -> 1284
~ sub_29b237f38 -> sub_29c6c9fd0 : 448 -> 444
~ sub_29b2380f8 -> sub_29c6ca18c : 252 -> 264
~ sub_29b23b538 -> sub_29c6cd5d8 : 348 -> 344
~ sub_29b23f518 -> sub_29c6d15b4 : 900 -> 884
~ sub_29b23fb2c -> sub_29c6d1bb8 : 708 -> 1576
~ sub_29b2402bc -> sub_29c6d26ac : 796 -> 808
~ sub_29b240e80 -> sub_29c6d327c : 256 -> 260
~ sub_29b241174 -> sub_29c6d3574 : 304 -> 308
CStrings:
+ "LeadSessionKeyQuery.sessionExists failed for serviceName=%{public}s, tag=%llu: %s"
```
