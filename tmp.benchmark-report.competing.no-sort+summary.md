| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 122.3 ± 0.9 | 120.3 | 123.9 | 1.00 |
| `dua --apparent-size tmp.sample` | 239.1 ± 7.2 | 230.3 | 252.2 | 1.96 ± 0.06 |
| `ncdu -o /dev/null -0 tmp.sample` | 218.5 ± 9.7 | 207.1 | 239.3 | 1.79 ± 0.08 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 314.5 ± 9.9 | 301.9 | 332.4 | 2.57 ± 0.08 |
| `du --apparent-size --total tmp.sample` | 199.9 ± 10.7 | 193.6 | 227.2 | 1.64 ± 0.09 |
