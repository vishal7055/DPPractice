class Solution
{
    //Bottom-Up DP
    public int climbStairs(int n)
    {
        int[] dp = new int[n + 1];
        dp[0] = 1;
        dp[1] = 2;
        
        for(int i = 2; i < n; i++)
        {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        
        return dp[n - 1];
    }
    //Memoized version (Top-Down DP)
//     public int climbStairs(int n)
//     {
//         int[] dp = new int[n + 1];
//         return recursion(n, dp);
//     }
    
//     private int recursion(int n, int[] dp)
//     {
//         if(n == 0)
//         {
//             return 1;
//         }
        
//         if(dp[n] != 0)
//         {
//             return dp[n];
//         }
        
//         int ans1 = recursion(n - 1, dp);
//         int ans2 = 0;
        
//         if(n > 1)
//         {
//             ans2 = recursion(n - 2, dp);
//         }
        
//         return dp[n] = ans1 + ans2;
//     }
    
    //Recursive version
//     public int climbStairs(int n) 
//     {
//         if(n == 0)
//         {
//             return 1;
//         }
        
//         int ans1 = climbStairs(n - 1);
//         int ans2 = 0;
        
//         if(n > 1)
//         {
//             ans2 = climbStairs(n - 2);
//         }
        
//         return ans1 + ans2;
//     }
}
