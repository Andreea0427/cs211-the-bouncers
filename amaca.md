# Profile: [Andreea Macovei]

- **NetID:** [amaco]
- **Major:** [Computer Science + Design]
**Question that I chose from the memoization exercise:** [Count ways to reach the n'th stair]
- **Link to the question article:** [https://www.geeksforgeeks.org/dsa/count-ways-reach-nth-stair/]
- **My solution:**
int countWays(int n) {
    if(n == 0 || n == 1){
        return 1;
    }
    
    return countWays(n-1) + countWays(n-2);
    
}
