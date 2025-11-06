# C Language Math Functions Reference

Complete enumeration of all standard math functions available in C (`math.h` library).

## 1. Trigonometric Functions

### Basic Trigonometric
- **`sin(double x)`** - Sine of angle x (radians)
- **`cos(double x)`** - Cosine of angle x (radians)  
- **`tan(double x)`** - Tangent of angle x (radians)
- **`asin(double x)`** - Arc sine (inverse sine)
- **`acos(double x)`** - Arc cosine (inverse cosine)
- **`atan(double x)`** - Arc tangent (inverse tangent)
- **`atan2(double y, double x)`** - Arc tangent of y/x

### Trigonometric (float versions)
- **`sinf(float x)`** - Sine (float)
- **`cosf(float x)`** - Cosine (float)
- **`tanf(float x)`** - Tangent (float)
- **`asinf(float x)`** - Arc sine (float)
- **`acosf(float x)`** - Arc cosine (float)
- **`atanf(float x)`** - Arc tangent (float)
- **`atan2f(float y, float x)`** - Arc tangent (float)

### Trigonometric (long double versions)
- **`sinl(long double x)`** - Sine (long double)
- **`cosl(long double x)`** - Cosine (long double)
- **`tanl(long double x)`** - Tangent (long double)
- **`asinl(long double x)`** - Arc sine (long double)
- **`acosl(long double x)`** - Arc cosine (long double)
- **`atanl(long double x)`** - Arc tangent (long double)
- **`atan2l(long double y, long double x)`** - Arc tangent (long double)

## 2. Hyperbolic Functions

### Basic Hyperbolic
- **`sinh(double x)`** - Hyperbolic sine
- **`cosh(double x)`** - Hyperbolic cosine
- **`tanh(double x)`** - Hyperbolic tangent
- **`asinh(double x)`** - Inverse hyperbolic sine
- **`acosh(double x)`** - Inverse hyperbolic cosine
- **`atanh(double x)`** - Inverse hyperbolic tangent

### Hyperbolic (float versions)
- **`sinhf(float x)`** - Hyperbolic sine (float)
- **`coshf(float x)`** - Hyperbolic cosine (float)
- **`tanhf(float x)`** - Hyperbolic tangent (float)
- **`asinhf(float x)`** - Inverse hyperbolic sine (float)
- **`acoshf(float x)`** - Inverse hyperbolic cosine (float)
- **`atanhf(float x)`** - Inverse hyperbolic tangent (float)

### Hyperbolic (long double versions)
- **`sinhl(long double x)`** - Hyperbolic sine (long double)
- **`coshl(long double x)`** - Hyperbolic cosine (long double)
- **`tanhl(long double x)`** - Hyperbolic tangent (long double)
- **`asinhl(long double x)`** - Inverse hyperbolic sine (long double)
- **`acoshl(long double x)`** - Inverse hyperbolic cosine (long double)
- **`atanhl(long double x)`** - Inverse hyperbolic tangent (long double)

## 3. Exponential and Logarithmic Functions

### Exponential Functions
- **`exp(double x)`** - Exponential function e^x
- **`exp2(double x)`** - 2^x
- **`exp10(double x)`** - 10^x (may not be available on all platforms)
- **`expm1(double x)`** - e^x - 1 (more accurate for small x)

### Exponential (float/long double versions)
- **`expf(float x)`** - e^x (float)
- **`exp2f(float x)`** - 2^x (float)
- **`expm1f(float x)`** - e^x - 1 (float)
- **`expl(long double x)`** - e^x (long double)
- **`exp2l(long double x)`** - 2^x (long double)
- **`expm1l(long double x)`** - e^x - 1 (long double)

### Logarithmic Functions
- **`log(double x)`** - Natural logarithm (base e)
- **`log2(double x)`** - Base 2 logarithm
- **`log10(double x)`** - Base 10 logarithm
- **`log1p(double x)`** - ln(1 + x) (more accurate for small x)
- **`logb(double x)`** - Extracts exponent of floating-point number
- **`ilogb(double x)`** - Integer exponent extraction

### Logarithmic (float/long double versions)
- **`logf(float x)`** - ln(x) (float)
- **`log2f(float x)`** - log2(x) (float)
- **`log10f(float x)`** - log10(x) (float)
- **`log1pf(float x)`** - ln(1 + x) (float)
- **`logbl(long double x)`** - Extracts exponent (long double)
- **`logl(long double x)`** - ln(x) (long double)
- **`log2l(long double x)`** - log2(x) (long double)
- **`log10l(long double x)`** - log10(x) (long double)

## 4. Power and Root Functions

