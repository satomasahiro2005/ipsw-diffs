## FSEvents

> `/System/Library/PrivateFrameworks/FSEvents.framework/FSEvents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91e8` | `0x923c` | **`+0x54`** |

### Other Changes

```text
Functions:
~ _process_dir_events : 1524 -> 1540
~ _implementation_callback_rpc : 3984 -> 4028
~ _FSEventStreamCopyPathsBeingWatched : 440 -> 424
~ _register_with_server : 1100 -> 1116
~ _FSEventStreamCopyDescription : 588 -> 584
~ __FSEventStreamCreate : 2284 -> 2312
~ _FSEventStreamSetExclusionPaths : 324 -> 320
~ _FSEventsPurgeEventsForDeviceUpToEventId : 392 -> 408
~ _FSEventStreamShow : 524 -> 516
~ _watch_all_parents : 776 -> 772
```
