summary:
better: 49, geomean: 1.147
worse: 5, geomean: 1.033
total diff: 54

| Slower                                                                           | diff/base | Base Median (ns) | Diff Median (ns) | Modality|
| -------------------------------------------------------------------------------- | ---------:| ----------------:| ----------------:| -------- |
| SerializationBaselineTests.SerializationBenchmarks.WriteJson(dataSize: 5000, isM |      1.05 |       8898300.00 |       9318600.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteJson(dataSize: 5000, isM |      1.04 |       8811100.00 |       9146850.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteJson(dataSize: 10000, is |      1.03 |      17782200.00 |      18353600.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteJson(dataSize: 10000, is |      1.03 |      17808000.00 |      18339200.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteJson(dataSize: 1000, isM |      1.02 |       1920100.00 |       1958800.00 | several?|

| Faster                                                                           | base/diff | Base Median (ns) | Diff Median (ns) | Modality|
| -------------------------------------------------------------------------------- | ---------:| ----------------:| ----------------:| --------:|
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.24 |      25225200.00 |      20343300.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 1000 |      1.24 |      23862600.00 |      19262100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 5000 |      1.23 |     118341100.00 |      95905100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 1000 |      1.23 |      25351900.00 |      20552100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.23 |      23740000.00 |      19270400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 1000 |      1.23 |     237077400.00 |     192992900.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 1000 |      1.23 |     252622700.00 |     205743500.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.23 |     123499700.00 |     100619500.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.23 |     118660300.00 |      96805100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.23 |     260084050.00 |     212241800.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.22 |     237068500.00 |     193569850.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.22 |     126436600.00 |     103321700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.22 |     243478000.00 |     199052750.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.22 |     260673500.00 |     213368700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.22 |     123509100.00 |     101132600.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSync(dataSize: 5000 |      1.22 |     125474200.00 |     102864000.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.22 |     129935600.00 |     106530300.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.22 |      24971900.00 |      20498700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.22 |     251591850.00 |     206530700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.22 |     243142250.00 |     199607300.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.22 |      26332700.00 |      21657100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncFile(dataSize:  |      1.21 |     129795700.00 |     107022400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPool(dataS |      1.21 |      25103000.00 |      20721100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataSyncArrayPoolFile(d |      1.20 |      26290200.00 |      21824850.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 1000 |      1.09 |      81137800.00 |      74461350.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 1000, is |      1.09 |      81192600.00 |      74658700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.09 |      81098100.00 |      74643500.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.09 |      79381500.00 |      73063700.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 1000, is |      1.09 |      79374950.00 |      73058300.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 5000 |      1.08 |     406913950.00 |     375129800.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.08 |      81239100.00 |      74901000.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 1000 |      1.08 |     813155600.00 |     750092800.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 1000 |      1.08 |     792749100.00 |     732295100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 5000 |      1.08 |     396905100.00 |     366955100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 10000, i |      1.08 |     809794600.00 |     748916450.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.08 |     792409500.00 |     733425600.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.08 |     808588600.00 |     748517400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 10000, i |      1.08 |     790945750.00 |     732221800.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.08 |     396616900.00 |     367378500.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.08 |     810447100.00 |     751194400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 5000, is |      1.08 |     394974000.00 |     366193000.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.08 |     394269300.00 |     365613000.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.08 |     405924650.00 |     376516100.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.08 |     789774950.00 |     732646500.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPool(dataSize: |      1.07 |     404467400.00 |     376915400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteOData(dataSize: 5000, is |      1.07 |     404288000.00 |     376802400.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataFile(dataSize: 1000 |      1.07 |      82057300.00 |      76606000.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteODataArrayPoolFile(dataS |      1.07 |      82417800.00 |      77090850.00 |         |
| SerializationBaselineTests.SerializationBenchmarks.WriteJsonFile(dataSize: 1000, |      1.02 |       2372650.00 |       2330900.00 |         |

No file given
