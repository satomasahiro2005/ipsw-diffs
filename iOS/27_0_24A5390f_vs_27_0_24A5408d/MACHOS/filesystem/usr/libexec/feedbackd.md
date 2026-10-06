## feedbackd

> `/usr/libexec/feedbackd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77854` | `0x78a0c` | **`+0x11b8`** |
| `__TEXT.__auth_stubs` | `0x1ed0` | `0x1f80` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x43f0` | `0x4478` | **`+0x88`** |
| `__DATA_CONST.__auth_got` | `0xf70` | `0xfc8` | **`+0x58`** |
| `__TEXT.__cstring` | `0x2c45` | `0x2c85` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x15b0` | `0x15e8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xd10` | `0xd44` | **`+0x34`** |
| `__TEXT.__const` | `0x1dd8` | `0x1e08` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1de0` | `0x1e08` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x7b0` | `0x7d0` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x278f` | `0x279f` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x724` | `0x734` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x3f0` | `0x3f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-232.0.0.0.0
+235.0.0.0.0

+  - /System/Library/PrivateFrameworks/IntelligencePlatformQuery.framework/IntelligencePlatformQuery

-  Functions: 1436
-  Symbols:   854
-  CStrings:  749
+  Functions: 1451
+  Symbols:   870
+  CStrings:  755
Symbols:
+ _$s25IntelligencePlatformQuery12ResultColumnV12currentValueSSSgyF
+ _$s25IntelligencePlatformQuery12ResultColumnV12currentValueSiyF
+ _$s25IntelligencePlatformQuery12ResultColumnVMa
+ _$s25IntelligencePlatformQuery13SQLConnectionC7execute5query8bindings5blockySS_SayAC8Bindable_pSgGyAA15ResultSetCursorCKXEtKF
+ _$s25IntelligencePlatformQuery13SQLConnectionC7useCase7accountACSo05BMUseF10Identifiera_So9BMAccountCSgtKcfC
+ _$s25IntelligencePlatformQuery13SQLConnectionC8BindableMp
+ _$s25IntelligencePlatformQuery13SQLConnectionCMa
+ _$s25IntelligencePlatformQuery15ResultSetCursorC3rowSDySSypSgGyKF
+ _$s25IntelligencePlatformQuery15ResultSetCursorC4stepSbyKF
+ _$s25IntelligencePlatformQuery15ResultSetCursorC6columnyAA0D6ColumnVSSKF
+ _$sSS25IntelligencePlatformQuery13SQLConnectionC8BindableAAWP
+ _$ss15_print_unlockedyyx_q_zts16TextOutputStreamR_r0_lF
+ _$ss26DefaultStringInterpolationVN
+ _$ss26DefaultStringInterpolationVs16TextOutputStreamsWP
+ _SBSRemoteAlertHandleInvalidationErrorDomain
+ _swift_retain_x8
CStrings:
+ "\n        )\n        AS rn FROM (\n            SELECT\n                json_extract(commonMetadata, '$.evaluationUuid') evaluationUuid,\n                replace(json_extract(commonMetadata, '$.evaluationUuid'), '-', '') compareableEvaluationUuid,\n                json_extract(commonMetadata, '$.featureDomain') featureDomain,\n                eventTimestamp,\n                commonMetadata\n            FROM (\n                SELECT\n                    eventTimestamp,\n                    commonMetadata\n                FROM \""
+ "\n    )\n    AS rn FROM (\n        SELECT\n            json_extract(commonMetadata, '$.evaluationUuid') evaluationUuid,\n            replace(json_extract(commonMetadata, '$.evaluationUuid'), '-', '') compareableEvaluationUuid,\n            json_extract(commonMetadata, '$.featureDomain') featureDomain,\n            eventTimestamp,\n            commonMetadata\n        FROM (\n            SELECT\n                eventTimestamp,\n                commonMetadata\n            FROM \""
+ "\n)\nSELECT\n    *\nFROM (\n    SELECT\n        *,\n        '"
+ " days')\n        AND evaluationUuid NOT IN (\n            "
+ "\"\n                UNION SELECT\n                    eventTimestamp,\n                    commonMetadata\n                FROM \""
+ "\"\n            UNION SELECT\n                eventTimestamp,\n                commonMetadata\n            FROM \""
+ "\"\n        )\n        WHERE datetime(eventTimestamp, 'unixepoch') >= datetime('now', '-"
+ "\"\n    WHERE evaluationUuid IN results\n    UNION SELECT\n        *,\n        '"
+ "\"\n)\nWHERE id = ?"
+ "$.dictionary._0."
+ "'\n        ) id\n    FROM \""
+ "' as stream,\n        json_extract(commonMetadata, '$.evaluationUuid') evaluationUuid,\n        generatedContent,\n        originalContent,\n        commonMetadata\n    FROM \""
+ "Duplicate values for key: '"
+ "Failed to execute IPSQL query: %@"
+ "Failed to initialize IPSQL connection: %@"
+ "FeedbackDonationFetch"
+ "FeedbackDuplicateCheck"
+ "Remote alert view service initialization failure: %{public}@"
+ "SELECT\n    count(*) count\nFROM (\n    SELECT\n        json_extract(\n            json_extract(\n                originalContent,\n                '$.text'\n            ),\n            '"
+ "SELECT\n    evaluationUuid\nFROM (\n    SELECT\n        featureDomain,\n        eventTimestamp,\n        evaluationUuid,\n        commonMetadata,\n        ROW_NUMBER()\n    OVER (\n        PARTITION BY json_extract(commonMetadata, '$.featureDomain')\n        ORDER BY eventTimestamp "
+ "Swift/NativeDictionary.swift"
+ "WITH results AS (\n    SELECT\n        evaluationUuid\n    FROM (\n        SELECT\n            featureDomain,\n            eventTimestamp,\n            evaluationUuid,\n            commonMetadata,\n            ROW_NUMBER()\n        OVER (\n            PARTITION BY json_extract(commonMetadata, '$.featureDomain')\n            ORDER BY eventTimestamp "
+ "fetchDonationIDs(count:fromLatest:excludingEvaluationIDs:connection:)"
+ "fetchDonations(count:fromLatest:excludingEvaluationIDs:connection:)"
- "\n        )\n        AS rn FROM (\n            SELECT\n                json_extract(commonMetadata_json, \"$.evaluationUuid\") evaluationUuid,\n                replace(json_extract(commonMetadata_json, \"$.evaluationUuid\"), \"-\", \"\") compareableEvaluationUuid,\n                json_extract(commonMetadata_json, \"$.featureDomain\") featureDomain,\n                eventTimestamp,\n                commonMetadata_json\n            FROM (\n                SELECT\n                    eventTimestamp,\n                    commonMetadata_json\n                FROM \""
- "\n    )\n    AS rn FROM (\n        SELECT\n            json_extract(commonMetadata_json, \"$.evaluationUuid\") evaluationUuid,\n            replace(json_extract(commonMetadata_json, \"$.evaluationUuid\"), \"-\", \"\") compareableEvaluationUuid,\n            json_extract(commonMetadata_json, \"$.featureDomain\") featureDomain,\n            eventTimestamp,\n            commonMetadata_json\n        FROM (\n            SELECT\n                eventTimestamp,\n                commonMetadata_json\n            FROM \""
- "\n)\nSELECT\n    *\nFROM (\n    SELECT\n        *,\n        \""
- " days\")\n        AND evaluationUuid NOT IN (\n            "
- "\"\n                UNION SELECT\n                    eventTimestamp,\n                    commonMetadata_json\n                FROM \""
- "\"\n            UNION SELECT\n                eventTimestamp,\n                commonMetadata_json\n            FROM \""
- "\"\n        )\n        WHERE datetime(eventTimestamp, \"unixepoch\") >= datetime(\"now\", \"-"
- "\"\n    WHERE evaluationUuid IN results\n    UNION SELECT\n        *,\n        \""
- "\" as stream,\n        json_extract(commonMetadata_json, \"$.evaluationUuid\") evaluationUuid,\n        generatedContent_json,\n        originalContent_json,\n        commonMetadata_json\n    FROM \""
- "%s - No error occurred"
- ".string._0\"\n        ) id\n    FROM \""
- "No duplicate row for spotlightID existed"
- "SELECT\n    count(*) count\nFROM (\n    SELECT\n        json_extract(\n            json_extract(\n                originalContent_json,\n                \"$.text\"\n            ),\n            \"$.dictionary._0."
- "SELECT\n    evaluationUuid\nFROM (\n    SELECT\n        featureDomain,\n        eventTimestamp,\n        evaluationUuid,\n        commonMetadata_json,\n        ROW_NUMBER()\n    OVER (\n        PARTITION BY json_extract(commonMetadata_json, \"$.featureDomain\")\n        ORDER BY eventTimestamp "
- "WITH results AS (\n    SELECT\n        evaluationUuid\n    FROM (\n        SELECT\n            featureDomain,\n            eventTimestamp,\n            evaluationUuid,\n            commonMetadata_json,\n            ROW_NUMBER()\n        OVER (\n            PARTITION BY json_extract(commonMetadata_json, \"$.featureDomain\")\n            ORDER BY eventTimestamp "
- "duplicate row count existed, but count didn't exist"
- "fetchDonationIDs(count:fromLatest:excludingEvaluationIDs:database:)"
- "fetchDonations(count:fromLatest:excludingEvaluationIDs:database:)"
```
