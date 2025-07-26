# PowerShell CSR Generatotion Module

This PowerShell module provides cmdlets for generating Certificate Signing Requests (CSRs). It simplifies the process of creating CSRs for various Certificate Authorities (CAs) and supports multiple key sizes and algorithms.

## Features

- Generate CSRs with RSA or ECDSA keys
- Supports multiple key sizes (2048, 3072, 4096 for RSA; 256, 384, 521 for ECDSA)
- Customizable subject names and extensions
- Customizable Lifetime for the certificate
- Outputs the CSR in PEM format
- Standardized properties can be saved to a file for reuse.
