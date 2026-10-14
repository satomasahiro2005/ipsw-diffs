## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff84` | `0x205dc` | **`+0x658`** |
| `__TEXT.__oslogstring` | `0x1a70` | `0x1ca5` | **`+0x235`** |
| `__AUTH_CONST.__objc_const` | `0x2880` | `0x28e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1c64` | `0x1cac` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x18d8` | `0x1908` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x8c8` | `0x8e0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4bc` | `0x4d0` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x19c` | `0x1a4` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 749
-  Symbols:   1489
-  CStrings:  228
+  Functions: 756
+  Symbols:   1499
+  CStrings:  233
Symbols:
+ -[AXUIDisplayManager _beginPendingSceneRequestForSceneClientIdentifier:]
+ -[AXUIDisplayManager _clearPendingSceneRequestForSceneClientIdentifier:]
+ -[AXUIDisplayManager pendingSceneRequestIdentifiers]
+ -[AXUIDisplayManager pendingSceneRequestTimers]
+ -[AXUIDisplayManager setPendingSceneRequestIdentifiers:]
+ -[AXUIDisplayManager setPendingSceneRequestTimers:]
+ GCC_except_table332
+ GCC_except_table333
+ GCC_except_table342
+ GCC_except_table343
+ GCC_except_table361
+ GCC_except_table362
+ GCC_except_table369
+ GCC_except_table377
+ GCC_except_table382
+ GCC_except_table398
+ GCC_except_table412
+ GCC_except_table433
+ GCC_except_table435
+ GCC_except_table452
+ _OBJC_IVAR_$_AXUIDisplayManager._pendingSceneRequestIdentifiers
+ _OBJC_IVAR_$_AXUIDisplayManager._pendingSceneRequestTimers
+ ___72-[AXUIDisplayManager _beginPendingSceneRequestForSceneClientIdentifier:]_block_invoke
- GCC_except_table328
- GCC_except_table329
- GCC_except_table338
- GCC_except_table339
- GCC_except_table357
- GCC_except_table358
- GCC_except_table365
- GCC_except_table373
- GCC_except_table378
- GCC_except_table394
- GCC_except_table426
- GCC_except_table428
- GCC_except_table445
CStrings:
+ "AXOverlayMonitor[Window]: attached %{public}@ scene=%{public}@ level=%f siblings=%lu"
+ "Active window scene for '%{public}@' changed from %{public}@ to %{public}@; migrating tracked content VCs"
+ "Adding contentVC=%p %@ service=%@ sceneClientIdentifier:%{public}@ windowScene=%{public}@, savedWindowScene=%{public}@"
+ "DisplayManager: Adding scene pending sceneClientIdentifier: %@"
+ "DisplayManager: No existing scene for identifier %@, requesting scene creation for service %@ at level %f"
+ "DisplayManager: Notifying newly registered service %@ about existing scene %@"
+ "DisplayManager: Removing scene pending sceneClientIdentifier: %@"
+ "DisplayManager: Scene creation already requested for identifier %@, skip requesting for service %@"
+ "DisplayManager: Scene creation request for identifier %@ never produced a scene, clearing request"
+ "Scene connected for Service: %@. windowScene: %{public}@ sceneClientIdentifier: %{public}@"
+ "Scene disconnected for Service: %@. windowScene: %{public}@ sceneClientIdentifier: %{public}@"
- "Active window scene for '%{public}@' changed from %p to %p; migrating tracked content VCs"
- "Adding contentVC=%p %@ service=%@ sceneClientIdentifier:%@ windowScene=%p, savedWindowScene=%p"
- "No existing scenes for identifier %@, requesting scene creation for service %@ at level %f"
- "Notifying newly registered service %@ about existing scene %@"
- "Scene connected for Service: %@. windowScene: %@"
- "Scene disconnected for Service: %@. windowScene: %@"
```
