## GameControllerIO

> `/System/Library/PrivateFrameworks/GameControllerIO.framework/GameControllerIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x533c` | `0x5464` | **`+0x128`** |
| `__TEXT.__oslogstring` | `0x495` | `0x4da` | **`+0x45`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__cstring` | `0x456` | `0x46d` | **`+0x17`** |
| `__TEXT.__const` | `0x85` | `0x8d` | **`+0x8`** |

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Symbols:   526
-  CStrings:  94
+  Symbols:   525
+  CStrings:  96
Symbols:
- _objc_alloc_init
Functions:
~ +[GCGamepadHIDServicePlugin matchService:options:score:] : 72 -> 288
~ -[GCGamepadHIDServicePlugin initWithService:] : 1344 -> 1372
~ -[GCGamepadHIDServicePlugin propertyForKey:client:] : 768 -> 820
CStrings:
+ "%{public}@ probe <%{public}@ %#010llx> (%zi)"
+ "GameControllerCategory"
+ "GameControllerSupport"
+ "Initialize %{public}@ for <%{public}@ %#010llx> {\nvendorID = %zu,\nproductID = %zu,\nversion = %zu,\nmanufacturer = '%{public}@',\nproduct = '%{public}@',\nserial = '%{private}@',\ntransport = '%{public}@',\ncategory = '%{public}@',\n}"
- "GameControllerPointer"
- "Initialize %{public}@' for <%{public}@ %#010llx> {\nvendorID = %zu,\nproductID = %zu,\nversion = %zu,\nmanufacturer = '%{public}@',\nproduct = '%{public}@',\nserial = '%{private}@',\ntransport = '%{public}@',\n}"
```
