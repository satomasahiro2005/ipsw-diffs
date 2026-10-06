## MediaIntelligence

> `/System/Library/Frameworks/MediaIntelligence.framework/MediaIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19a84` | `0x1a594` | **`+0xb10`** |
| `__AUTH_CONST.__const` | `0x10a0` | `0x1140` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xa88` | `0xa08` | **`-0x80`** |
| `__TEXT.__swift5_typeref` | `0x8a6` | `0x90e` | **`+0x68`** |
| `__TEXT.__cstring` | `0x383` | `0x3e3` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x820` | `0x858` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x94` | `0xc8` | **`+0x34`** |
| `__DATA.__data` | `0x480` | `0x4a8` | **`+0x28`** |
| `__TEXT.__const` | `0x1780` | `0x1788` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x5e0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x48` | `0x44` | **`-0x4`** |

### Other Changes

```diff

-435.79.1.5.0
+460.7.1.0.0

-  Functions: 559
-  Symbols:   482
-  CStrings:  49
+  Functions: 565
+  Symbols:   487
+  CStrings:  52
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _objc_retain_x1
+ _swift_retain_x28
+ _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
+ _symbolic So21VNImageRequestHandlerC
+ _symbolic So24VNCreateFaceprintRequestC
+ _symbolic So29VNDetectFaceRectanglesRequestC
- _swift_retain_x19
- _swift_retain_x22
CStrings:
+ "Adding faces for asset "
+ "Adding/updating "
+ "Detecting faces in asset "
+ "Identifying faces for "
+ "Updating faces for existing asset "
- " does not exist. Inserting faces ..."
- " exists. Updating faces ..."
```
