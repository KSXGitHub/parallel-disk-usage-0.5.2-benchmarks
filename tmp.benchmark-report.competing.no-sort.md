| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 131.8 ± 4.1 | 125.2 | 142.0 | 1.00 |
| `du --apparent-size tmp.sample` | 194.4 ± 0.5 | 193.6 | 195.1 | 1.48 ± 0.05 |
| `dua --apparent-size tmp.sample` | 249.9 ± 7.9 | 234.7 | 261.9 | 1.90 ± 0.08 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 208.4 ± 1.2 | 205.5 | 209.5 | 1.58 ± 0.05 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 304.4 ± 15.6 | 282.2 | 324.1 | 2.31 ± 0.14 |
