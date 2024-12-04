# PHP: Insecure Password Generation

This repository demonstrates a common vulnerability in PHP applications: insecure password generation.
The `bug.php` file shows the vulnerable code. The password generation is done by shuffling the lowercase alphabet and taking a substring.  This is highly predictable and not suitable for real-world applications.
The `bugSolution.php` file provides a secure alternative using `random_bytes()` for cryptographically secure random number generation.