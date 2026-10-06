## CentauriDiagnostic

> `/System/Library/PrivateFrameworks/CentauriDiagnostic.framework/CentauriDiagnostic`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6504` | `0x6488` | **`-0x7c`** |

### Other Changes

```diff

-123.0.0.0.1
+124.0.0.0.1
Functions:
~ _collectSubsystemLogsForClient : 3144 -> 3152
~ _collectFoldersForSubsystem : 4484 -> 4384
~ _getTotalSizeForPath : 768 -> 764
~ _getCDFClientFolderName : 140 -> 136
~ +[CDFSubsystemDiagnostics createSubsystemDirectoryStructure:outputDir:subDirectoryList:] : 860 -> 848
~ +[CDFSubsystemDiagnostics collectFilesWithRegex:from:to:] : 1512 -> 1508
~ +[CDFSubsystemDiagnostics collectFileWithRegex:from:to:mostRecent:] : 2080 -> 2076
~ +[CDFSubsystemDiagnostics collectFilesWithRegexes:from:to:mostRecent:] : 820 -> 816
```
