# 主要过程
1. 不明白数据库的大小
2. 不明白query过程
3. 不明白answer过程
4. 退而求其次，弄清楚Baseline就行，也就是benchmark
5. 


# python3 generate_all_schemes.py && \
python3 generate_all_schemes.py --stream && \
python3 generate_all_schemes.py --high-rate && \
python3 generate_all_schemes.py --stream --high-rate

# python3 select_params.py 20 256 --show-output


PIR over n=32768 elements of size 8192 bytes each.
The total database size is 268Mbytes.
The database is structured as 512 x 2^6.

Communication

         Total offline query size (Kbytes): 13888
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 583
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 253
                        Total (CPU·ms): 822

Database-dependent computation

     First dimension multiply (CPU·ms): 263
                      Folding (CPU·ms): 175
                        Total (CPU·ms): 438

Client computation

               Key generation (CPU·ms): 301
             Query generation (CPU·ms): 26
                     Decoding (CPU·ms): 0


# python3 select_params.py 20 256 --show-output --direct-upload


PIR over n=32768 elements of size 8192 bytes each.
The total database size is 268Mbytes.
The database is structured as 512 x 2^6.

Communication

         Total offline query size (Kbytes): 336
                  First dimension (Kbytes): 15176
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 15176
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 48
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 250
                        Total (CPU·ms): 297

Database-dependent computation

     First dimension multiply (CPU·ms): 242
                      Folding (CPU·ms): 94
                        Total (CPU·ms): 336

# python3 select_params.py 18 30960 --show-output

PIR over n=262144 elements of size 8192 bytes each.
The total database size is 2147Mbytes.
The database is structured as 512 x 2^9.

Communication

         Total offline query size (Kbytes): 17696
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 1004
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 310
                        Total (CPU·ms): 1291

Database-dependent computation

     First dimension multiply (CPU·ms): 2495
                      Folding (CPU·ms): 1964
                        Total (CPU·ms): 4459

Client computation

               Key generation (CPU·ms): 309
             Query generation (CPU·ms): 42
                     Decoding (CPU·ms): 1

# python3 select_params.py 18 30960 --show-output --direct-upload

PIR over n=262144 elements of size 11264 bytes each.
The total database size is 2952Mbytes.
The database is structured as 2048 x 2^7.

Communication

         Total offline query size (Kbytes): 672
                  First dimension (Kbytes): 58128
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 58128
                    Response size (Kbytes) : 24


Database-independent computation

              Main expansion  (CPU·ms): 236
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 907
                        Total (CPU·ms): 1137

Database-dependent computation

     First dimension multiply (CPU·ms): 1904
                      Folding (CPU·ms): 171
                        Total (CPU·ms): 2075

Client computation

               Key generation (CPU·ms): 57
             Query generation (CPU·ms): 1976
                     Decoding (CPU·ms): 0


# python3 select_params.py 14 102400 --show-output


PIR over n=16384 elements of size 8192 bytes each.
The total database size is 134Mbytes.
The database is structured as 512 x 2^5.

Communication

         Total offline query size (Kbytes): 13888
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 440
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 172
                        Total (CPU·ms): 602

Database-dependent computation

     First dimension multiply (CPU·ms): 112
                      Folding (CPU·ms): 92
                        Total (CPU·ms): 204

Client computation

               Key generation (CPU·ms): 232
             Query generation (CPU·ms): 24
                     Decoding (CPU·ms): 0


# python3 select_params.py 14 102400 --show-output --direct-upload


PIR over n=16384 elements of size 13312 bytes each.
The total database size is 218Mbytes.
The database is structured as 1024 x 2^4.

Communication

         Total offline query size (Kbytes): 672
                  First dimension (Kbytes): 29120
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 29120
                    Response size (Kbytes) : 27


Database-independent computation

              Main expansion  (CPU·ms): 144
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 386
                        Total (CPU·ms): 526

Database-dependent computation

     First dimension multiply (CPU·ms): 117
                      Folding (CPU·ms): 16
                        Total (CPU·ms): 133

Client computation

               Key generation (CPU·ms): 25
             Query generation (CPU·ms): 471
                     Decoding (CPU·ms): 0

# python3 select_params.py 20 1024 --show-output


PIR over n=131072 elements of size 8192 bytes each.
The total database size is 1073Mbytes.
The database is structured as 512 x 2^8.

Communication

         Total offline query size (Kbytes): 15456
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 639
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 249
                        Total (CPU·ms): 874

Database-dependent computation

     First dimension multiply (CPU·ms): 1056
                      Folding (CPU·ms): 837
                        Total (CPU·ms): 1892

Client computation

               Key generation (CPU·ms): 261
             Query generation (CPU·ms): 22
                     Decoding (CPU·ms): 0

# python3 select_params.py 20 1024 --show-output --direct-upload

