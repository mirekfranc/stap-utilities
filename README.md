stap-utilities
==============

various useful utilities based on systemtap

aslr-recorder.stp : Allows to record and later replay randomized memory layout
                    on linux for the identical run of a program.
                    /proc/sys/kernel/randomize_va_space != 0 obviously
                    Immensely useful for debugging/reproducing certain issues.
