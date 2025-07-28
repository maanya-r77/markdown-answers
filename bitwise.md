## Bitwise Operators

Used to perform bit-level operations.

| Operator | Meaning         | Example       |
|----------|------------------|---------------|
| `&`      | AND              | `5 & 3` → 1    |
| `|`      | OR               | `5 | 3` → 7    |
| `^`      | XOR              | `5 ^ 3` → 6    |
| `~`      | NOT              | `~5` → -6     |
| `<<`     | Left Shift       | `5 << 1` → 10 |
| `>>`     | Right Shift      | `5 >> 1` → 2  |

### Example:
```java
int a = 5;  // 0101
int b = 3;  // 0011

System.out.println(a & b);  // 1
System.out.println(a | b);  // 7
System.out.println(a ^ b);  // 6
System.out.println(~a);     // -6
System.out.println(a << 1); // 10
System.out.println(a >> 1); // 2