### Power Functions
- **`pow(double x, double y)`** - x^y (x to the power of y)
- **`powi(double x, int n)`** - x^n (integer power, may not be standard)
- **`cpow(double complex x, double complex y)`** - Complex power (C99)

### Power (float/long double versions)
- **`powf(float x, float y)`** - x^y (float)
- **`powl(long double x, long double y)`** - x^y (long double)
- **`cpowf(float complex x, float complex y)`** - Complex power (float)
- **`cpowl(long double complex x, long double complex y)`** - Complex power (long double)

### Root Functions
- **`sqrt(double x)`** - Square root of x
- **`cbrt(double x)`** - Cube root of x
- **`hypot(double x, double y)`** - sqrt(x² + y²) (hypotenuse)
- **`sqrtf(float x)`** - Square root (float)
- **`cbrtf(float x)`** - Cube root (float)
- **`hypotf(float x, float y)`** - Hypotenuse (float)
- **`sqrtl(long double x)`** - Square root (long double)
- **`cbrtl(long double x)`** - Cube root (long double)
- **`hypotl(long double x, long double y)`** - Hypotenuse (long double)

## 5. Rounding and Remainder Functions

### Rounding Functions
- **`ceil(double x)`** - Round up to nearest integer
- **`floor(double x)`** - Round down to nearest integer
- **`round(double x)`** - Round to nearest integer (half away from zero)
- **`trunc(double x)`** - Truncate fractional part
- **`rint(double x)`** - Round to nearest integer (using current rounding mode)
- **`nearbyint(double x)`** - Round to nearest integer (no exception)

### Rounding (float/long double versions)
- **`ceilf(float x)`** - Round up (float)
- **`floorf(float x)`** - Round down (float)
- **`roundf(float x)`** - Round (float)
- **`truncf(float x)`** - Truncate (float)
- **`rintf(float x)`** - Round (float)
- **`nearbyintf(float x)`** - Round (float)
- **`ceill(long double x)`** - Round up (long double)
- **`floorl(long double x)`** - Round down (long double)
- **`roundl(long double x)`** - Round (long double)
- **`truncl(long double x)`** - Truncate (long double)
- **`rintl(long double x)`** - Round (long double)
- **`nearbyintl(long double x)`** - Round (long double)

### Remainder Functions
- **`fmod(double x, double y)`** - Floating-point remainder of x/y
- **`remainder(double x, double y)`** - IEEE remainder of x/y
- **`remquo(double x, double y, int *quo)`** - Remainder and quotient

### Remainder (float/long double versions)
- **`fmodf(float x, float y)`** - Remainder (float)
- **`remainderf(float x, float y)`** - IEEE remainder (float)
- **`remquof(float x, float y, int *quo)`** - Remainder and quotient (float)
- **`fmodl(long double x, long double y)`** - Remainder (long double)
- **`remainderl(long double x, long double y)`** - IEEE remainder (long double)
- **`remquol(long double x, long double y, int *quo)`** - Remainder and quotient (long double)

## 6. Floating-Point Manipulation Functions

### Scaling and Extraction
- **`frexp(double x, int *exponent)`** - Break x into normalized fraction and power of 2
- **`ldexp(double x, int exponent)`** - Multiply x by 2 raised to exponent
- **`modf(double x, double *integer_part)`** - Split x into integer and fractional parts
- **`scalbn(double x, int n)`** - Multiply x by FLT_RADIX^n
- **`scalbln(double x, long int n)`** - Multiply x by FLT_RADIX^n (long)

### Scaling (float/long double versions)
- **`frexpf(float x, int *exponent)`** - Break into fraction and power (float)
- **`ldexpf(float x, int exponent)`** - Multiply by 2^n (float)
- **`modff(float x, float *integer_part)`** - Split into parts (float)
- **`scalbnf(float x, int n)`** - Scale by FLT_RADIX^n (float)
- **`scalblnf(float x, long int n)`** - Scale by FLT_RADIX^n (float, long)
- **`frexpl(long double x, int *exponent)`** - Break into fraction and power (long double)
- **`ldexpl(long double x, int exponent)`** - Multiply by 2^n (long double)
- **`modfl(long double x, long double *integer_part)`** - Split into parts (long double)
- **`scalbnl(long double x, int n)`** - Scale by FLT_RADIX^n (long double)
- **`scalblnl(long double x, long int n)`** - Scale by FLT_RADIX^n (long double, long)

## 7. Comparison Functions

### Classification Functions
- **`isfinite(double x)`** - Check if x is finite
- **`isinf(double x)`** - Check if x is infinite
- **`isnan(double x)`** - Check if x is NaN (Not a Number)
- **`isnormal(double x)`** - Check if x is normalized
- **`signbit(double x)`** - Check sign of x

