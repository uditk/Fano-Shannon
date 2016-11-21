#Shannon Fano Algorithm implementation

### Files description

  * ShannonFano.py 

  * original.pgm - original monochrome PGM file

  * binary - Encoded binary file

  * decompress.pgm - Decoded PGM file from binary


### Run the algorithm

 1. Step 1: Encoding the monochrome PGM file into a binary (original.pgm -> binary)

  * python ShannonFano.py e original.pgm binary.pgm


 2. Step 2: Decode binary back to PGM file (binary -> decompress.pgm)

  * python ShannonFano.py d binary decompress.pgm


### Note: Syntax 

  * python ShannonFano.py [e|d] [path]InputFileName [path]OutputFileName


