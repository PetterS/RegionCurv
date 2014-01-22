# Author: petter.strandmark@gmail.com (Petter Strandmark)

configure_file(cameraman.pgm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/cameraman.pgm COPYONLY)
configure_file(cameraman_small.pgm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/cameraman_small.pgm COPYONLY)
configure_file(cameraman_tiny.pgm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/cameraman_tiny.pgm COPYONLY)

configure_file(leo2_small.ppm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/leo2_small.ppm COPYONLY)
configure_file(leo2_small_bgmask.pgm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/leo2_small_bgmask.pgm COPYONLY)
configure_file(leo2_small_fgmask.pgm ${CMAKE_RUNTIME_OUTPUT_DIRECTORY}/leo2_small_fgmask.pgm COPYONLY)
