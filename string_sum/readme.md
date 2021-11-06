 Ran the example from [here](https://github.com/PyO3/pyo3):
 ```
 apt-get install python3-venv
 python3  -m venv .env
 source .env/bin/activate
 pip install maturin
 cd string_sum/
 maturin develop
 (.env) root@rust:/var/tmp/rust_from_python/string_sum# python3 
Python 3.9.2 (default, Feb 28 2021, 17:03:44)
[GCC 10.2.1 20210110] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import string_sum
>>> string_sum.sum_as_string(5, 20)
'25'
```