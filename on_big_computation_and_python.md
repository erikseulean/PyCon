#### Big computation in python

Takeaways: 
- Python is not the best language for big computation.
- It does a good job well, but it's not good for everything.
- Don't be afraid to be a polyglot engineer. Choose your programming languages based on your needs.
- There are decent options to write code that is making good use of all your resources. Rust, D, Chapel. Ignore C, C++ for the good well known reasons. 
- numpy (even being written in C) is slow because everything is vectorized. Multiplying 2 vectors cannot be paralelyzed and this is basically making it slow. 
