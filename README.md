# simple-wait
Simple wait

```python
from datetime import datetime
from simple_wait import wait

print("Start wait")
wait(seconds=5)
print("Finish wait")

while True:
    print()
    print("Current datetime:", datetime.now())
    print()
    wait(minutes=1, seconds=30)
```
