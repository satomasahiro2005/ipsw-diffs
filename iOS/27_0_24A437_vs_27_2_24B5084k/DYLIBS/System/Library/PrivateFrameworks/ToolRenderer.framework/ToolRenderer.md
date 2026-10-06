## ToolRenderer

> `/System/Library/PrivateFrameworks/ToolRenderer.framework/ToolRenderer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85f50` | `0x8857c` | **`+0x262c`** |
| `__AUTH_CONST.__const` | `0x6d18` | `0x7380` | **`+0x668`** |
| `__TEXT.__const` | `0x5b32` | `0x5f92` | **`+0x460`** |
| `__DATA.__bss` | `0x6210` | `0x6510` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0x5f40` | `0x6178` | **`+0x238`** |
| `__TEXT.__swift5_fieldmd` | `0x1dc0` | `0x1f18` | **`+0x158`** |
| `__TEXT.__constg_swiftt` | `0x11c8` | `0x12e4` | **`+0x11c`** |
| `__TEXT.__unwind_info` | `0x2310` | `0x23f0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x574b` | `0x57fb` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x1767` | `0x17e7` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x1480` | `0x14fa` | **`+0x7a`** |
| `__TEXT.__swift5_proto` | `0x580` | `0x5d8` | **`+0x58`** |
| `__TEXT.__swift_as_entry` | `0x298` | `0x2e8` | **`+0x50`** |
| `__DATA.__data` | `0xe20` | `0xe68` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x9e8` | `0xa28` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x468` | `0x498` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x4e0` | `0x510` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x1bc` | `0x1e8` | **`+0x2c`** |
| `__TEXT.__swift5_types` | `0x1e8` | `0x204` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0xb4` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xd50` | `0xd58` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x34` | **`+0x4`** |

### Other Changes

```diff

-5037.109.0.0.0
+5110.0.8.0.0

-  Functions: 3660
-  Symbols:   1137
-  CStrings:  508
+  Functions: 3787
+  Symbols:   1150
+  CStrings:  511
Symbols:
+ _WFWorkflowTypeShowInSearch
+ ___swift_exist.box.addr_destructor.74Tm
+ _associated conformance So18WFWorkflowTypeNameaSHSCSQ
+ _associated conformance So18WFWorkflowTypeNameas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So18WFWorkflowTypeNameas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _symbolic $s12ToolRenderer20RunSurfaceEnablementP
+ _symbolic _____ 12ToolRenderer15WatchEnablementV
+ _symbolic _____ 12ToolRenderer20ShareSheetEnablementV
+ _symbolic _____ 12ToolRenderer22QuickActionsEnablementV
+ _symbolic _____ 12ToolRenderer22ShowInSearchEnablementV
+ _symbolic _____ 12ToolRenderer23WhatsOnScreenEnablementV
+ _symbolic _____ 12ToolRenderer31EnablementClassPythonDefinitionV
+ _symbolic _____ So18WFWorkflowTypeNamea
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 12ToolRenderer20RunSurfaceEnablementP
+ _type_layout_string 12ToolRenderer15WatchEnablementV
+ _type_layout_string 12ToolRenderer31EnablementClassPythonDefinitionV
- _OUTLINED_FUNCTION_332
- _WFWorkflowTypeMenuBar
- _WFWorkflowTypeSleep
CStrings:
+ "\": ...\n@staticmethod\ndef "
+ "Referable = TypeVar(\"Referable\")\n\nclass CatalogRef(Generic[Referable]):\n    \"\"\"\n    A reference to a value in the parameter catalog.\n    \"\"\"\n\ndef ref(tag: int, /) -> CatalogRef:\n    \"\"\"\n    A reference to an entry in the parameter catalog.\n    Only tags returned from tool calls are valid.\n    Tag must be formatted as a 4 digit hex number, e.g. 0xABCD\n    \"\"\"\n    ...\n\nclass Resolved(CatalogRef[Referable]):\n    \"\"\"\n    An entity which must be retrieved from the user's device.\n    Identify it by searching for the entity by name, then pass the returned catalog reference (ref(0x…)).\n    \"\"\"\n\nclass Picked(CatalogRef[Referable]):\n    \"\"\"\n    A value that must be chosen by the user.\n    Use the pick tool with a descriptive question to ask the user to select this value.\n    \"\"\"\n\nclass Comparable:\n    \"\"\"\n    A type whose values can be searched by name.\n    Name searches return catalog references for values of this type.\n    \"\"\""
+ "Whether the shortcut runs on the "
+ "from typing import Any, Callable, Optional, Union, List, Dict, Literal, TypeVar, Generic, Protocol"
+ "input_from_search"
+ "input_from_search: bool = False"
+ "input_from_search=True"
+ "on the specified run surfaces"
- "INPUT_FROM_SEARCH"
- "Referable = TypeVar(\"Referable\")\n\nclass CatalogRef(Generic[Referable]):\n    \"\"\"\n    A reference to a value in the parameter catalog.\n    \"\"\"\n\ndef ref(tag: int, /) -> CatalogRef:\n    \"\"\"\n    Represents a catalog entry returned by find_entities or pick.\n    Only tags returned from these tools are valid.\n    Tag must be formatted as a 4 digit hex number, e.g. 0xABCD\n    \"\"\"\n    ...\n\nclass Resolved(CatalogRef[Referable]):\n    \"\"\"\n    An entity which must be retrieved from the user's device.\n    Retrieve entites using the find_entities tool.\n    \"\"\"\n\nclass Picked(CatalogRef[Referable]):\n    \"\"\"\n    A value that must be chosen by the user.\n    Use the pick tool with a descriptive question to ask the user to select this value.\n    \"\"\"\n\nclass Comparable:\n    \"\"\"\n    A type whose values can be searched by name.\n    Use the find_entities tool to resolve values of this type.\n    \"\"\""
- "The surface on which to show this shortcut."
- "from typing import Any, Callable, Optional, Union, List, Dict, Literal, TypeVar, Generic"
- "on the specified run surface"
```
