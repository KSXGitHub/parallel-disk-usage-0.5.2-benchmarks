| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 207.6 ± 1.0 | 206.5 | 210.3 | 1.00 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 211.0 ± 3.7 | 208.7 | 222.6 | 1.02 ± 0.02 |
| `gdu --show-apparent-size --non-interactive tmp.sample` | 318.4 ± 10.6 | 302.3 | 340.9 | 1.53 ± 0.05 |
