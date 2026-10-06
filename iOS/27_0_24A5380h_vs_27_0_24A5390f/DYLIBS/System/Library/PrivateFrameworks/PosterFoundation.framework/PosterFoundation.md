## PosterFoundation

> `/System/Library/PrivateFrameworks/PosterFoundation.framework/PosterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e1e0` | `0x5e500` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x47d1` | `0x4911` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x9390` | `0x93e0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x4969` | `0x49b9` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x4480` | `0x44c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3aa0` | `0x3ab8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2270` | `0x2280` | **`+0x10`** |
| `__TEXT.__const` | `0x558` | `0x568` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd68` | `0xd70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x310` | `0x318` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x18d8` | `0x18e0` | **`+0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 2175
-  Symbols:   3113
-  CStrings:  1014
+  Functions: 2178
+  Symbols:   3119
+  CStrings:  1018
Symbols:
+ -[PFPosterExtensionInstanceProvider initWithDefaultInstanceIdentifier:maxNumberOfInstancesPerExtension:]
+ -[PFPosterExtensionInstanceProvider maxNumberOfInstancesPerExtension]
+ GCC_except_table68
+ _OBJC_IVAR_$_PFPosterExtensionInstanceProvider._lock_releasedInstances
+ _OBJC_IVAR_$_PFPosterExtensionInstanceProvider._maxNumberOfInstancesPerExtension
+ _PFDispatchTimeAfterSeconds
+ ___104-[PFPosterExtensionInstanceProvider initWithDefaultInstanceIdentifier:maxNumberOfInstancesPerExtension:]_block_invoke
+ _dispatch_time
- GCC_except_table67
- ___71-[PFPosterExtensionInstanceProvider initWithDefaultInstanceIdentifier:]_block_invoke
CStrings:
+ "(%p) BACKSTOP HIT: extension '%{public}@' already has %lu live instances (max %lu); refusing to create another for reason '%{public}@' — an upstream gate over-admitted (accounting bug). rdar://181536204"
+ "(%p) relinquish of UNKNOWN instance '%{public}@'/%{public}@ for reason '%{public}@' — never vended by this provider"
+ "(%p) relinquish of already-released instance '%{public}@'/%{public}@ for reason '%{public}@' — no-op"
+ "exceeds max number of instances for extension"
+ "maxNumberOfInstancesPerExtension"
- "(%p) attempted to relinquish unknown or mismatched instance '%{public}@'/%{public}@ for reason '%{public}@'"
```
