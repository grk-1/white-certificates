# White certificates

Computational certificates for **White’s conjecture, exchange defects and sharp Gröbner bounds for matroids**, by Eren Ercan.

The version 1 release contains the complete text inputs, RUP proof traces, verification code and retained replay records used by the manuscript. Download `white-certificates-v1.tar.xz` from the release and extract it. The archive’s `README.txt` gives the reproduction commands, and `MANIFEST.json` records every included file’s SHA-256 and size.

The current paper uses 54 RUP traces, with 4,182,181 additions in the recorded verification. The data also retains the six retired traces with their historical scope. All portable verification inputs are present. The three native-object pickle snapshots have been omitted because the portable verifiers read the JSON data.

The finite proof drivers require Python 3.10+ and a C++17 compiler. Individual algebraic computations identify their additional requirements in the corresponding README files.

The release contains 577 files from the original certificate index, plus the subsequent verification records and release documentation. Packaging checks establish exact file identity. The mathematical verification records retain their original dates and scope.
