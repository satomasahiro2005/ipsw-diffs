## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ee7a8` | `0x3eebf0` | **`+0x448`** |
| `__TEXT.__oslogstring` | `0x33140` | `0x332aa` | **`+0x16a`** |
| `__DATA_CONST.__const` | `0x9a90` | `0x9ab8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x2b3ef` | `0x2b413` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x13198` | `0x131b0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x3185c` | `0x3186c` | **`+0x10`** |

### Other Changes

```diff

-2720.17.0.0.0
+2720.17.6.0.0

-  Functions: 21002
+  Functions: 21004

-  CStrings:  8531
+  CStrings:  8534
CStrings:
+ "%tu out of the %tu removed participants on share %@ for operation %{public}@ are pending participants being re-added with the same user identity."
+ "All %tu of the removed participants on share %@ for operation %{public}@ are pending participants that are also being re-added with the same user identity. There is no need for a key roll due to participant removal."
+ "B32@?0@\"CKShareParticipant\"8Q16^B24"
```