PIR over n=131072 elements of size 8192 bytes each.
The total database size is 1073Mbytes.
The database is structured as 1024 x 2^7.

Communication

         Total offline query size (Kbytes): 336
                  First dimension (Kbytes): 29652
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 29652
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 185
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 288
                        Total (CPU·ms): 469

Database-dependent computation

     First dimension multiply (CPU·ms): 967
                      Folding (CPU·ms): 202
                        Total (CPU·ms): 1169

Client computation

               Key generation (CPU·ms): 13
             Query generation (CPU·ms): 517
                     Decoding (CPU·ms): 0

# python3 select_params.py 23 1024 --show-output


PIR over n=1048576 elements of size 8192 bytes each.
The total database size is 8589Mbytes.
The database is structured as 512 x 2^11.

Communication

         Total offline query size (Kbytes): 17696
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 21


Database-independent computation

              Main expansion  (CPU·ms): 8215
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 3741
                        Total (CPU·ms): 11763

Database-dependent computation

     First dimension multiply (CPU·ms): 33091
                      Folding (CPU·ms): 210927
                        Total (CPU·ms): 244018

Client computation

               Key generation (CPU·ms): 2010
             Query generation (CPU·ms): 332
                     Decoding (CPU·ms): 1

# python3 select_params.py 23 1024 --show-output --direct-upload


Communication

         Total offline query size (Kbytes): 336
                  First dimension (Kbytes): 115808
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 115808
                    Response size (Kbytes) : 20


Database-independent computation

              Main expansion  (CPU·ms): 667
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 1331
                        Total (CPU·ms): 1983

Database-dependent computation

     First dimension multiply (CPU·ms): 7514
                      Folding (CPU·ms): 419
                        Total (CPU·ms): 7933

Client computation

               Key generation (CPU·ms): 30
             Query generation (CPU·ms): 3315
                     Decoding (CPU·ms): 0

# python3 select_params.py 20 1536 --show-output


PIR over n=262144 elements of size 6144 bytes each.
The total database size is 1610Mbytes.
The database is structured as 512 x 2^9.

Communication

         Total offline query size (Kbytes): 13888
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 17


Database-independent computation

              Main expansion  (CPU·ms): 566
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 228
                        Total (CPU·ms): 780

Database-dependent computation

     First dimension multiply (CPU·ms): 2161
                      Folding (CPU·ms): 1241
                        Total (CPU·ms): 3402

Client computation

               Key generation (CPU·ms): 211
             Query generation (CPU·ms): 19
                     Decoding (CPU·ms): 0

# python3 select_params.py 20 1536 --show-output --direct-upload


PIR over n=131072 elements of size 12288 bytes each.
The total database size is 1610Mbytes.
The database is structured as 1024 x 2^7.

Communication

         Total offline query size (Kbytes): 672
                  First dimension (Kbytes): 29456
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 29456
                    Response size (Kbytes) : 26


Database-independent computation

              Main expansion  (CPU·ms): 114
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 366
                        Total (CPU·ms): 477

Database-dependent computation

     First dimension multiply (CPU·ms): 903
                      Folding (CPU·ms): 173
                        Total (CPU·ms): 1076

Client computation

               Key generation (CPU·ms): 24
             Query generation (CPU·ms): 494
                     Decoding (CPU·ms): 0

# python3 select_params.py 17 40960 --show-output


PIR over n=131072 elements of size 8192 bytes each.
The total database size is 1073Mbytes.
The database is structured as 512 x 2^8.

Communication

         Total offline query size (Kbytes): 17696
                  First dimension (Kbytes): 28
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 28
                    Response size (Kbytes) : 21


Database-independent computation

              Main expansion  (CPU·ms): 997
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 306
                        Total (CPU·ms): 1279

Database-dependent computation

     First dimension multiply (CPU·ms): 1166
                      Folding (CPU·ms): 666
                        Total (CPU·ms): 1832

Client computation

               Key generation (CPU·ms): 311
             Query generation (CPU·ms): 23
                     Decoding (CPU·ms): 0

# python3 select_params.py 17 40960 --show-output --direct-upload

PIR over n=131072 elements of size 14336 bytes each.
The total database size is 1879Mbytes.
The database is structured as 1024 x 2^7.

Communication

         Total offline query size (Kbytes): 1344
                  First dimension (Kbytes): 29456
       Total for other dimensions (Kbytes): 0
          Total online query size (Kbytes): 29456
                    Response size (Kbytes) : 29


Database-independent computation

              Main expansion  (CPU·ms): 108
  Further dimension expansion (CPU·ms): 0
                   Conversion (CPU·ms): 800
                        Total (CPU·ms): 905

Database-dependent computation

     First dimension multiply (CPU·ms): 983
                      Folding (CPU·ms): 182
                        Total (CPU·ms): 1165

Client computation

               Key generation (CPU·ms): 53
             Query generation (CPU·ms): 499
                     Decoding (CPU·ms): 0
