## IOHIDPointerScrollFilter

> `/System/Library/HIDPlugins/IOHIDPointerScrollFilter.plugin/IOHIDPointerScrollFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83d4` | `0x8420` | **`+0x4c`** |

### Other Changes

```diff

-2353.0.0.0.1
+2360.0.2.0.0
Functions:
~ __ZN24IOHIDPointerScrollFilter20setPropertyForClientEPK10__CFStringPKvS4_ : 488 -> 500
~ __ZN22IOHIDSimpleAccelerator10accelerateEPdmy : 56 -> 64
~ __ZNK17ACCEL_TABLE_ENTRY1yIiEET_j : 16 -> 28
~ __ZNK17ACCEL_TABLE_ENTRY1yIdEET_j : 20 -> 32
~ __ZNK17ACCEL_TABLE_ENTRY5pointEj : 40 -> 48
~ __ZNK11ACCEL_TABLE5entryEi : 44 -> 60
~ __ZlsRNSt3__113basic_ostreamIcNS_11char_traitsIcEEEERK11ACCEL_TABLE : 480 -> 488
~ sub_24754c8c0 -> sub_248af390c : 552 -> 564
~ __ZN24IOHIDPointerScrollFilterD2Ev : 168 -> 180
~ __ZNK24IOHIDPointerScrollFilter9serializeEP14__CFDictionary : 1792 -> 1780
~ __ZN24IOHIDPointerScrollFilter15accelerateEventEP12__IOHIDEvent : 1080 -> 1072
~ __ZN24IOHIDPointerScrollFilter23setupScrollAccelerationEd : 2196 -> 2192
```
