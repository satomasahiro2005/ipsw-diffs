## backboardd

> `/usr/libexec/backboardd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58298` | `0x58a64` | **`+0x7cc`** |
| `__DATA.__objc_const` | `0xad88` | `0xaf20` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0x704c` | `0x7144` | **`+0xf8`** |
| `__DATA.__data` | `0x1ac8` | `0x1b88` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0xdb53` | `0xdbe8` | **`+0x95`** |
| `__TEXT.__objc_methlist` | `0x49a4` | `0x4a0c` | **`+0x68`** |
| `__TEXT.__objc_stubs` | `0x9e20` | `0x9e80` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x1368` | `0x13c1` | **`+0x59`** |
| `__TEXT.__cstring` | `0x4c7f` | `0x4cd3` | **`+0x54`** |
| `__DATA.__objc_data` | `0x1fe0` | `0x2030` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x32f0` | `0x3318` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x2eb6` | `0x2ed7` | **`+0x21`** |
| `__DATA.__objc_selrefs` | `0x30c8` | `0x30e8` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x5020` | `0x5000` | **`-0x20`** |
| `__DATA.__bss` | `0x328` | `0x340` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x15c8` | `0x15e0` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x230` | `0x240` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x88` | `0x98` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7f0` | `0x7fc` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x890` | `0x898` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x330` | `0x338` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x268` | `0x270` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-873.100.0.0.0
+877.0.0.0.0

-  Functions: 1897
-  Symbols:   617
-  CStrings:  4079
+  Functions: 1904
+  Symbols:   618
+  CStrings:  4091
Symbols:
+ _BKSDisplayServiceName
CStrings:
+ "%s %{public}@ Blanked: %{BOOL}u"
+ "%s Blanked: %{BOOL}u"
+ "%s Blanked: %{BOOL}u -- suppressed - shell handles it"
+ "%{public}s: unknown displayUUID/systemDisplayIdentifier:%{public}@ "
+ "BKDisplayService: ignoring screen-blank suppression from non-system-shell client %{public}@"
+ "BKDisplayServiceServer"
+ "BKSDisplayServiceClientInterface"
+ "BKSDisplayServiceServerInterface"
+ "Vv24@0:8@\"NSSet<__NSString__>\"16"
+ "_connectionIsSystemShell:"
+ "_publishLock"
+ "_publishScreenBlankNotificationSuppressedDisplays"
+ "com.apple.backboardd.BKDisplayServiceServer"
+ "hasBlankedScreen notification suppressed for displays: %{public}@"
+ "setScreenBlankNotificationSuppressedDisplayUUIDs:"
+ "unionSet:"
+ "v24@?0@\"BSServiceConnection\"8@\"NSMutableSet\"16"
- "%s %{public}@ Blanked: %@"
- "%s Blanked: %@"
- "%{public}s: unknown displayUUID:%{public}@ "
- "NO"
- "YES"
```
