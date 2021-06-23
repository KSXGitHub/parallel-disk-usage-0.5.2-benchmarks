| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=len tmp.sample` | 127.4 ± 3.6 | 123.0 | 137.3 | 1.00 |
| `dust --apparent-size tmp.sample` | 165.5 ± 8.4 | 155.6 | 187.0 | 1.30 ± 0.08 |
| `dutree tmp.sample` | 3859.0 ± 4.6 | 3851.9 | 3863.8 | 30.30 ± 0.86 |
| `dua --apparent-size tmp.sample` | 258.2 ± 13.8 | 243.1 | 286.9 | 2.03 ± 0.12 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 210.1 ± 2.2 | 208.1 | 215.3 | 1.65 ± 0.05 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 310.6 ± 12.9 | 291.4 | 329.7 | 2.44 ± 0.12 |
| `du --apparent-size tmp.sample` | 194.4 ± 0.5 | 193.6 | 195.3 | 1.53 ± 0.04 |
