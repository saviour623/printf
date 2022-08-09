Hi This is a project on the FUNCTION PRINTF.
The derived function "_printf" sends output to standard output with the following format specifiers below.

   _printf("Length:[%d, %i]\n", len, len);

printf("Length:[%d, %i]\n", len2, len2);

_printf("Negative:[%d]\n", -762534);

printf("Negative:[%d]\n", -762534);

_printf("Unsigned:[%u]\n", ui);

printf("Unsigned:[%u]\n", ui);

_printf("Unsigned octal:[%o]\n", ui);

_printf("Unsigned octal:[%o]\n", ui);

_printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);

_printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);

__printf("Character:[%c]\n", 'H');

_printf("Character:[%c]\n", 'H');

_printf("String:[%s]\n", "I am a string !");

_printf("String:[%s]\n", "I am a string !");

_printf("Address:[%p]\n", addr);

_printf("Address:[%p]\n", addr);

len = _printf("Percent:[%%]\n");

len2 = printf("Percent:[%%]\n");

_printf("Len:[%d]\n", len);

_printf("Len:[%d]\n", len2);

_printf("Unknown:[%r]\n");