### Classification (float versions)
- **`isfinitef(float x)`** - Finite check (float)
- **`isinff(float x)`** - Infinite check (float)
- **`isnanf(float x)`** - NaN check (float)
- **`isnormalf(float x)`** - Normal check (float)
- **`signbitf(float x)`** - Sign check (float)

### Classification (long double versions)
- **`isfinitel(long double x)`** - Finite check (long double)
- **`isinfl(long double x)`** - Infinite check (long double)
- **`isnanl(long double x)`** - NaN check (long double)
- **`isnormall(long double x)`** - Normal check (long double)
- **`signbitl(long double x)`** - Sign check (long double)

### Comparison Functions
- **`fpclassify(double x)`** - Classify floating-point value
- **`isgreater(double x, double y)`** - Check x > y (avoids NaN issues)
- **`isgreaterequal(double x, double y)`** - Check x >= y (avoids NaN issues)
- **`isless(double x, double y)`** - Check x < y (avoids NaN issues)
- **`islessequal(double x, double y)`** - Check x <= y (avoids NaN issues)
- **`islessgreater(double x, double y)`** - Check x < y or x > y (avoids NaN issues)
- **`isunordered(double x, double y)`** - Check if x or y is NaN

### Comparison (float/long double versions)
- **`fpclassifyf(float x)`** - Classify (float)
- **`isgreaterf(float x, float y)`** - Compare > (float)
- **`isgreaterequalf(float x, float y)`** - Compare >= (float)
- **`islessf(float x, float y)`** - Compare < (float)
- **`islessequalf(float x, float y)`** - Compare <= (float)
- **`islessgreaterf(float x, float y)`** - Compare <> (float)
- **`isunorderedf(float x, float y)`** - Unordered check (float)
- **`fpclassifyl(long double x)`** - Classify (long double)
- **`isgreaterl(long double x, long double y)`** - Compare > (long double)
- **`isgreaterequall(long double x, long double y)`** - Compare >= (long double)
- **`islessl(long double x, long double y)`** - Compare < (long double)
- **`islessequall(long double x, long double y)`** - Compare <= (long double)
- **`islessgreaterl(long double x, long double y)`** - Compare <> (long double)
- **`isunorderedl(long double x, long double y)`** - Unordered check (long double)

## 8. Mathematical Constants

### Standard Mathematical Constants (defined as macros)
- **`M_E`** - Euler's number (e)
- **`M_LOG2E`** - Log base 2 of e
- **`M_LOG10E`** - Log base 10 of e
- **`M_LN2`** - Natural logarithm of 2
- **`M_LN10`** - Natural logarithm of 10
- **`M_PI`** - Pi (π)
- **`M_PI_2`** - Pi/2
- **`M_PI_4`** - Pi/4
- **`M_1_PI`** - 1/pi
- **`M_2_PI`** - 2/pi
- **`M_2_SQRTPI`** - 2/sqrt(pi)
- **`M_SQRT2`** - Square root of 2
- **`M_SQRT1_2`** - 1/sqrt(2)

### Mathematical Constants (C99+ functions)
- **`INFINITY`** - Infinity constant
- **`NAN`** - Not a Number constant

## 9. Error and Gamma Functions

### Error Functions
- **`erf(double x)`** - Error function
- **`erfc(double x)`** - Complementary error function
- **`tgamma(double x)`** - Gamma function
- **`lgamma(double x)`** - Natural logarithm of gamma function

### Error Functions (float versions)
- **`erff(float x)`** - Error function (float)
- **`erfcf(float x)`** - Complementary error function (float)
- **`tgammaf(float x)`** - Gamma function (float)
- **`lgammaf(float x)`** - Log gamma function (float)

### Error Functions (long double versions)
- **`erfl(long double x)`** - Error function (long double)
- **`erfcl(long double x)`** - Complementary error function (long double)
- **`tgammal(long double x)`** - Gamma function (long double)
- **`lgammal(long double x)`** - Log gamma function (long double)

## 10. Complex Math Functions (C99+)

