<h1>LIBFT</h1>

<h3>Mark: 125/100</h3>

<p>LIBFT, the first project in the 42 Cursus, set about teaching us how standard functions in C work, by implementing our own versions, whilst matching the original functions functionality as per their manual entries. From these functions, we create our own library to use in future projects.</p>

<p>This project was split into 3 parts</p>

<ol>
<li>Standard C Library (libc) Functions - Same protoypes and comply with definition as in the man</li>
<li>Additional Functions - Functions not in libc, or are part of it, but in an altered form</li>
<li>Bonus Functions - List manipulation functions</li>
</ol>

<h3>Creating the library</h3>

<p>Run the following command:</p>

```bash

# Make using the default Makefile

make re

# This creates the function library libft.a at the root
```

<h3>Testing LIBFT functions</h3>

<p>Run these commands to test the libft functionality:</p>

```bash

# Make using the specific Makefile with the -f flag

make re -f testing_Makefile

# Run compiled program

./test_libft
```
<p>Compare the user output with the expected output</p>

