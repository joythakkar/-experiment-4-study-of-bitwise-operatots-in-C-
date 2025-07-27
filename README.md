AIM:

    To study and implement C++ Bitwise Operators

SOFTWARE USED:

     VS Code

Theory:

    Bitwise operators in C++ are used to perform operations at the bit level. These operators directly manipulate the binary representations of data, making them efficient for low-level programming, embedded systems, and performance-critical applications.

     C++ provides the following bitwise operators:

         1.& (Bitwise AND):Sets each bit to 1 if both bits are 1.
              Example: a & b

        2.| (Bitwise OR):Sets each bit to 1 if at least one of the bits is 
                Example: a | b

        3.^ (Bitwise XOR):Sets each bit to 1 if only one of the bits is 1.
                    Example: a ^ b

        4.~ (Bitwise NOT):Inverts all the bits.
                    Example: ~a

        5.<< (Left Shift):Shifts bits to the left by the specified number of positions.
                Example: a << 1

        6.>> (Right Shift):Shifts bits to the right by the specified number of positions.
              Example: a >> 1

       Bitwise operators are typically used in situations where direct manipulation of bits is necessary, such as in cryptography, device drivers, graphics, and memory-efficient computations.


SAMPLE OUTPUT:

    bitwise operators program-

            AND: 0
            OR:6
            NOT: -5
            XOR: 6
            right shift: 1
            left shift: 4

    Performing bitset & reset program-

          Enter the bit position to be set:
          7
          Enter the bit position to be reset:
          90
          Your number is:152
          Your number is:24


CONCLUSION:

     In this experiment, we successfully studied and implemented various C++ bitwise operators such as AND (&), OR (|), XOR (^), NOT (~), left shift (<<), and right shift (>>). These operators allowed us to perform efficient binary-level operations on integer data. Understanding and applying bitwise operators is essential for optimizing performance in low-level programming and for solving problems that involve binary logic and data masking.

