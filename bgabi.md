- **NetID:** bgabi
- **Major:** Computer Science
- **Question that I chose from the memoization exercise:** program for fibonacci numbers
- **Link to the question article:** https://www.geeksforgeeks.org/dsa/program-for-nth-fibonacci-number/
- **My solution:**
- int nthFibonacci(int n) {
    // code here
    if(n <= 1){
        return n;
    }
    
    return nthFibonacci(n - 1) + nthFibonacci(n - 2);
    
}
