## Symbols

> `/System/Library/Frameworks/Symbols.framework/Symbols`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1e0` | `0x370` | **`+0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x410` | `0x280` | **`-0x190`** |

### Other Changes

```text
Functions:
~ +[NSSymbolDisappearEffect disappearDownEffect] -> -[NSSymbolEffectOptions .cxx_destruct] : 80 -> 12
~ +[NSSymbolDisappearEffect effect] -> +[NSSymbolDisappearEffect disappearDownEffect] : 84 -> 80
~ +[NSSymbolEffect _effectWithType:] -> +[NSSymbolDisappearEffect effect] : 56 -> 84
~ -[NSSymbolDisappearEffect _withStyle:] -> +[NSSymbolEffect _effectWithType:] : 8 -> 56
~ +[NSSymbolEffectOptions options] -> -[NSSymbolDisappearEffect _withStyle:] : 112 -> 8
~ -[NSSymbolEffectOptions set_speed:] -> +[NSSymbolEffectOptions options] : 8 -> 112
~ -[NSSymbolEffectOptions set_repeatDelay:] -> -[NSSymbolEffectOptions set_repeatCount:] : 12 -> 8
~ -[NSSymbolEffect _effectType] -> -[NSSymbolEffectOptions set_repeatDelay:] : 8 -> 12
~ -[NSSymbolDisappearEffect copyWithZone:] -> -[NSSymbolEffect _effectType] : 84 -> 8
~ -[NSSymbolEffect copyWithZone:] -> -[NSSymbolDisappearEffect copyWithZone:] : 60 -> 84
~ -[NSSymbolEffectOptions copyWithZone:] -> -[NSSymbolEffect copyWithZone:] : 184 -> 60
~ -[NSSymbolEffectOptions _speed] -> -[NSSymbolEffectOptions copyWithZone:] : 8 -> 184
~ -[NSSymbolEffectOptions .cxx_destruct] -> -[NSSymbolDisappearEffect _style] : 12 -> 8
```
