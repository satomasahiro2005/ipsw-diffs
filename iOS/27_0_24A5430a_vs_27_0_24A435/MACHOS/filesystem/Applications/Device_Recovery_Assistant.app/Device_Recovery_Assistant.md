## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e77c` | `0x1facc` | **`+0x1350`** |
| `__TEXT.__oslogstring` | `0x35e9` | `0x3956` | **`+0x36d`** |
| `__TEXT.__objc_stubs` | `0x6220` | `0x6500` | **`+0x2e0`** |
| `__TEXT.__objc_methname` | `0x8b1c` | `0x8dc2` | **`+0x2a6`** |
| `__DATA.__objc_const` | `0x6558` | `0x6718` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x2d90` | `0x2eb8` | **`+0x128`** |
| `__TEXT.__cstring` | `0x35b5` | `0x36a7` | **`+0xf2`** |
| `__DATA.__objc_selrefs` | `0x22c0` | `0x2390` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0xa08` | `0xa80` | **`+0x78`** |
| `__DATA.__objc_data` | `0xaf0` | `0xb40` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x748` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x118` | `0x150` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x1960` | `0x1980` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x257a` | `0x2597` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0x20c` | `0x224` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4c0` | `0x4d8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x840` | `0x850` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x689` | `0x699` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x430` | `0x438` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x108` | `0x110` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`

### Other Changes

```diff

+  - /System/Library/Frameworks/CoreMotion.framework/CoreMotion

-  Functions: 793
-  Symbols:   307
-  CStrings:  2355
+  Functions: 822
+  Symbols:   310
+  CStrings:  2410
Symbols:
+ _NSStringFromCGRect
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_NSOperationQueue
CStrings:
+ "%{public}s: [DREHingeManager] CMAngleManager unavailable (no hinge on this hardware); not observing."
+ "%{public}s: [DREHingeManager] Display: name=%{public}@ device=%{public}@ main=%d bounds=%{public}@"
+ "%{public}s: [DREHingeManager] Hinge state %ld -> %ld (angle=%.1f°)"
+ "%{public}s: [DREHingeManager] No display configuration for hinge state %ld; not switching."
+ "%{public}s: [DREHingeManager] Only %lu always-connected display(s); nothing to switch between."
+ "%{public}s: [DREHingeManager] Started observing hinge angle."
+ "%{public}s: [DisplayManager] No configuration for always-connected display %{public}@; skipping."
+ "%{public}s: [SceneManager] Moving %lu scene(s) from %{public}@ to %{public}@ (%{public}@)"
+ "%{public}s: [SceneManager] Scenes already on display %{public}@; no move needed"
+ "%{public}s: [SceneManager] moveToDisplayConfiguration: called with nil configuration; ignoring"
+ "+[DREHingeManager shouldMonitorHingeAngle]"
+ "-[DREHingeManager _handleAngle:]"
+ "-[DREHingeManager start]"
+ "-[DisplayManager internalDisplayConfigurations]"
+ "-[SceneManager moveToDisplayConfiguration:]"
+ "@\"CMAngleManager\""
+ "@\"DREHingeManager\""
+ "@\"NSOperationQueue\""
+ "@24@0:8q16"
+ "DREHingeManager"
+ "T@\"CMAngleManager\",&,N,V_angleManager"
+ "T@\"DREHingeManager\",&,V_hingeManager"
+ "T@\"NSMutableDictionary\",&,V_presentationBindersByIdentity"
+ "T@\"NSOperationQueue\",&,N,V_angleQueue"
+ "Tq,N,V_currentState"
+ "_angleManager"
+ "_angleQueue"
+ "_currentState"
+ "_displayConfigurationForHingeState:"
+ "_handleAngle:"
+ "_hingeManager"
+ "_presentationBinderForConfiguration:"
+ "_presentationBindersByIdentity"
+ "allValues"
+ "alwaysConnectedIdentities"
+ "angleDegrees"
+ "angleManager"
+ "angleQueue"
+ "com.apple.devicerecovery.hinge"
+ "configurationForIdentity:"
+ "currentState"
+ "deviceName"
+ "hingeManager"
+ "identity"
+ "internalDisplayConfigurations"
+ "isAvailable"
+ "isMainDisplay"
+ "moveToDisplayConfiguration:"
+ "presentationBindersByIdentity"
+ "setAngleManager:"
+ "setAngleQueue:"
+ "setCurrentState:"
+ "setHingeManager:"
+ "setMaxConcurrentOperationCount:"
+ "setPresentationBindersByIdentity:"
+ "shouldMonitorHingeAngle"
+ "startAngleUpdatesToQueue:handler:"
+ "stopAngleUpdates"
+ "updateActiveDisplayConfiguration:"
+ "v16@?0@\"CMAngle\"8"
- "@\"UIRootWindowScenePresentationBinder\""
- "T@\"UIRootWindowScenePresentationBinder\",&,V_rootWindowScenePresentationBinder"
- "_rootWindowScenePresentationBinder"
- "rootWindowScenePresentationBinder"
- "setRootWindowScenePresentationBinder:"
```
