## SpotlightUIInternal

> `/System/Library/PrivateFrameworks/SpotlightUIInternal.framework/SpotlightUIInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5201c` | `0x521fc` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x1376` | `0x1476` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x9360` | `0x9390` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4348` | `0x4368` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5d60` | `0x5d78` | **`+0x18`** |
| `__TEXT.__const` | `0x1488` | `0x1498` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x418` | `0x41c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-250.1.4.1.0
+250.1.9.0.0

-  Functions: 2106
-  Symbols:   3285
-  CStrings:  373
+  Functions: 2108
+  Symbols:   3288
+  CStrings:  375
Symbols:
+ -[SPUISearchViewController searchViewIsPresented]
+ -[SPUISearchViewController searchui_cardLoader]
+ -[SPUISearchViewController setSearchViewIsPresented:]
+ _OBJC_IVAR_$_SPUISearchViewController._searchViewIsPresented
- -[SPUISearchViewController cardLoader]
CStrings:
+ "!!\xf0!"
+ "askSiriDecision: qid=%lu displayState=%ld tier=%ld elevatedActive=%d hasElevatedResult=%d hasTopHitResult=%d isElevatedSiri=%d elevIsInstantAnswer=%d elevHasAppBundle=%d showAskSiri=%d suppressedForAuth=%d askSiriResult=%d queryLen=%ld complete=%d"
```
