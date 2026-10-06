## HybridDatabase

> `/System/Library/PrivateFrameworks/HybridDatabase.framework/HybridDatabase`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f39f8` | `0x7f30f8` | **`-0x900`** |
| `__DATA_CONST.__const` | `0x4db28` | `0x4d6a8` | **`-0x480`** |
| `__TEXT.__gcc_except_tab` | `0x53d38` | `0x53fd8` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x8b96c` | `0x8b73b` | **`-0x231`** |
| `__TEXT.__const` | `0xe8780` | `0xe86c0` | **`-0xc0`** |
| `__AUTH_CONST.__const` | `0x39670` | `0x396b8` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0xb64` | `0xb70` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x548` | `0x550` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-60.3.0.0.0
+60.3.1.0.0

-  Functions: 22300
+  Functions: 22305

-  CStrings:  8622
+  CStrings:  8620
CStrings:
+ "60.3.1"
+ "Cannot find rel entry for group {} from table ID {} to table ID {}."
+ "CorruptInvalidRelTableInfos"
+ "Query timed out."
+ "TimeoutException"
+ "const RelTableCatalogInfo *kuzu::catalog::RelGroupCatalogEntry::getRelEntryInfo(table_id_t, table_id_t, bool) const"
+ "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:841:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:848:13)>]"
+ "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:864:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:868:13)>]"
+ "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:933:9), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:937:9)>]"
+ "static auto kuzu::common::TypeUtils::visit(const LogicalType &, Fs...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/vector/src/index/hnsw_index.cpp:787:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/vector/src/index/hnsw_index.cpp:789:13)>]"
+ "void kuzu::main::ClientContext::throwIfInterruptedOrTimedOut() const"
- "60.3"
- "auto kuzu::function::tableFunc(const TableFuncInput &, TableFuncOutput &)::(anonymous class)::operator()(auto) const [epos:auto = unsigned long long]"
- "auto kuzu::function::tableFunc(const TableFuncInput &, TableFuncOutput &)::(anonymous class)::operator()(auto) const [epos:auto = unsigned long]"
- "bool kuzu::processor::PhysicalOperator::getNextTuple(ExecutionContext *)"
- "offset_t kuzu::fts_extension::tableFunc(const TableFuncMorsel &, const TableFuncInput &, DataChunk &)"
- "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:844:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:851:13)>]"
- "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:867:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:871:13)>]"
- "static auto kuzu::common::TypeUtils::visit(PhysicalTypeID, Fs &&...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:936:9), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/src/storage/index/hash_index.cpp:940:9)>]"
- "static auto kuzu::common::TypeUtils::visit(const LogicalType &, Fs...) [Fs = <(lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/vector/src/index/hnsw_index.cpp:790:13), (lambda at /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/HybridDatabase/libhybriddatabase/extension/vector/src/index/hnsw_index.cpp:792:13)>]"
- "void kuzu::fts_extension::FTSIndex::integrityCheckOnAppearsInTable(main::ClientContext *, transaction::Transaction *, graph::OnDiskGraph &) const"
- "void kuzu::function::PathsOutputWriter::dfsFast(ParentList *, FactorizedTable &, LimitCounter *)"
- "void kuzu::function::PathsOutputWriter::dfsSlow(ParentList *, FactorizedTable &, LimitCounter *)"
- "void kuzu::vector_extension::HNSWSearchState::checkInterrupt() const"
```
