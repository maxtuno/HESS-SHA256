# HESS-SHA256
A sha256 sequential inverter with HESS algorithm.

HESS with SHA256 (Canonical) Oracle
=======================

By Oscar Riveros

Usage:
    
    hess-sha256 hash number_of_bytes_on_the_password 
    hess-sha256-mt hash number_of_bytes_on_the_password number_of_threads

Tip: in case of unknown password leng, use multiples, on multiples machines.

[![Watch the video](https://img.youtube.com/vi/U5r9sHa6DiQ/hqdefault.jpg)](https://youtu.be/U5r9sHa6DiQ)

# Password 3
    hess-sha256.exe 4e07408562bedb8b60ce05c1decfe3ad16b72230967de01f640b7e4729b49fce 1
    c 0 | 0 (s) | 3 | 4e07408562bedb8b60ce05c1decfe3ad16b72230967de01f640b7e4729b49fce

# Password 3K
    hess-sha256.exe 7594ee1cc8fb538281b40e95d497dd72d991ba9323d2dafa6e424b591ff084b2 2
    c 0 | 0 (s) | 3K | 7594ee1cc8fb538281b40e95d497dd72d991ba9323d2dafa6e424b591ff084b2

# Password 3KC
    hess-sha256.exe 5ee4a4acaa94bc1e489740a100a660fe336f47e061859a9a4c631eaaa887bc54 3
    c 0 | 7 (s) | 3KC | 5ee4a4acaa94bc1e489740a100a660fe336f47e061859a9a4c631eaaa887bc54

# Password 3KC*
    hess-sha256.exe 7e1bec5ee860d362c9aa6c535d2ec3568c9d30f0f1a845e0595d860b90d98db5 4
    c 0 | 56 (s) | 3KC* | 7e1bec5ee860d362c9aa6c535d2ec3568c9d30f0f1a845e0595d860b90d98db5
    
    hess-sha256-mt.exe 7e1bec5ee860d362c9aa6c535d2ec3568c9d30f0f1a845e0595d860b90d98db5 4 4
    c (4) 0 | 16 (s) | 3KC* | 7e1bec5ee860d362c9aa6c535d2ec3568c9d30f0f1a845e0595d860b90d98db5
    

# Password 3KC*d
    hess-sha256.exe 70516e7d37d344e832d8f89040ae3ee3dc3a87a85905fb206f110f639f874918 5
    evaluating...

Thanks to:
PicoSHA2 - a C++ SHA256 hash generator
https://github.com/okdshin/PicoSHA2
