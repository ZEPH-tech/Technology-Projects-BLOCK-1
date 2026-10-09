
## Limits of Binary Representation
**Determine the limits of binary representation:**
   - Largest positive number with 8 bits in unsigned binary: `255` (`11111111`)
   - Largest positive number with 8 bits in signed binary (two's complement): `127` (`01111111`)
   - Smallest negative number with 8 bits in signed binary (two's complement): `-128` (`10000000`)

### Working

- **Unsigned 8-bit:** all 8 bits store magnitude → 2⁸ − 1 = 255; range 0 to 255.
- **Signed 8-bit (two's complement):** the most significant bit is the sign bit, so the positive range uses 7 magnitude bits → 2⁷ − 1 = 127.
- **Smallest negative:** the sign bit set with all other bits 0 represents −2⁷ = −128 (there is no positive counterpart for this value).

Full signed range: **−128 to +127**.
