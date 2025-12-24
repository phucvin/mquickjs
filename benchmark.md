# MicroQuickJS Benchmark Report

Results from running `make microbench`.

| Test | N | Time (ns) |
|---|---|---|
| empty_loop | 5000000 | 23.80 |
| date_now | 2000000 | 95.00 |
| prop_read | 2000000 | 23.75 |
| prop_write | 2000000 | 16.25 |
| prop_update | 500000 | 45.00 |
| prop_create | 50000 | 105.00 |
| prop_delete | 1000 | 150.00 |
| array_read | 500000 | 22.00 |
| array_write | 1000000 | 15.00 |
| array_update | 200000 | 32.00 |
| array_prop_create | 2000 | 62.00 |
| array_length_read | 1000000 | 35.00 |
| array_length_decr | 1000 | 129.00 |
| array_push | 2000 | 117.00 |
| array_pop | 5000 | 78.40 |
| typed_array_read | 500000 | 40.00 |
| typed_array_write | 500000 | 38.00 |
| closure_read | 2000000 | 23.50 |
| closure_write | 5000000 | 11.50 |
| global_read | 2000000 | 23.50 |
| global_write_strict | 5000000 | 11.50 |
| func_call | 500000 | 50.00 |
| closure_var | 500000 | 50.00 |
| int_arith | 5000 | 39.00 |
| float_arith | 2000 | 55.00 |
| array_for | 50000 | 42.00 |
| array_for_in | 10000 | 110.00 |
| array_for_of | 50000 | 26.00 |
| math_min | 2000 | 80.00 |
| regexp_ascii | 500 | 340.00 |
| regexp_utf16 | 500 | 360.00 |
| regexp_replace | 50 | 1900.00 |
| string_length | 2000000 | 22.50 |
| string_build1 | 500 | 950.00 |
| string_build2 | 500 | 800.00 |
| sort_bench | 1 | 10.70 |
| int_to_string | 1000000 | 170.00 |
| float_to_string | 200000 | 600.00 |
| string_to_int | 1000000 | 160.00 |
| string_to_float | 500000 | 200.00 |
| TOTAL |  | 7062.40 |
