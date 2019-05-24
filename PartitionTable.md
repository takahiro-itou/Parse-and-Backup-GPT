# パーティションテーブル

現在のパーティション

* Disk 1 (/dev/sda)

|No.|Type|TypeID|FS|Start LBA|End LBA|Sectors|Size|Label|
|--:|----|-----|:--|--------:|------:|------:|---:|:----|
| 1|GPT Primary||OTHER|            34|       262,177|       262,144|       128 MiB            |GPT 予約 |
| 2|GPT Primary||EXT 4|       264,192|     8,652,799|     8,388,608|     4,096 MiB (    4 GiB)|LINUXBOOT|
| 3|GPT Primary||NTFS |     9,062,400|   260,720,639|   251,658,240|   122,880 MiB (  120 GiB)|WINDOWS  |
| 4|GPT Primary||NTFS |   260,720,640|   428,492,799|   167,772,160|    81,920 MiB (   80 GiB)|PROGRAMS |
| 5|GPT Primary||NTFS |   428,492,800|   680,151,039|   251,658,240|   122,880 MiB (  120 GiB)|NOINST   |
| 6|GPT Primary||EXT 4|   680,151,040|   805,980,159|   125,829,120|    61,440 MiB (   60 GiB)|LINUXROOT|
| 7|GPT Primary||FAT32|   805,980,160|   810,176,511|     4,196,352|     2,049 MiB (    2 GiB)|RECOVERY |
| 8|GPT Primary||NTFS |   810,176,512|   811,198,463|     1,021,952|       499 MiB            |回復     |
| 9|GPT Primary||FAT32|   811,198,464|   811,403,263|       204,800|       100 MiB            |EFI      |

* Disk 2 (/dev/sdb)

|No.|Type|TypeID|FS|Start LBA|End LBA|Sectors|Size|Label|
|--:|----|-----|:--|--------:|------:|------:|---:|:----|
| 1|GPT Primary||OTHER|            34|       262,177|       262,144|       128 MiB            |GPT 予約    |
| 2|GPT Primary||EXT 3|       264,192|     4,458,495|     4,194,304|     2,048 MiB (    2 GiB)|BKUPLNXBOOT |
| 3|GPT Primary||     |     4,458,496|     8,857,599|     4,399,104|     2,148 MiB (  2.1 GiB)|            |
| 4|GPT Primary||NTFS |     8,857,600|    75,966,463|    67,108,864|    32,768 MiB (   32 GiB)|USERS       |
| 5|GPT Primary||NTFS |    75,966,464|   243,738,623|   167,772,160|    81,920 MiB (   80 GiB)|RAMBK       |
| 6|GPT Primary||NTFS |   243,738,624|   369,567,743|   125,829,120|    61,440 MiB (   60 GiB)|PAGEFILE    |
| 7|GPT Primary||FAT32|   369,567,744|   906,438,655|   536,870,912|   262,144 MiB (  256 GiB)|DATA1       |
| 8|GPT Primary||FAT32|   906,438,656| 4,052,166,655| 3,145,728,000| 1,536,000 MiB (1,500 GiB)|DATA2       |
| 9|GPT Primary||NTFS | 4,052,166,656| 4,589,037,567|   536,870,912|   262,144 MiB (  256 GiB)|MOZILLA     |
|10|GPT Primary||NTFS | 4,589,037,568| 5,637,613,567| 1,048,576,000|   512,000 MiB (  500 GiB)|INSTALLER   |
|11|GPT Primary||EXT 4| 5,637,613,568| 6,174,484,479|   536,870,912|   262,144 MiB (  256 GiB)|LINUXHOME   |
|12|GPT Primary||SWAP | 6,174,484,480| 6,176,581,631|     2,097,152|     1,024 MiB (    1 GiB)|LINUXSWAP   |
|13|GPT Primary||EXT 4| 6,176,581,632| 6,184,970,239|     8,388,608|     4,096 MiB (    4 GiB)|LINUXTEMP   |
|14|GPT Primary||FAT32| 6,184,970,240| 6,185,175,039|       204,800|       100 MiB            |BACKUPEFI   |
|15|GPT Primary||NTFS | 6,185,175,040| 6,436,833,279|   251,658,240|   122,880 MiB (  120 GiB)|BKUPNOINST  |
|16|GPT Primary||EXT 3| 6,436,833,280| 6,562,662,399|   125,829,120|    61,440 MiB (   60 GiB)|BKUPLNXROOT |
|17|GPT Primary||NTFS | 6,562,662,400| 6,814,320,639|   251,658,240|   122,880 MiB (  120 GiB)|BKUPWINDOWS |
|18|GPT Primary||NTFS | 7,268,775,936| 7,478,489,087|   209,713,152|   102,399 MiB (  100 GiB)|OLDMOZILLA  |
|19|GPT Primary||NTFS | 7,478,489,088| 7,604,316,032|   125,826,945|    61,439 MiB (   60 GiB)|OLDRAMBK    |
|20|GPT Primary||EXT 4| 7,604,318,208| 7,814,033,407|   209,715,200|   102,400 MiB (  100 GiB)|OLDLINUXHOME|


