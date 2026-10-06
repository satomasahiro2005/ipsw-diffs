## DayStreamProcessorService

> `/System/Library/PrivateFrameworks/HealthAlgorithms.framework/XPCServices/DayStreamProcessorService.xpc/DayStreamProcessorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x161` | `0x1a8` | **`+0x47`** |
| `__TEXT.__text` | `0xd50` | `0xd8c` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x40` | `0x78` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x134` | `0x15f` | **`+0x2b`** |
| `__TEXT.__auth_stubs` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-150.0.0.0.0
+151.0.0.0.0

-  Symbols:   60
-  CStrings:  118
+  Symbols:   61
+  CStrings:  124
Symbols:
+ _qos_class_self
Functions:
~ sub_1000014f0 : 1096 -> 1156
CStrings:
+ "BACKGROUND"
+ "DEFAULT"
+ "UNSPECIFIED"
+ "USER_INITIATED"
+ "USER_INTERACTIVE"
+ "UTILITY"
+ "menstrualPredictionFirstPrimarySource=%{signpost.telemetry:number1}f fertilityPredictionFirstPrimarySource=%{signpost.telemetry:number2}f qos=%{public, signpost.telemetry:string1}s enableTelemetry=YES "
- "menstrualPredictionFirstPrimarySource=%{signpost.telemetry:number1}f fertilityPredictionFirstPrimarySource=%{signpost.telemetry:number2}f enableTelemetry=YES "
```
