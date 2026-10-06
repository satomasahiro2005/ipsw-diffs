## SignpostCollection

> `/System/Library/PrivateFrameworks/SignpostCollection.framework/SignpostCollection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fd0` | `0x6f84` | **`-0x4c`** |
| `__DATA_CONST.__const` | `0x398` | `0x3e0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x760` | `0x7a0` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa8d` | `0xac1` | **`+0x34`** |

### Other Changes

```diff

-202.0.0.0.0
+203.0.0.0.0

-  CStrings:  100
+  CStrings:  102
Functions:
~ ___153-[SignpostSupportObjectExtractor(Notifications) processNotificationsWithIntervalTimeoutInSeconds:shouldCalculateAnimationFramerate:targetQueue:errorOut:]_block_invoke_3 : 276 -> 200
CStrings:
+ "Initialization failure"
+ "Predicate evaluation failure"
```