### Complex Arithmetic
- **`cabs(double complex z)`** - Absolute value of complex number
- **`carg(double complex z)`** - Argument (phase) of complex number
- **`cexp(double complex z)`** - Complex exponential
- **`clog(double complex z)`** - Complex logarithm
- **`csqrt(double complex z)`** - Complex square root
- **`cpow(double complex base, double complex exp)`** - Complex power
- **`csin(double complex z)`** - Complex sine
- **`ccos(double complex z)`** - Complex cosine
- **`ctan(double complex z)`** - Complex tangent
- **`casin(double complex z)`** - Complex arc sine
- **`cacos(double complex z)`** - Complex arc cosine
- **`catan(double complex z)`** - Complex arc tangent
- **`csinh(double complex z)`** - Complex hyperbolic sine
- **`ccosh(double complex z)`** - Complex hyperbolic cosine
- **`ctanh(double complex z)`** - Complex hyperbolic tangent
- **`casinh(double complex z)`** - Complex inverse hyperbolic sine
- **`cacosh(double complex z)`** - Complex inverse hyperbolic cosine
- **`catanh(double complex z)`** - Complex inverse hyperbolic tangent

### Complex (float versions)
- **`cabsf(float complex z)`** - Absolute value (float complex)
- **`cargf(float complex z)`** - Argument (float complex)
- **`cexpf(float complex z)`** - Complex exponential (float)
- **`clogf(float complex z)`** - Complex logarithm (float)
- **`csqrtf(float complex z)`** - Complex square root (float)
- **`cpowf(float complex base, float complex exp)`** - Complex power (float)
- **`csinf(float complex z)`** - Complex sine (float)
- **`ccosf(float complex z)`** - Complex cosine (float)
- **`ctanf(float complex z)`** - Complex tangent (float)
- **`casinf(float complex z)`** - Complex arc sine (float)
- **`cacosf(float complex z)`** - Complex arc cosine (float)
- **`catanf(float complex z)`** - Complex arc tangent (float)
- **`csinhf(float complex z)`** - Complex hyperbolic sine (float)
- **`ccoshf(float complex z)`** - Complex hyperbolic cosine (float)
- **`ctanhf(float complex z)`** - Complex hyperbolic tangent (float)
- **`casinhf(float complex z)`** - Complex inverse hyperbolic sine (float)
- **`cacoshf(float complex z)`** - Complex inverse hyperbolic cosine (float)
- **`catanhf(float complex z)`** - Complex inverse hyperbolic tangent (float)

### Complex (long double versions)
- **`cabsl(long double complex z)`** - Absolute value (long double complex)
- **`cargl(long double complex z)`** - Argument (long double complex)
- **`cexpl(long double complex z)`** - Complex exponential (long double)
- **`clogl(long double complex z)`** - Complex logarithm (long double)
- **`csqrtl(long double complex z)`** - Complex square root (long double)
- **`cpowl(long double complex base, long double complex exp)`** - Complex power (long double)
- **`csinl(long double complex z)`** - Complex sine (long double)
- **`ccosl(long double complex z)`** - Complex cosine (long double)
- **`ctanl(long double complex z)`** - Complex tangent (long double)
- **`casinl(long double complex z)`** - Complex arc sine (long double)
- **`cacosl(long double complex z)`** - Complex arc cosine (long double)
- **`catanl(long double complex z)`** - Complex arc tangent (long double)
- **`csinhl(long double complex z)`** - Complex hyperbolic sine (long double)
- **`ccoshl(long double complex z)`** - Complex hyperbolic cosine (long double)
- **`ctanhl(long double complex z)`** - Complex hyperbolic tangent (long double)
- **`casinhl(long double complex z)`** - Complex inverse hyperbolic sine (long double)
- **`cacoshl(long double complex z)`** - Complex inverse hyperbolic cosine (long double)
- **`catanhl(long double complex z)`** - Complex inverse hyperbolic tangent (long double)

## Usage Notes

### Compilation
```c
#include <math.h>

// Link with math library
// gcc program.c -o program -lm
```

### Function Naming Conventions
- **`f`** suffix: `sinf()`, `cosf()`, etc. - for `float` arguments
- **`l`** suffix: `sinl()`, `cosl()`, etc. - for `long double` arguments
- No suffix: `sin()`, `cos()`, etc. - for `double` arguments
- **`c` prefix**: `cabs()`, `csin()`, etc. - for complex numbers
- **`_` prefix**: `_Float32`, `_Float64`, `_Float128` - for extended precision (C23)

### Domain and Range
- Most functions have specific domain requirements
- Check function documentation for valid input ranges
- Functions may return NaN for invalid inputs
- Some functions have overflow/underflow protections

### Performance Considerations
- Use appropriate precision level (float/double/long double)
- Avoid redundant calculations (precompute constants)
- Consider using compiler optimizations (`-O2`, `-O3`)
- For frequently called functions, cache results when possible

### Standards Compliance
- Most functions are available in C89/C90 standard
- Complex math functions require C99 or later
- Some functions may be extensions in certain implementations
- Check your compiler's math.h header for exact availability
