| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 725.0 ± 20.4 | 713.2 | 782.6 | 3.60 ± 0.20 |
| `dutree tmp.sample` | 3847.4 ± 19.6 | 3809.9 | 3879.4 | 19.10 ± 0.91 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 208.0 ± 1.3 | 204.7 | 209.3 | 1.03 ± 0.05 |
| `du --apparent-size tmp.sample` | 201.4 ± 9.5 | 193.9 | 224.0 | 1.00 |
