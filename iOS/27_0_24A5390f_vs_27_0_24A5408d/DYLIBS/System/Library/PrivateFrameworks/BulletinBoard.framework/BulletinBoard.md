## BulletinBoard

> `/System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x190` | `0x188` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x65ef` | `0x65f7` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x20b8` | `0x20b0` | **`-0x8`** |
| `__TEXT.__text` | `0x786f4` | `0x786f0` | **`-0x4`** |

### Other Changes

```diff

-953.100.0.0.0
+955.0.0.0.0
Symbols:
+ __OBJC_$_CLASS_METHODS_BBSectionInfoSettings(Deprecated|Managed)
+ __OBJC_$_INSTANCE_METHODS_BBSectionInfoSettings(Deprecated|Managed)
- __OBJC_$_CLASS_METHODS_BBSectionInfoSettings(Managed|Deprecated)
- __OBJC_$_INSTANCE_METHODS_BBSectionInfoSettings(Managed|Deprecated)
CStrings:
+ "Effective content preview setting: %{public}@, raw: %{public}@, globalSetting: %{public}@, isLocked: %{public}@"
- "Effective content preview setting: %{public}@, raw: %{public}@, globalSetting: %{public}@, isLocked: %@"
```
