# profile_memory
Measures the RSS and VMS memory used in a Python script

---
from profile_memory import profile

@profile
def code_to_run():
    from sklearn.datasets import load_iris
    
res = code_to_run()
---

Result:
Profiling:        <code_to_run>  RSS:   45.1MB | VMS:  66.16MB | SHR  16.57MB | time: 345.73ms
