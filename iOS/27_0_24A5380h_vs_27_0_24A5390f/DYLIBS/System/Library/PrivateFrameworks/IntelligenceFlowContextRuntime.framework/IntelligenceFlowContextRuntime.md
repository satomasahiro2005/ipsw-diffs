## IntelligenceFlowContextRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/IntelligenceFlowContextRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1087bc` | `0x113774` | **`+0xafb8`** |
| `__TEXT.__oslogstring` | `0x3a00` | `0x407b` | **`+0x67b`** |
| `__TEXT.__eh_frame` | `0x8598` | `0x8b20` | **`+0x588`** |
| `__AUTH_CONST.__const` | `0x5230` | `0x5448` | **`+0x218`** |
| `__TEXT.__unwind_info` | `0x2fa8` | `0x3110` | **`+0x168`** |
| `__TEXT.__const` | `0x4930` | `0x4a60` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x172c` | `0x17ec` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x2658` | `0x2700` | **`+0xa8`** |
| `__TEXT.__swift5_typeref` | `0x2b10` | `0x2b74` | **`+0x64`** |
| `__DATA_CONST.__got` | `0x1030` | `0x1088` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0x65c` | `0x6ac` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1a6c` | `0x1aa8` | **`+0x3c`** |
| `__TEXT.__swift_as_ret` | `0x3c0` | `0x3fc` | **`+0x3c`** |
| `__TEXT.__swift5_fieldmd` | `0x1204` | `0x1230` | **`+0x2c`** |
| `__TEXT.__cstring` | `0x1cec` | `0x1d0c` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x394` | `0x3ac` | **`+0x18`** |
| `__DATA.__bss` | `0x13f0` | `0x1400` | **`+0x10`** |
| `__DATA.__data` | `0xc90` | `0xca0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3168` | `0x3158` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x1d60` | `0x1d68` | **`+0x8`** |
| `__DATA.__common` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xab8` | `0xac0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6cc` | `0x6d4` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1f8` | `0x1fc` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1e4` | `0x1e8` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3600.147.12.501.3
+3600.151.4.501.6

-  Functions: 4846
-  Symbols:   327
-  CStrings:  383
+  Functions: 5007
+  Symbols:   328
+  CStrings:  398
Symbols:
+ _CGRectContainsPoint
CStrings:
+ "[AppCompatibility] Editing context fetched for %{public}s but no matching window found to inject synthetic entity"
+ "[AppCompatibility] Synthesized OnScreenText for %{public}s"
+ "[ContextMenuEntityExtractor] Deduplicated %ld duplicate entities — returning %ld unique entities"
+ "[ContextMenuEntityExtractor] No pattern matched — no focused entities resolved (hasExportableData=%{bool}d, ancestors=%ld)"
+ "[ContextMenuEntityExtractor] Pattern 1 direct — no expansion (isSelected=%{bool}d)"
+ "[ContextMenuEntityExtractor] Pattern 1a sibling expansion — %ld total entities after expanding selected siblings"
+ "[ContextMenuEntityExtractor] Pattern 1b cell-in-selected-row expansion — %ld total entities after expanding selected rows"
+ "[ContextMenuEntityExtractor] Pattern 1c collection cross-section expansion — %ld total entities after expanding selected items"
+ "[ContextMenuEntityExtractor] Pattern 2 hit-test — no child matched point (%f, %f) (children=%ld)"
+ "[ContextMenuEntityExtractor] Pattern 2 hit-test — resolved clicked child (%ld entities, isSelected=%{bool}d)"
+ "[ContextMenuEntityExtractor] Pattern 2 selection expansion — %ld total entities after expanding selected siblings"
+ "[ContextMenuEntityExtractor] Pattern 3 exportable data — %ld entities"
+ "[ContextMenuEntityExtractor] Pattern 4 ancestor walk — %ld entities on %s"
+ "[ContextMenuEntityExtractor] Pattern 4 selection expansion (collectionItem) — %ld total entities after expanding selected items"
+ "[ContextMenuEntityExtractor] Pattern 4 selection expansion (tableRow) — %ld total entities after expanding selected rows"
+ "[ContextMenuEntityExtractor] Skipping context-menu-excluded entity type: %s"
+ "[ContextMenuEntityExtractor] Skipping unsupported entity type: %s"
+ "[ContextMenuExportDataExtractor] Context menu source element has no exportableData"
+ "[ContextMenuExportDataExtractor] Failed to write in-memory data to temp file: %@"
+ "[ContextMenuExportDataExtractor] export item has no usable representations"
+ "[ContextMenuExportDataExtractor] exportData failed: %@"
+ "[ContextMenuExportDataExtractor] exportData returned %ld items for context menu element"
+ "[EditingContextFetcher] cursor=%{public}ld preservedRanges=%{public}ld hasText=%{bool,public}d hasMarkdown=%{bool,public}d"
+ "[EditingContextFetcher] fetch failed for %{public}s: %{public}s"
+ "[EditingContextFetcher] fetch for %{public}s returned no value"
+ "[EditingContextFetcher] probe reported no editable field for %{public}s; skipping fetch"
+ "[ElementEntityExtractor] Failed to lookup container for bundle: %s"
+ "[ElementEntityExtractor] Failed to resolve transient entity: %@"
+ "[ElementEntityExtractor] Filtered 3P transient entity from %s"
+ "[ElementEntityExtractor] Filtered non-schematized 3P entity: %s from %s"
+ "[ElementEntityExtractor] Filtered non-schematized 3P foreign entity: %s from %s"
+ "[ElementEntityExtractor] ToolDatabase unavailable for transient entity resolution"
+ "[ElementEntityExtractor] ToolDatabase unavailable — blocking 3P entity %s from %s"
+ "[UserContextFetcher] Extracted %ld entities, %ld selected, %ld focused, %ld context menu focused, %ld on-screen texts for window %s"
+ "[UserContextFetcher] Found context menu source element; ancestorCount: %ld, nearestParent content: %s, presentationPoint: %s"
+ "[UserContextFetcher] Full element hierarchy:\n%{public}s"
+ "[UserContextFetcher] Resolving context menu entities: appIntentsPayloadCount=%ld, hasExportableData=%{bool}d, ancestors=%ld"
+ "com.apple.TVSystemUIService"
- "[EditingContextFetcher] cursor=%{public}ld preservedRanges=%{public}ld hasMarkdown=%{bool,public}d"
- "[UserContextFetcher] Context menu source element has no exportableData"
- "[UserContextFetcher] Context menu source element: appIntentsPayloadCount=%ld, hasExportableData=%{bool}d"
- "[UserContextFetcher] Context menu: direct entities excluded, falling back to exportable data (hasExportableData=%{bool}d)"
- "[UserContextFetcher] Context menu: extracted %ld direct entities from source element"
- "[UserContextFetcher] Context menu: extracted %ld entities from element directly"
- "[UserContextFetcher] Context menu: extracted %ld entities from sibling (content: %s)"
- "[UserContextFetcher] Context menu: no entities on element, searched parent subtree and found %ld elements with payloads"
- "[UserContextFetcher] Extracted %ld entities, %ld selected, %ld context menu focused, %ld on-screen texts for window %s"
- "[UserContextFetcher] Failed to lookup container for bundle: %s"
- "[UserContextFetcher] Failed to resolve transient entity: %@"
- "[UserContextFetcher] Failed to write in-memory data to temp file: %@"
- "[UserContextFetcher] Filtered 3P transient entity from %s"
- "[UserContextFetcher] Filtered non-schematized 3P entity: %s from %s"
- "[UserContextFetcher] Filtered non-schematized 3P foreign entity: %s from %s"
- "[UserContextFetcher] Found context menu source element; parent content: %s, presentationPoint: %s"
- "[UserContextFetcher] Skipping excluded entity type for context menu"
- "[UserContextFetcher] Skipping unsupported entity type for context menu: %s"
- "[UserContextFetcher] ToolDatabase unavailable for transient entity resolution"
- "[UserContextFetcher] ToolDatabase unavailable — blocking 3P entity %s from %s"
- "[UserContextFetcher] export item has no usable representations"
- "[UserContextFetcher] exportData failed: %@"
- "[UserContextFetcher] exportData returned %ld items for context menu element"
```
