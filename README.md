# IDA7 Hex-Rays Invert If-Statement

Code originally from the Hex-Rays SDK examples. I have made a solution to compile it for convenience since IDAPython's copy constructor for `cexpr_t` seems broken, breaking the Python version.

# Compiling Notes

The following system environment variables should be set before running Visual Studio, or in the Property Manager by editing `PropertySheet.props`:

1. `$(IDADIR)` - path to IDA 7.0 where ida64.exe can be found

The IDA 7.0 SDK should also be located at `$(IDADIR)\idasdk70`.

# Credits

- Hex-Rays for code
