## Check-if-all-items-in-the-following-tuple-are-the-same
## Sample code to check the details
```sh
def check(sampleTuple):
    return all(i == sampleTuple[0] for i in sampleTuple)

tuple1 = (45, 45, 45, 45)
print(check(tuple1))
```
## Expected Output
true
