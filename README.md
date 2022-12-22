### Manipulate_file_size

```
dd if=/dev/zero of=tester.csv  bs=1M  count=2400
```

### Add milion row
```
for i in {1..200000}; do cat number.csv >> validnumber.csv; done
```

### Add content to first header
```
x=`echo "product_id"; cat bignumber.csv`
echo "$x" > bignumber.csv
```
