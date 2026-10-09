
## Fixed Point Representation
**Represent the decimal number in fixed-point binary:**
   - `12.75` with 4 bits for the integer part and 4 bits for the fractional part → `1100.1100`
   - `5.125` with 3 bits for the integer part and 5 bits for the fractional part → `101.00100`
   - `7.5` with 4 bits for the integer part and 4 bits for the fractional part → `0111.1000`

### Working

Fractional weights (left to right): 2⁻¹ = 0.5, 2⁻² = 0.25, 2⁻³ = 0.125, 2⁻⁴ = 0.0625, 2⁻⁵ = 0.03125.

**12.75 (4.4)**
- Integer 12 = `1100`
- Fraction 0.75 = 0.5 + 0.25 = `.1100`
- Result: `1100.1100`

**5.125 (3.5)**
- Integer 5 = `101`
- Fraction 0.125 = 2⁻³ = `.00100` (5 bits)
- Result: `101.00100`

**7.5 (4.4)**
- Integer 7 = `0111`
- Fraction 0.5 = 2⁻¹ = `.1000`
- Result: `0111.1000`
