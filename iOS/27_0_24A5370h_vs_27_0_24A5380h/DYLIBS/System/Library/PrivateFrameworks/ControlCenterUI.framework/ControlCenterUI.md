## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba654` | `0xbaf24` | **`+0x8d0`** |
| `__DATA_DIRTY.__objc_data` | `0x3960` | `0x3a40` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x1d42` | `0x1de2` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x2bb4` | `0x2c40` | **`+0x8c`** |
| `__DATA_CONST.__const` | `0x1368` | `0x13f0` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x29fc` | `0x2a5c` | **`+0x60`** |
| `__DATA_DIRTY.__data` | `0xe10` | `0xe60` | **`+0x50`** |
| `__TEXT.__cstring` | `0x47a4` | `0x47f4` | **`+0x50`** |
| `__DATA.__data` | `0x3a30` | `0x3a70` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1340` | `0x1380` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2d40` | `0x2d70` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1348` | `0x1368` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb500` | `0xb4e0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x11120` | `0x11108` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x750` | `0x738` | **`-0x18`** |
| `__DATA.__bss` | `0x11b0` | `0x11a0` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x8b0` | `0x8c0` | **`+0x10`** |
| `__TEXT.__const` | `0x2c2a` | `0x2c3a` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd30` | `0xd28` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x220` | `0x228` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-699.0.100.0.0
+701.101.0.0.0

-  Functions: 5034
-  Symbols:   5610
-  CStrings:  849
+  Functions: 5044
+  Symbols:   5615
+  CStrings:  850
Symbols:
+ -[CCUIAirDropModuleViewController _updateStateAnimated:]
+ -[CCUIAirDropModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUIAirDropModuleViewController updateStateAnimated:]
+ -[CCUIBluetoothModuleViewController _updateStateAnimated:]
+ -[CCUIBluetoothModuleViewController _updateWithState:animated:]
+ -[CCUIBluetoothModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUICellularDataModuleViewController _applyStateWithCapable:enabled:airplaneMode:animated:]
+ -[CCUICellularDataModuleViewController _updateStateAnimated:]
+ -[CCUICellularDataModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUICellularDataModuleViewController updateStateAnimated:]
+ -[CCUIHeaderPocketView sensorAttributionExpandedViewController:didChangeExpanded:]
+ -[CCUIModuleInstanceManager removeAllModules]
+ -[CCUISatelliteModuleViewController _updateState:animated:]
+ -[CCUISatelliteModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUISatelliteModuleViewController updateStateAnimated:]
+ -[CCUIVPNModuleViewController _updateStateAnimated:]
+ -[CCUIVPNModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUIVPNModuleViewController updateStateAnimated:]
+ -[CCUIWiFiModuleViewController _glyphImageForState:currentSignalBars:forceSignalBars:network:]
+ -[CCUIWiFiModuleViewController _updateStateAnimated:]
+ -[CCUIWiFiModuleViewController _updateWithState:animated:]
+ -[CCUIWiFiModuleViewController performGlyphButtonActionForControlTemplateView:]
+ -[CCUIWiFiModuleViewController updateStateAnimated:]
+ GCC_except_table45
+ GCC_except_table47
+ GCC_except_table52
+ GCC_except_table56
+ _CCUIApplySecondaryAttributionLabelStyle
+ _NSSelectorFromString
+ _OBJC_CLASS_$_CCUIGlyphButtonConfiguration
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CCUISensorAttributionExpandedViewControllerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CCUISensorAttributionExpandedViewControllerDelegate
+ __OBJC_LABEL_PROTOCOL_$_CCUISensorAttributionExpandedViewControllerDelegate
+ __OBJC_PROTOCOL_$_CCUISensorAttributionExpandedViewControllerDelegate
+ __PROTOCOL_CCUISensorAttributionExpandedViewControllerDelegate
+ __PROTOCOL_INSTANCE_METHODS_CCUISensorAttributionExpandedViewControllerDelegate
+ __PROTOCOL_METHOD_TYPES_CCUISensorAttributionExpandedViewControllerDelegate
+ __UIClamp
+ __UIUnlerp
+ ___52-[CCUIVPNModuleViewController _updateStateAnimated:]_block_invoke
+ ___56-[CCUIAirDropModuleViewController _updateStateAnimated:]_block_invoke
+ ___58-[CCUIWiFiModuleViewController _updateWithState:animated:]_block_invoke
+ ___59-[CCUISatelliteModuleViewController _updateState:animated:]_block_invoke
+ ___61-[CCUICellularDataModuleViewController _updateStateAnimated:]_block_invoke
+ ___61-[CCUICellularDataModuleViewController _updateStateAnimated:]_block_invoke_2
+ ___61-[CCUICellularDataModuleViewController _updateStateAnimated:]_block_invoke_3
+ ___63-[CCUIBluetoothModuleViewController _updateWithState:animated:]_block_invoke
+ ___93-[CCUICellularDataModuleViewController _applyStateWithCapable:enabled:airplaneMode:animated:]_block_invoke
+ ___block_descriptor_41_e8_32s_e45_v16?0"<CCUIControlTemplateViewProperties>"8ls32l8
+ ___block_descriptor_41_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_42_e8_32s_e45_v16?0"<CCUIControlTemplateViewProperties>"8ls32l8
+ ___block_descriptor_44_e8_32w_e5_v8?0lw32l8
+ __updateStateAnimated:.onceToken
+ __updateStateAnimated:.serialQueue
+ _flat unique So51CCUISensorAttributionExpandedViewControllerDelegate_p
+ _objc_autorelease
+ _symbolic $s15ControlCenterUI47SensorAttributionExpandedViewControllerDelegateP
+ _symbolic ______pSgXw 15ControlCenterUI47SensorAttributionExpandedViewControllerDelegateP
- -[CCUIAirDropModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUIAirDropModuleViewController _updateState]
- -[CCUIAirDropModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUIAirDropModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUIAirDropModuleViewController updateState]
- -[CCUIBluetoothModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUIBluetoothModuleViewController _updateState]
- -[CCUIBluetoothModuleViewController _updateWithState:]
- -[CCUIBluetoothModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUIBluetoothModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUICellularDataModuleViewController _applyStateWithCapable:enabled:airplaneMode:]
- -[CCUICellularDataModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUICellularDataModuleViewController _updateState]
- -[CCUICellularDataModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUICellularDataModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUICellularDataModuleViewController updateState]
- -[CCUISatelliteModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUISatelliteModuleViewController _updateState:]
- -[CCUISatelliteModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUISatelliteModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUISatelliteModuleViewController updateState]
- -[CCUIVPNModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUIVPNModuleViewController _updateState]
- -[CCUIVPNModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUIVPNModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUIVPNModuleViewController updateState]
- -[CCUIWiFiModuleViewController _glyphImageForState:currentSignalBars:forceSignalBars:network:applyConfiguration:]
- -[CCUIWiFiModuleViewController _glyphViewForExpandedConnectivityModuleTapped]
- -[CCUIWiFiModuleViewController _updateState]
- -[CCUIWiFiModuleViewController _updateWithState:]
- -[CCUIWiFiModuleViewController glyphViewForExpandedConnectivityModule]
- -[CCUIWiFiModuleViewController setGlyphViewForExpandedConnectivityModule:]
- -[CCUIWiFiModuleViewController updateState]
- GCC_except_table15
- GCC_except_table24
- GCC_except_table44
- GCC_except_table46
- GCC_except_table49
- GCC_except_table53
- GCC_except_table55
- _OBJC_IVAR_$_CCUIAirDropModuleViewController._glyphViewForExpandedConnectivityModule
- _OBJC_IVAR_$_CCUIBluetoothModuleViewController._glyphViewForExpandedConnectivityModule
- _OBJC_IVAR_$_CCUICellularDataModuleViewController._glyphViewForExpandedConnectivityModule
- _OBJC_IVAR_$_CCUISatelliteModuleViewController._glyphViewForExpandedConnectivityModule
- _OBJC_IVAR_$_CCUIVPNModuleViewController._glyphViewForExpandedConnectivityModule
- _OBJC_IVAR_$_CCUIWiFiModuleViewController._glyphViewForExpandedConnectivityModule
- ___52-[CCUICellularDataModuleViewController _updateState]_block_invoke
- ___52-[CCUICellularDataModuleViewController _updateState]_block_invoke_2
- ___52-[CCUICellularDataModuleViewController _updateState]_block_invoke_3
- ___block_descriptor_43_e8_32w_e5_v8?0lw32l8
- __updateState.onceToken
- __updateState.serialQueue
- _swift_willThrowTypedImpl
CStrings:
+ "[VPN] Error toggling VPN: %{public}@"
+ "t1"
+ "updateIconViewVisibility"
+ "v16@?0@\"<CCUIControlTemplateViewProperties>\"8"
- "#"
- "[VPN] Error togging VPN: %{public}@"
- "tA"
```
