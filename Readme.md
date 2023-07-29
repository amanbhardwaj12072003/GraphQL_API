# BigInteger Implementation in Java

## Overview
This is a custom implementation of a BigInteger library in Java, named **BigNumber**. The library provides support for performing arithmetic operations on large integers with arbitrary precision. It is capable of handling numbers that exceed the range of primitive data types in Java.

## Features
- Addition, subtraction, multiplication, and division of arbitrarily large integers
- Modulo and power operations
- Comparison methods (greater than, less than, equal to)
- Prime factorization and primality testing
- Random prime number generation
- Clean input method to handle leading zeros and spaces in input numbers

## Usage
### Creating a BigNumber
You can create a BigNumber instance using one of the following constructors:

1. From a **String** representation of a number:
```
BigNumber num1 = new BigNumber("12345678901234567890");
```
2. From a **long** value:
```
BigNumber num2 = new BigNumber(98765432109876543210L);
```
