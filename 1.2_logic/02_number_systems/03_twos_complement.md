## Two's Complement
**Find the two's complement of the binary number:**
   - `101010` → `010110`
   - `110011` → `001101`
   - `1001` → `0111`

### Working

Two's complement = invert every bit (one's complement), then add 1.

**101010 (6 bits)**
- One's complement: `010101`
- Add 1: `010101 + 1 = 010110`

**110011 (6 bits)**
- One's complement: `001100`
- Add 1: `001100 + 1 = 001101`

**1001 (4 bits)**
- One's complement: `0110`
- Add 1: `0110 + 1 = 0111`

### Check (interpret as signed values)
- `101010` = −22, two's complement `010110` = +22 ✓
- `110011` = −13, two's complement `001101` = +13 ✓
- `1001` = −7, two's complement `0111` = +7 ✓

