# Next smaller number with the same digits

## Instructions
Write a function that takes a positive integer and returns the next smaller positive integer containing the same digits.

For example:
```
nextSmaller(21) == 12
nextSmaller(531) == 513
nextSmaller(2071) == 2017
```

Return -1 when there is no smaller number that contains the same digits. Also return -1 when the next smaller number with the same digits would require the leading digit to be zero.
```
nextSmaller(9) == -1
nextSmaller(111) == -1
nextSmaller(135) == -1
nextSmaller(1027) == -1 // 0721 is out since we don't write numbers with leading zeros
```

Create a unit test project to test all the following scenarios:
```
nextSmaller(21) 	==> 12
nextSmaller(907) 	==> 790
nextSmaller(531) 	==> 513
nextSmaller(1027) 	==> -1
nextSmaller(441) 	==> 414
nextSmaller(123456798) 	==> 123456789
```

New content
