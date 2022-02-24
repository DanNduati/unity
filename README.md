<h1 align="center"><b>UNITY</b></h1>

Unit Testing FOR C (ESPECIALLY EMBEDDED SOFTWARE)
## <b>Description</b>
Simple unit tests on native c application

## Prerequisites
- [GCC](https://gcc.gnu.org/)
- [Unity](https://github.com/ThrowTheSwitch/Unity/)

## Build Executable
Compile source file, a test file, and Unity and link them together

```bash
gcc TestDumbExample.c DumbExample.c ./Unity/src/unity.c -o TestDumbExample
./TestDumbExample
```

## Run executable 
```bash
./TestDumbExample
```
## Output
```
TestDumbExample.c:32:test_AverageThreeBytes_should_AverageMidRangeValues:PASS
TestDumbExample.c:33:test_AverageThreeBytes_should_AverageHighValues:PASS

-----------------------
2 Tests 0 Failures 0 Ignored 
OK
```