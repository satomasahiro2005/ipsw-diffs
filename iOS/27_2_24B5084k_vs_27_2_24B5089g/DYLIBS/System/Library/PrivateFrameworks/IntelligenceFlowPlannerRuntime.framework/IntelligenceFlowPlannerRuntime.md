## IntelligenceFlowPlannerRuntime

> `/System/Library/PrivateFrameworks/IntelligenceFlowPlannerRuntime.framework/IntelligenceFlowPlannerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7751f4` | `0x781054` | **`+0xbe60`** |
| `__DATA_DIRTY.__data` | `0xeca0` | `0x10268` | **`+0x15c8`** |
| `__DATA.__bss` | `0x26560` | `0x25050` | **`-0x1510`** |
| `__DATA_DIRTY.__bss` | `0x7490` | `0x8990` | **`+0x1500`** |
| `__AUTH.__data` | `0x5320` | `0x4640` | **`-0xce0`** |
| `__DATA.__data` | `0x5a98` | `0x5290` | **`-0x808`** |
| `__TEXT.__eh_frame` | `0x3eb10` | `0x3f2f8` | **`+0x7e8`** |
| `__AUTH_CONST.__const` | `0x26740` | `0x26e48` | **`+0x708`** |
| `__TEXT.__swift5_capture` | `0x6af4` | `0x6dcc` | **`+0x2d8`** |
| `__TEXT.__cstring` | `0x175fa` | `0x178ba` | **`+0x2c0`** |
| `__TEXT.__unwind_info` | `0x16188` | `0x163d8` | **`+0x250`** |
| `__AUTH.__objc_data` | `0x598` | `0x3b8` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0xab0` | `0xc90` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x2359c` | `0x2374c` | **`+0x1b0`** |
| `__AUTH_CONST.__auth_got` | `0xb588` | `0xb640` | **`+0xb8`** |
| `__DATA_DIRTY.__common` | `0x400` | `0x4b8` | **`+0xb8`** |
| `__DATA.__common` | `0x1e0` | `0x129` | **`-0xb7`** |
| `__TEXT.__swift5_typeref` | `0xd9a2` | `0xd9f8` | **`+0x56`** |
| `__TEXT.__swift_as_cont` | `0x2e28` | `0x2e78` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x95d8` | `0x9618` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xadf3` | `0xae33` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x5320` | `0x5358` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0xbea4` | `0xbedc` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xc540` | `0xc570` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x1760` | `0x178c` | **`+0x2c`** |
| `__TEXT.__const` | `0x2a560` | `0x2a580` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x115c` | `0x1178` | **`+0x1c`** |

### Other Changes

```diff

-3605.14.3.501.4
+3605.16.9.501.1

-  Functions: 34445
+  Functions: 34682

-  CStrings:  3754
+  CStrings:  3770
CStrings:
+ " Key data points (e.g. for retrieval or list queries, name the items themselves) must appear inside <"
+ "%s %s: AgenticPlannerService: handed the turn to Siri X to run a non-schematized app-intent shortcut"
+ "%s: AgenticPlannerService: Siri X accepted the shortcut handoff"
+ "%s: AgenticPlannerService: fuzzy match found a non-schematized shortcut; handing off to Siri X"
+ "%s: Tool retrieval returned no response"
+ "' in this toolbox."
+ ">. By calling ui_entity_rendering on entities with ui_entity_rendering_text_components you have already presented their data to the user — do not restate it after <"
+ "Arguments schema: "
+ "PlannerToolExecutor.recordToolResult"
+ "SleepTimerEntity"
+ "[GeoAppResolver] CarPlay dock app: %s"
+ "[GeoAppResolver] Defaulting to 1P app: %s"
+ "[GeoAppResolver] Error fetching CarPlay dock app: %@"
+ "[GeoAppResolver] Foreground app: %s"
+ "[GeoAppResolver] Interaction-history app: %s"
+ "[GeoAppResolver] No signal preferred any of %s"
+ "[INSIGHTS_TIMELINE|Generate Plan|Using injected tool call - Skipping model inference|⏭️|]"
+ "[INSIGHTS_TIMELINE|Planning Loop|Ending - Shortcut handoff|✅|]"
+ "[INSIGHTS_TIMELINE|Planning Loop|Injected tool calls exhausted - Ending turn|🏁|]"
+ "[SessionSummarization] isFirstTurnOfCurrentTask() unexpectedly called during translation"
+ "callDeterministicToolRetrieval(toolNames:): Tool '%s' is already available in the prompt"
- "%s: No tools retrieved for query"
- "[GeoAppResolver] #getPreferredApp Error fetching CarPlay dock app: %@"
- "[GeoAppResolver] #getPreferredApp returning CarPlay dock app bundle id: %s"
- "[GeoAppResolver] #getPreferredApp returning foreground app bundle id: %s"
- "[GeoAppResolver] #getPreferredApp returning interaction-history app bundle id: %s"
```
