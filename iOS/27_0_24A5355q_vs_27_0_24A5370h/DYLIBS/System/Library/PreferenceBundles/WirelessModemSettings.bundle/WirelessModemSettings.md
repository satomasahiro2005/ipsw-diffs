## WirelessModemSettings

> `/System/Library/PreferenceBundles/WirelessModemSettings.bundle/WirelessModemSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13668` | `0x13648` | **`-0x20`** |

### Other Changes

```diff

-840.20.0.0.0
+840.21.0.0.0
Functions:
~ -[WiFiPasswordController textField:shouldChangeCharactersInRange:replacementString:] : 196 -> 192
~ -[HotspotClientUsageController getSpecifiersForClients] : 1032 -> 1028
~ -[WMSPersonalHotspotDataUsageCache _usageForBundleID:inPeriod:] : 812 -> 808
~ -[WMSPersonalHotspotDataUsageCache hotspotClientIDsForPeriod:mruMap:] : 1304 -> 1312
~ -[WirelessModemController updateDataUsageSection] : 868 -> 864
~ -[WirelessModemController dataUsageString] : 776 -> 772
~ -[TetheringSwitchFooterView setText:] : 656 -> 648
~ -[TetheringSwitchFooterView sizeThatFits:inTableView:shouldSetSize:] : 548 -> 544
~ sub_247c0ff00 -> sub_2491b9ee8 : 1380 -> 1376
~ sub_247c10804 -> sub_2491ba7e8 : 280 -> 276
```
