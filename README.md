### manipulate_file_size

```
dd if=/dev/zero of=tester.csv  bs=1M  count=2400
```

### add milion row
```
for i in {1..200000}; do cat number.csv >> validnumber.csv; done
```

