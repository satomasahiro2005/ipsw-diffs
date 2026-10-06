## GamePolicy

> `/System/Library/PrivateFrameworks/GamePolicy.framework/GamePolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1422c` | `0x14234` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 782
-  Symbols:   669
+  Functions: 781
+  Symbols:   668
Symbols:
- _OUTLINED_FUNCTION_3
Functions:
~ _OUTLINED_FUNCTION_1 : 16 -> 12
~ _OUTLINED_FUNCTION_2 : 20 -> 24
- _OUTLINED_FUNCTION_3
~ -[GPGameLibrary _onqueue_connectToXPCService].cold.1 : 100 -> 96
~ -[GPGameLibrary _handleXPCConnectionLost].cold.1 : 80 -> 84
~ -[GPGameLibrary _onqueue_ensureConnected].cold.1 : 80 -> 84
~ -[GPGameLibrary pong].cold.1 : 80 -> 84
~ -[GPGameLibrary installedGamesDidChange:].cold.1 : 100 -> 108
~ -[GPGameLibrary installedGamesDidChange:].cold.2 : 112 -> 108
~ ___56-[GPGameLibrary registerInstalledGamesDidChangeHandler:]_block_invoke.cold.1 : 100 -> 108
~ ___58-[GPGameLibrary fetchInstalledGamesWithCompletionHandler:]_block_invoke.cold.1 : 80 -> 84
~ ___58-[GPGameLibrary fetchInstalledGamesWithCompletionHandler:]_block_invoke.12.cold.1 : 100 -> 108
```
