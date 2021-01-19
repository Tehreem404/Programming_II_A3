# Programming_II_A3

[AUTHOR]
    Name: Tehreem Nazar
    Student Number: 1108993


[DESCRIPTION]
    Program 1 (frequency_table.c):
        Creates a frequency table based on what the user inputs

    Program 2 (decode.c):
        Has several functions, reads flags and outputs corresponding information
        flags:
        [-f <filename.txt] => reads encoded text from a file
        [-O <newfile.txt>] => makes a new file to put decoded text into
        [-n] => stops printing of decoded text
        [-s] => does cesear shift and also prints it
        [-S] => prints original cesar shift value used to incode text
        [-t] => prints letter count and frequency table
        [-x] => prints chi-squared table


[USAGE]
    frequency_table:
    make frequency_table
    ./frequency_table

    decode:
    make decode
    ./decode -sStxn -F <filename.txt> -O <newfile.txt>


[FILENAMES]
    chi_squared.c
    create_freqt.c
    decode.c
    decode.h
    encode_shift.c
    encode.c
    eng_freq.h
    file_size.c
    frequency_table.c
    letter_count.c
    offset.c
    to_decode.c
