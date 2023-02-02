# RUBY CHEATSHEET

## RULE #1 - WE DON'T TALK ABOUT `i++`
## RULE #2 - WE DON'T TALK ABOUT `i++`

### CASTING METHODS
- `.to_i` - Casts to int by dropping anything after decimal point from a float, no rounding
- `.to_f` - Casts to float
- `.to_s` - Casts to string
- `.to_sym` - Casts to symbol

### STRING CONCATENATION && SUBSTRINGS
- Use `+`, `<<` or `.concat()` to concatenate strings
- `"hello"[0..1]` # => `"he"`
- `"hello"[0, 4]` # => `"hell"`
- `"hello"[-1] # => `"o"`

### ESCAPE CHARACTERS
```bash
\\ #=> backslash
\b #=> backspace
\r #=> carriage return
\n #=> newline
\s #=> space
\t #=> tab
\" #=> double quotation
\' #=> single quotation
```

### STRING INTERPOLATION - STRING PLACEHOLDERS FOR VARIABLES
```bash
name = "Mark"
puts "Oh, hi #{name}!" #=> "Oh, hi Mark!"
puts 'Oh, hi #{name}!' #=> "Oh, hi #{name}!"
```
- Must use double quotation marks for string interpolation to work!
