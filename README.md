# Performance testing localhost

```bash
docker run -p 3001:3001 oleksandrgolubishko/qa_pro_rest_app
```

**The HW21.1 repository contains test folders with the following settings:**

- Thread users 100, Ramp up 1, Loop count 1 --> **Thread100.1**
- Thread users 1000, Ramp up 1, Loop count 2 --> **Thread1000.2**
- Thread users 5000, Ramp up 1, Loop count 4 --> **Thread5000.4**

and

- Thread users 1000, Ramp up 2, Loop count Infinity, Duration 30 sec --> **Thread1000.2.Inf+Duration30**
- Thread users 5000, Ramp up 3, Loop count Infinity, Duration 60 sec --> **Thread5000.3.Inf+Duration60**
- Thread users 10000, Ramp up 5, Loop count Infinity, Duration 180 sec --> **Thread10000.2.Inf+Duration180**

 **Also contains:**
 - Test script files in a .jmx file
 - Test results in the form of a CSV file
 - Generated HTML reports
