## WorkflowResponsiveness

> `/System/Library/PrivateFrameworks/WorkflowResponsiveness.framework/WorkflowResponsiveness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d740` | `0x3f128` | **`+0x19e8`** |
| `__TEXT.__gcc_except_tab` | `0x14dc` | `0x182c` | **`+0x350`** |
| `__TEXT.__cstring` | `0x86f6` | `0x89f9` | **`+0x303`** |
| `__AUTH_CONST.__objc_const` | `0x1a40` | `0x1cc0` | **`+0x280`** |
| `__AUTH_CONST.__cfstring` | `0x5140` | `0x52a0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x900` | `0xa08` | **`+0x108`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x890` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x918` | `0x9a0` | **`+0x88`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x628` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x5bce` | `0x5ba2` | **`-0x2c`** |
| `__DATA.__objc_ivar` | `0x190` | `0x1b8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x360` | `0x380` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-435.0.0.0.0
+440.0.0.0.0

-  Functions: 698
-  Symbols:   1110
-  CStrings:  690
+  Functions: 730
+  Symbols:   1170
+  CStrings:  703
Symbols:
+ +[WRWorkflow allDisabledWorkflows]
+ +[WRWorkflow loadWorkflowFromPlistURL:isOverride:telemetryEnabled:diagnosticsEnabled:isDisabled:]
+ -[WRDiagnostic filterTailspinLogsToSubsystemCategory]
+ -[WRDisabledWorkflow .cxx_destruct]
+ -[WRDisabledWorkflow disabledViaOverride]
+ -[WRDisabledWorkflow disabledViaTasking]
+ -[WRDisabledWorkflow initWithName:]
+ -[WRDisabledWorkflow name]
+ -[WRDisabledWorkflow originalPlistPath]
+ -[WRDisabledWorkflow setDisabledViaOverride:]
+ -[WRDisabledWorkflow setDisabledViaTasking:]
+ -[WRDisabledWorkflow setOriginalPlistPath:]
+ -[WRWorkflow filterTailspinLogsToSubsystemCategory]
+ -[WRWorkflow originalPlistPath]
+ -[WRWorkflow overriddenViaCLI]
+ -[WRWorkflow overriddenViaTasking]
+ -[WRWorkflow resolveSourcePath:workflowName:isOverride:]
+ -[WRWorkflow setOriginalPlistPath:]
+ -[WRWorkflow setOverriddenViaCLI:]
+ -[WRWorkflow setOverriddenViaTasking:]
+ -[WRWorkflow setSourcePath:]
+ -[WRWorkflow sourcePath]
+ -[WRWorkflowEventTracker gatherDiagnosticsWithTailspin:tailspinIncludeOSLogs:subsystemCategoryFilter:]
+ GCC_except_table14
+ GCC_except_table143
+ GCC_except_table152
+ GCC_except_table17
+ GCC_except_table24
+ GCC_except_table61
+ _NSURLFileSizeKey
+ _OBJC_CLASS_$_WRDisabledWorkflow
+ _OBJC_IVAR_$_WRDiagnostic._filterTailspinLogsToSubsystemCategory
+ _OBJC_IVAR_$_WRDisabledWorkflow._disabledViaOverride
+ _OBJC_IVAR_$_WRDisabledWorkflow._disabledViaTasking
+ _OBJC_IVAR_$_WRDisabledWorkflow._name
+ _OBJC_IVAR_$_WRDisabledWorkflow._originalPlistPath
+ _OBJC_IVAR_$_WRWorkflow._filterTailspinLogsToSubsystemCategory
+ _OBJC_IVAR_$_WRWorkflow._originalPlistPath
+ _OBJC_IVAR_$_WRWorkflow._overriddenViaCLI
+ _OBJC_IVAR_$_WRWorkflow._overriddenViaTasking
+ _OBJC_IVAR_$_WRWorkflow._sourcePath
+ _OBJC_METACLASS_$_WRDisabledWorkflow
+ _OUTLINED_FUNCTION_189
+ _OUTLINED_FUNCTION_190
+ _OUTLINED_FUNCTION_72
+ _OUTLINED_FUNCTION_73
+ _TSPDumpOptions_OSSignpostLogSubsystemCategories
+ _WRDiagnosticOptionFilterTailspinLogsToSubsystemCategoriesKey
+ _WRSortedSubsystemCategoryFilter
+ _WRValidateSubsystemCategoryFilterDict
+ _WRWorkflowOptionFilterTailspinLogsToSubsystemCategoriesKey
+ __OBJC_$_INSTANCE_METHODS_WRDisabledWorkflow
+ __OBJC_$_INSTANCE_VARIABLES_WRDisabledWorkflow
+ __OBJC_$_PROP_LIST_WRDisabledWorkflow
+ __OBJC_CLASS_RO_$_WRDisabledWorkflow
+ __OBJC_METACLASS_RO_$_WRDisabledWorkflow
+ ___102-[WRWorkflowEventTracker gatherDiagnosticsWithTailspin:tailspinIncludeOSLogs:subsystemCategoryFilter:]_block_invoke
+ ___26+[WRWorkflow allWorkflows]_block_invoke_2
+ ___34+[WRWorkflow allDisabledWorkflows]_block_invoke
+ ___34+[WRWorkflow allDisabledWorkflows]_block_invoke_2
+ ___51-[WRWorkflowEventTracker gatherDiagnosticsIfNeeded]_block_invoke
+ ___51-[WRWorkflowEventTracker gatherDiagnosticsIfNeeded]_block_invoke_2
+ ___WRSortedSubsystemCategoryFilter_block_invoke
+ ___WRValidateSubsystemCategoryFilterDict_block_invoke
+ ___block_descriptor_40_e8_32r_e22_v16?0"NSDictionary"8lr32l8
+ ___block_descriptor_40_e8_32r_e34_v32?0"NSString"8"NSArray"16^B24lr32l8
+ ___block_descriptor_40_e8_32s_e34_v32?0"NSString"8"NSArray"16^B24ls32l8
+ ___block_descriptor_40_e8_32s_e38_"WRDisabledWorkflow"16?0"NSString"8ls32l8
+ ___block_descriptor_50_e8_32s40r_e30_"WRWorkflow"20?0"NSURL"8B16ls32l8r40l8
+ ___block_descriptor_50_e8_32s40s_e18_v20?0"NSURL"8B16ls32l8s40l8
+ _objc_setProperty_atomic_copy
- -[WRWorkflowEventTracker gatherDiagnosticsWithTailspin:tailspinIncludeOSLogs:]
- GCC_except_table12
- GCC_except_table150
- GCC_except_table47
- GCC_except_table9
- _OUTLINED_FUNCTION_76
- _OUTLINED_FUNCTION_77
- ___78-[WRWorkflowEventTracker gatherDiagnosticsWithTailspin:tailspinIncludeOSLogs:]_block_invoke
- ___block_descriptor_50_e8_32s40r_e27_"WRWorkflow"16?0"NSURL"8ls32l8r40l8
- ___block_descriptor_50_e8_32s40s_e15_v16?0"NSURL"8ls32l8s40l8
- _objc_release_x3
CStrings:
+ "!5"
+ "%@ is not an integer (%f)"
+ "%@.plist"
+ "%{public}@: Loaded workflow from %{public}@"
+ "*"
+ "@\"WRDisabledWorkflow\"16@?0@\"NSString\"8"
+ "@\"WRWorkflow\"20@?0@\"NSURL\"8B16"
+ "No categories specified for option_filter_tailspin_logs_to_subsystem_categories subsystem \"%@\""
+ "Wrong key type under option_filter_tailspin_logs_to_subsystem_categories: %s, expected NSString"
+ "Wrong value type for option_filter_tailspin_logs_to_subsystem_categories subsystem \"%@\" array value: %s"
+ "Wrong value type for option_filter_tailspin_logs_to_subsystem_categories subsystem \"%@\": %s"
+ "filterTailspinLogsToSubsystemCategory"
+ "name:%@\ntriggerThresholdDurationSum:%f\ntriggerThresholdDurationUnion:%f\ntriggerThresholdDurationSingle:%f\ntriggerThresholdCount:%u\ntriggerEventTimeout:%u\ngatherTailspin:%u\ntailspinIncludeOSLogs:%u\nreportSpindumpForThisThread:%u\nreportSpindumpForThreadWithName:%@\nreportSpindumpForMainThread:%u\nreportSpindumpForThisDispatchQueue:%u\nreportSpindumpForDispatchQueueWithLabel:%@\nreportOtherSignpostWithName:%@\nreportProcessesWithName:%@\nreportOmittingNetworkBoundIntervals:%u\nfilterTailspinLogsToSubsystemCategory:%@\n"
+ "option_filter_tailspin_logs_to_subsystem_categories"
+ "option_filter_tailspin_logs_to_subsystem_categories subsystem \"%@\" array has \"*\" but is not the only category: %@"
+ "unhandled diagnostic dictionary key %@"
+ "unhandled diagnostic dictionary key %{public}@"
+ "unhandled workflow dictionary key %@"
+ "unhandled workflow dictionary key %{public}@"
+ "v16@?0@\"NSDictionary\"8"
+ "v20@?0@\"NSURL\"8B16"
- "!4"
- "%{public}@: Adding workflow from %{public}@"
- "%{public}@: Found workflow from %@"
- "%{public}@: Ignoring duplicate workflow from %{public}@"
- "%{public}@: Unable to read in %{public}@: %@"
- "@\"WRWorkflow\"16@?0@\"NSURL\"8"
- "name:%@\ntriggerThresholdDurationSum:%f\ntriggerThresholdDurationUnion:%f\ntriggerThresholdDurationSingle:%f\ntriggerThresholdCount:%u\ntriggerEventTimeout:%u\ngatherTailspin:%u\ntailspinIncludeOSLogs:%u\nreportSpindumpForThisThread:%u\nreportSpindumpForThreadWithName:%@\nreportSpindumpForMainThread:%u\nreportSpindumpForThisDispatchQueue:%u\nreportSpindumpForDispatchQueueWithLabel:%@\nreportOtherSignpostWithName:%@\nreportProcessesWithName:%@\nreportOmittingNetworkBoundIntervals:%u\n"
- "v16@?0@\"NSURL\"8"
```
