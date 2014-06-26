Displays contents of ASN.1 encoded data.

Sample output from this program (using the default format) is::

     256  159: SEQUENCE {
     259   13:   SEQUENCE {
     261    9:     OBJECT IDENTIFIER rsaEncryption (1 2 840 113549 1 1 1)
     272    0:     NULL
             :     }
     274  141:   BIT STRING, encapsulates {
     278  137:     SEQUENCE {
     281  129:       INTEGER
             :         00 E5 19 BF 6D A3 56 61 2D 99 48 71 F6 67 DE B9
     [...]   :         8F
     413    3:       INTEGER 65537
             :       }
             :     }
             :   }

See https://www.cs.auckland.ac.nz/~pgut001/ for details.
