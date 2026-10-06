## AskToViewExtension

> `/System/Library/ExtensionKit/Extensions/AskToViewExtension.appex/AskToViewExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x106fc` | `0x11b98` | **`+0x149c`** |
| `__TEXT.__eh_frame` | `0x64c` | `0x864` | **`+0x218`** |
| `__DATA.__objc_const` | `0x2c8` | `0x3a0` | **`+0xd8`** |
| `__TEXT.__objc_methtype` | `0xf8` | `0x1a9` | **`+0xb1`** |
| `__DATA.__objc_data` | `0x118` | `0x1c8` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x498` | `0x538` | **`+0xa0`** |
| `__TEXT.__const` | `0x628` | `0x6c2` | **`+0x9a`** |
| `__TEXT.__objc_methname` | `0x381` | `0x401` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x368` | `0x3e0` | **`+0x78`** |
| `__TEXT.__objc_classname` | `0xa2` | `0x112` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x14c` | `0x1a0` | **`+0x54`** |
| `__TEXT.__swift5_capture` | `0x198` | `0x1e8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1020` | `0x1060` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x46f` | `0x4af` | **`+0x40`** |
| `__DATA.__data` | `0x500` | `0x530` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x240` | `0x26c` | **`+0x2c`** |
| `__DATA_CONST.__auth_got` | `0x818` | `0x838` | **`+0x20`** |
| `__TEXT.__cstring` | `0x368` | `0x388` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x140` | `0x15c` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x280` | `0x298` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x40` | `0x54` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x38` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x20` | `0x34` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1cf` | `0x1df` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x74e` | `0x753` | **`+0x5`** |
| `__TEXT.__swift5_types` | `0x14` | `0x18` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-90.1.0.0.0
+92.0.0.0.0

-  Functions: 217
-  Symbols:   169
-  CStrings:  120
+  Functions: 245
+  Symbols:   170
+  CStrings:  130
Symbols:
+ _swift_getExistentialTypeMetadata
CStrings:
+ "%s Error calling acknowledgmentAlertButtonTapped: %@"
+ "_TtC18AskToViewExtension24NoOpDaemonClientReceiver"
+ "_TtP9AskToCore22ATDaemonClientProtocol_"
+ "acknowledgmentAlertButtonTappedWithQuestion:action:reply:"
+ "messagesComposeDidFinishWithQuestion:didSend:reply:"
+ "notifyDaemonOfAlertAction(_:)"
+ "v36@0:8@\"_TtC5AskTo10ATQuestion\"16B24@?<v@?@\"NSError\">28"
+ "v36@0:8@16B24@?28"
+ "v40@0:8@\"_TtC5AskTo10ATQuestion\"16q24@?<v@?@\"NSError\">32"
+ "v40@0:8@16q24@?32"
```
