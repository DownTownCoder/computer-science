### 1. Overview

We start by deconstructing a number to form a general expression for any given digit in a number.

Create our own Java method to convert a hexadecimal string to an integer.

Java's base conversion methods. Ensure we don't violate the boundaries of the numeric types.

### n. Deconstructing a Number to Locate its Base

To reveal the base of the decimal number 2473, write it down thus:

2 * 10^3 + 4 * 10^2 + 7 * 10^1 + 3 * 10^0

2 * 1000 + 4 * 100 + 7 * 10 + 3 * 1

2000 + 400 + 70 + 3

2473

We knew the base was 10, but we didn't know where it was. We can now write a general expression for any particular term in any number of any base:

d * b^n, (n = 0,1,2,...) (reversed)

Each digit, d, of a base 10 number must be between 0 and 9 inclusive:

0 <= d <= 9

In fact, for any base, we have:

0 <= d <= b-1

### n. A Custom Method to Convert a Hexadecimal String to an Integer



### n. Java's Base Conversion Methods



### n. Conclusion



### n. References

https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#valueOf-java.lang.String-int-

https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#parseInt-java.lang.String-int-

https://docs.oracle.com/javase/8/docs/api/java/lang/Integer.html#decode-java.lang.String-

https://stackoverflow.com/questions/11377944/parsing-a-hexadecimal-string-to-an-integer-throws-a-numberformatexception

https://stackoverflow.com/questions/11194513/convert-hex-string-to-int