| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=blksize tmp.sample` | 130.6 ± 3.8 | 125.7 | 138.1 | 1.00 |
| `dust tmp.sample` | 183.0 ± 3.4 | 178.1 | 191.1 | 1.40 ± 0.05 |
| `dutree --usage tmp.sample` | 3829.2 ± 15.7 | 3811.7 | 3859.4 | 29.33 ± 0.85 |
| `dua tmp.sample` | 275.9 ± 17.5 | 251.0 | 307.5 | 2.11 ± 0.15 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 212.1 ± 5.4 | 209.0 | 225.2 | 1.62 ± 0.06 |
| `gdu --non-interactive --no-progress tmp.sample` | 294.0 ± 4.2 | 286.1 | 299.7 | 2.25 ± 0.07 |
| `du tmp.sample` | 196.7 ± 2.7 | 194.7 | 204.6 | 1.51 ± 0.05 |
