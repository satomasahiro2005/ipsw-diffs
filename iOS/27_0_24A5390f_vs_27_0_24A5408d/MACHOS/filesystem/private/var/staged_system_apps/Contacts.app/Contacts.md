## Contacts

> `/private/var/staged_system_apps/Contacts.app/Contacts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf964` | `0xfd60` | **`+0x3fc`** |
| `__TEXT.__objc_methname` | `0x5ed3` | `0x5fb6` | **`+0xe3`** |
| `__TEXT.__objc_stubs` | `0x3e80` | `0x3f00` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x352` | `0x3c0` | **`+0x6e`** |
| `__DATA_CONST.__const` | `0x430` | `0x458` | **`+0x28`** |
| `__DATA.__objc_const` | `0x2f30` | `0x2f50` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1610` | `0x1630` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xdc` | `0xfc` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1e00` | `0x1e20` | **`+0x20`** |
| `__TEXT.__cstring` | `0x517` | `0x530` | **`+0x19`** |
| `__TEXT.__unwind_info` | `0x580` | `0x598` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1ad1` | `0x1ae8` | **`+0x17`** |
| `__TEXT.__auth_stubs` | `0x4c0` | `0x4d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x230` | `0x238` | **`+0x8`** |
| `__TEXT.__const` | `0x38` | `0x40` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1456.100.1.2.1
+1461.100.1.0.0

-  Functions: 516
-  Symbols:   163
-  CStrings:  1157
+  Functions: 522
+  Symbols:   165
+  CStrings:  1165
Symbols:
+ _UISceneDidActivateNotification
+ __Block_object_dispose
CStrings:
+ "B36@0:8B16B20B24B28B32"
+ "No active scene when -application:runTest:options: was called for \"%@\"; waiting for a scene to become active."
+ "T@\"UIWindowScene\",R,N"
+ "activeMainWindowScene"
+ "addObserverForName:object:queue:usingBlock:"
+ "hasActiveMainScene"
+ "removeObserver:"
+ "shouldSelectFirstContactWhenContactCardVisible:isCollapsed:hasDisplayedContact:hasRestorationActivity:hasDelayedActions:"
+ "v16@?0@\"NSNotification\"8"
- "setCornerRadius:"
```
