This is an aptional RSA Factoring Challenge

For question one
We define a factorize function that takes a number n and returns a pair of factors of n, if they exist. If no such pair exists, it returns None.
In the main block, we check that the program has been invoked with the correct number of command-line arguments (i.e., one).
We open the input file specified on the command line and loop over its lines.
For each line, we convert the input string to an integer and call factorize to get a pair of factors.
If a pair of factors exists, we print it in the desired output format.


For question  two

Factoring large numbers into prime factors is a notoriously difficult problem, and even state-of-the-art algorithms can take a long time to factor large numbers. In general, the time it takes to factor a number depends on the size of the number and the particular algorithm used.

For small RSA numbers (i.e., those with less than 100 digits), it may be possible to factor them in less than 5 seconds using trial division or a similar method. However, as the size of the numbers increases, the difficulty of factoring them increases exponentially.

For example, the largest RSA number factored to date is RSA-250, which has 829 bits (250 decimal digits) and was factored in 2019 using the Number Field Sieve algorithm, which is currently the most efficient algorithm for factoring large numbers. This factorization took over 2700 core-years of computation time, which is equivalent to a single processor running for over 300 years.

Therefore, it is unlikely that we can factor large RSA numbers in less than 5 seconds using currently available methods.
