# STOS Public Repository Security Boundary

This repository is public.

It must not contain:

- secret values
- protected runtime configuration
- private CORE material
- production credentials
- private student information
- private recovery assets
- internal keys or authentication material

Public documentation may describe architecture at a high level, but implementation details that materially expose protected controls should remain behind the private STOS trust boundary.

Use placeholders and environment-variable names only in public configuration examples.
