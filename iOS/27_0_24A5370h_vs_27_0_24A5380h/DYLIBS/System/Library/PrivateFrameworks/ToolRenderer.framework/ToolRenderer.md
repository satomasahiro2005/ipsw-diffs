## ToolRenderer

> `/System/Library/PrivateFrameworks/ToolRenderer.framework/ToolRenderer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81264` | `0x82fcc` | **`+0x1d68`** |
| `__TEXT.__cstring` | `0x500b` | `0x54db` | **`+0x4d0`** |
| `__TEXT.__eh_frame` | `0x5e98` | `0x5d60` | **`-0x138`** |
| `__AUTH_CONST.__const` | `0x69f0` | `0x6998` | **`-0x58`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x220` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2290` | `0x2258` | **`-0x38`** |
| `__TEXT.__swift5_reflstr` | `0x16a7` | `0x16d7` | **`+0x30`** |
| `__DATA.__data` | `0xd80` | `0xd60` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x118` | `0x138` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1160` | `0x1144` | **`-0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x1cac` | `0x1cc0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xcf8` | `0xd08` | **`+0x10`** |
| `__TEXT.__const` | `0x57b2` | `0x57c2` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x570` | `0x560` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x2a4` | `0x298` | **`-0xc`** |
| `__TEXT.__swift5_typeref` | `0x140c` | `0x1406` | **`-0x6`** |
| `__TEXT.__swift5_types` | `0x1dc` | `0x1d8` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x1b8` | `0x1b4` | **`-0x4`** |

### Other Changes

```diff

-5028.0.21.0.0
+5032.5.0.0.0

-  Functions: 3522
-  Symbols:   1094
-  CStrings:  490
+  Functions: 3529
+  Symbols:   1097
+  CStrings:  495
Symbols:
+ _OUTLINED_FUNCTION_317
+ ___swift_memcpy144_8
+ _get_enum_tag_for_layout_string 12ToolRenderer20ArgumentDefaultValueO
+ _swift_retain_n
+ _type_layout_string 12ToolRenderer20ArgumentDefaultValueO
- ___swift_memcpy136_8
- _symbolic _____ 7ToolKit14TypeIdentifierO09PrimitivecD0O0A8RendererE22PersonPythonDefinitionV
CStrings:
+ "\n\nclass Measurement:\n    \"\"\"A measurement of a quantity in a specific unit.\"\"\"\n\n    def __init__(self, "
+ "\":\n        \"\"\"This measurement converted to a different unit. Use this to normalize units before comparing or doing arithmetic with measurements.\n        Args:\n            "
+ "# ContentCollection[T] is `List[T]` renamed to surface Shortcuts' content-collection semantics. Treat it as a flat, 1-indexed collection that stands in for a single T wherever the runtime can.\n#\n# - Tools take ContentCollection[T] as input and return it as output. Mapping tools (e.g. com_apple_shortcuts_adjust_date) apply the same operation to every element and return a same-sized collection.\n# - Wherever a parameter accepts T, ContentCollection[T] is accepted in its place — the runtime resolves the collection-vs-single mismatch automatically.\n# - Property access auto-maps: e.g. `events.title` on ContentCollection[CalendarEvent] yields ContentCollection[str].\n# - Collections are flat — no ContentCollection[ContentCollection[T]].\n#\n# Subscript with get_item_from_list ONLY when:\n# - You're confident the collection has multiple items AND the next step needs exactly one of them, or\n# - You want to deterministically discard all items except one, without asking the user to choose.\n#\n# In every other case, pass the ContentCollection through directly.\nContentCollection = List"
+ ": The unit to convert the measurement to.\n        \"\"\""
+ "ContentCollection["
+ "format"
+ "is.workflow.actions.ride.requestride"
- "\n\nclass Measurement:\n    \"\"\"A measurement of a quantity in a specific unit.\"\"\"\n    \n    def __init__(self, "
- ":\n    display_name: Optional[str]\n    name_components: Optional[PersonNameComponents]\n    handle: Optional[PersonHandle]\n    label: Optional[PersonLabel]\n    relationship: Optional[PersonRelationship]"
```
