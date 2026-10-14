## HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25f8c` | `0x27e70` | **`+0x1ee4`** |
| `__DATA_CONST.__cfstring` | `0x29a0` | `0x2fc0` | **`+0x620`** |
| `__TEXT.__oslogstring` | `0x503b` | `0x54d7` | **`+0x49c`** |
| `__TEXT.__cstring` | `0x1ef6` | `0x232d` | **`+0x437`** |
| `__TEXT.__ustring` | `0x54` | `0x168` | **`+0x114`** |
| `__TEXT.__objc_stubs` | `0x3d60` | `0x3dc0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x3ff4` | `0x4037` | **`+0x43`** |
| `__DATA_CONST.__const` | `0x878` | `0x8a0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x13b0` | `0x13c8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x448` | `0x460` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x760` | `0x768` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x8fc` | `0x900` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1520.2.3.0.2
+1520.2.7.1.3

-  Functions: 635
-  Symbols:   303
-  CStrings:  1685
+  Functions: 639
+  Symbols:   306
+  CStrings:  1758
Symbols:
+ _HomeUtilAggregateRoomsKey
+ _HomeUtilAggregateThermostatsKey
+ _OBJC_CLASS_$_NSLock
CStrings:
+ "          Humidities: %@\n"
+ "          Temperatures: %@\n"
+ "        %@ (%@)\n"
+ "      Aggregated Humidity:        %.2f%%\n"
+ "      Aggregated Humidity: %.2f%%\n"
+ "      Aggregated Temperature:     %.2f°C\n"
+ "      Aggregated Temperature: %.2f°C\n"
+ "      Humidity Sensor Priority: %@\n"
+ "      Last Published Humidity:    %.2f%%\n"
+ "      Last Published Humidity:    null\n"
+ "      Last Published Temperature: %.2f°C\n"
+ "      Last Published Temperature: null\n"
+ "      Monitored Rooms (%lu):\n"
+ "      Monitors All Rooms: %@\n"
+ "      Sensors:\n"
+ "      Service Rooms (%lu):\n"
+ "      Service Rooms: (none)\n"
+ "      Temperature Sensor Priority: %@\n"
+ "      Use Service Rooms: %@\n"
+ "    %@ (%@)\n"
+ "  (not primary resident for this home or no data)\n\n"
+ "  Rooms:\n"
+ "  Thermostats:\n"
+ "  → Aggregate climate data not available or device is not primary resident"
+ "  → Fetching aggregate climate data for home %{public}@"
+ "  → No aggregate climate data available"
+ "  → No aggregate climate data to write"
+ "  → Skipping: device is not the primary resident"
+ "  ✓ Aggregate climate data collected"
+ "  ✗ Failed to fetch aggregate climate data for home %{public}@: %@"
+ "  ✗ Failed to write aggregate climate data: %@"
+ "  ✗ Timed out waiting for aggregate climate data"
+ "Home: %@\n\n"
+ "HomeUtil accessory climate fetch-aggregate-data"
+ "STEP %lu/%lu: Collecting Aggregate Climate Data"
+ "[%{public}@]   → Aggregate climate data not available or device is not primary resident"
+ "[%{public}@]   → Fetching aggregate climate data for home %{public}@"
+ "[%{public}@]   → No aggregate climate data available"
+ "[%{public}@]   → No aggregate climate data to write"
+ "[%{public}@]   → Skipping: device is not the primary resident"
+ "[%{public}@]   ✓ Aggregate climate data collected"
+ "[%{public}@]   ✗ Failed to fetch aggregate climate data for home %{public}@: %@"
+ "[%{public}@]   ✗ Failed to write aggregate climate data: %@"
+ "[%{public}@]   ✗ Timed out waiting for aggregate climate data"
+ "[%{public}@] STEP %lu/%lu: Collecting Aggregate Climate Data"
+ "accessoryName"
+ "accessoryUUID"
+ "aggregatedHumidity"
+ "aggregatedTemperature"
+ "char %@: %.2f%%"
+ "char %@: %.2f°C"
+ "false"
+ "fetchAggregateClimateDataForDiagnosticsWithCompletion:"
+ "homeutil-aggregate-climate-data.txt"
+ "humidities"
+ "humiditySensorPriorityState"
+ "lastPublishedHumidity"
+ "lastPublishedTemperature"
+ "lock"
+ "monitoredRoomUUIDs"
+ "monitorsAllRooms"
+ "roomName"
+ "roomUUID"
+ "sensors"
+ "serviceRoomUUIDs"
+ "temperatureSensorPriorityState"
+ "temperatures"
+ "thermostatName"
+ "thermostatUUID"
+ "true"
+ "unlock"
+ "useServiceRooms"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
```
