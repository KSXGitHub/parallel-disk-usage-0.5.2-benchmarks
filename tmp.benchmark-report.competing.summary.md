| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 135.1 ± 7.6 | 128.3 | 152.9 | 1.00 |
| `dutree --summary tmp.sample` | 334.1 ± 12.5 | 316.4 | 350.7 | 2.47 ± 0.17 |
| `dua --apparent-size tmp.sample` | 254.7 ± 16.0 | 240.0 | 292.8 | 1.88 ± 0.16 |
| `ncdu -o /dev/null -0 tmp.sample` | 213.8 ± 11.9 | 208.5 | 243.5 | 1.58 ± 0.13 |
| `du --apparent-size --total tmp.sample` | 194.5 ± 0.5 | 193.9 | 195.7 | 1.44 ± 0.08 |
