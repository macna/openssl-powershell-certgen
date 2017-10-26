# Script to more-easily generate SAN certificates using PowerShell and OpenSSL

This PowerShell script can be used to generate a standard certificate request with a correctly-formed CN and SANs.

The variable $openSSLDir needs setting to the location of openssl.exe. The CSR and private key files will be output to C:\Temp\ or a location of your choice.