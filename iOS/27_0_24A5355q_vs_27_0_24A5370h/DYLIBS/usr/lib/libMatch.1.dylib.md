## libMatch.1.dylib

> `/usr/lib/libMatch.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6874` | `0x682c` | **`-0x48`** |

### Other Changes

```text
Functions:
~ _matchExec : 4152 -> 4184
~ _addNodeToList : 232 -> 240
~ _matchOptimize : 3528 -> 3420
~ _simplifyBranches : 364 -> 344
~ _nodeModRefs : 312 -> 316
~ _recurseThroughBranches : 404 -> 408
~ _isStraightLineUntilDotStar : 304 -> 328
~ _matchUnpack : 888 -> 892
~ _matchPack : 2252 -> 2268
~ _matchDiagram : 2908 -> 2892
~ _printGraphNode : 804 -> 808
~ _printRunNode : 664 -> 660
~ _tokenize : 1056 -> 1040
~ _verifyOperandCount : 192 -> 184
~ _nfaCopyNodes : 448 -> 452
```
