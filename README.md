# MPI_FFT
When problem size is 8192:

  serial 4.7s

  2 process 2.07s

  4 process 1.10s

  8 process 0.69s

  16 process 0.61s

  32 process 0.50s

  64 process 0.48s

When problem size is 1024:

  serial 0.064s

  2 process 0.034s

  4 process 0.020s

  8 process 0.020s

  16 process 0.017s

  32 process 0.0209s

  64 process 0.010s

  128 process 0.012s

When problem size is 32768:

  serial 69s

  2 process 33.0s

  4 process 18.73s

  8 process 12.55s

  16 process 8.384s

  32 process 6.22s

  64 process 6.5s

  128 process 10s

More process take more time for communication.
