# DynamiCprogramming


Certainly! Here's a categorized list of important dynamic programming problems based on the type of dynamic programming approach used. You can paste this in your README file on GitHub.

### Dynamic Programming Problems Categorized by Type

#### 1. **1D DP**
   - **Longest Increasing Subsequence**
     - [LeetCode 300: Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
   - **Maximum Subarray Sum (Kadane's Algorithm)**
     - [LeetCode 53: Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)
   - **House Robber Problem**
     - [LeetCode 198: House Robber](https://leetcode.com/problems/house-robber/)
   - **Climbing Stairs**
     - [LeetCode 70: Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
   - **Minimum Path Sum**
     - [LeetCode 64: Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)

#### 2. **2D DP**
   - **Longest Common Subsequence**
     - [LeetCode 1143: Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
   - **Edit Distance**
     - [LeetCode 72: Edit Distance](https://leetcode.com/problems/edit-distance/)
   - **Unique Paths**
     - [LeetCode 62: Unique Paths](https://leetcode.com/problems/unique-paths/)
   - **Palindrome Partitioning**
     - [LeetCode 131: Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)
   - **Minimum Path Sum**
     - [LeetCode 64: Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)
   - **Longest Palindromic Substring**
     - [LeetCode 5: Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)

#### 3. **Backtracking with DP**
   - **Word Break Problem**
     - [LeetCode 139: Word Break](https://leetcode.com/problems/word-break/)
   - **Subset Sum Problem**
     - [LeetCode 416: Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)

#### 4. **Combination DP**
   - **0/1 Knapsack Problem**
     - [LeetCode 416: Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
   - **Coin Change Problem**
     - [LeetCode 322: Coin Change](https://leetcode.com/problems/coin-change/)

#### 5. **Advanced DP**
   - **Frog Jump**
     - [LeetCode 403: Frog Jump](https://leetcode.com/problems/frog-jump/)
   - **Burst Balloons**
     - [LeetCode 312: Burst Balloons](https://leetcode.com/problems/burst-balloons/)
   - **Capacity to Ship Packages Within D Days**
     - [LeetCode 1011: Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)

### Additional Notes:
- **1D DP**: Problems that can be solved using a single-dimensional array for storing states.
- **2D DP**: Problems requiring a two-dimensional array for storing states (usually involving two input sequences).
- **Backtracking with DP**: Problems that utilize a backtracking approach while caching results to avoid recalculating.
- **Combination DP**: Problems that involve selecting items with constraints, often related to knapsack or coin change problems.
- **Advanced DP**: More complex problems that may combine different techniques or require a deeper understanding of DP principles.

Feel free to adjust or expand upon this list as you see fit!


Group 1 (warmup):
### Basic questions to get a feel of DP.

https://leetcode.com/problems/climbing-stairs/ in linear time

https://leetcode.com/problems/n-th-tribonacci-number/ in linear time

https://leetcode.com/problems/perfect-squares/ (maybe)

### Group 2 (linear sequence, linear time, constant transition):
Dp solution requires us to solve the sub problem on every prefix of the array. A prefix of the array is a subarray from 0 to i for some i.

https://leetcode.com/problems/min-cost-climbing-stairs/ in linear time

https://leetcode.com/problems/minimum-time-to-make-rope-colorful/

https://leetcode.com/problems/house-robber/

https://leetcode.com/problems/decode-ways/

https://leetcode.com/problems/minimum-cost-for-tickets/

https://leetcode.com/problems/solving-questions-with-brainpower/

### Group 3 (on grids):
Dp table will have the same dimensions as grid, the state at cell i,j will be related to the grid at cell i,j.

https://leetcode.com/problems/unique-paths/

https://leetcode.com/problems/unique-paths-ii/

https://leetcode.com/problems/minimum-path-sum/

https://leetcode.com/problems/count-square-submatrices-with-all-ones/

https://leetcode.com/problems/maximal-square/

https://leetcode.com/problems/dungeon-game/

### Group 4 (two sequences, O(NM) style):
Dp[i][j] is some value related to the problem solved on prefix of sequence 1 with length i, and prefix on sequence 2 with length j.

https://leetcode.com/problems/longest-common-subsequence/

https://leetcode.com/problems/uncrossed-lines/ (longest common subsequence)

https://leetcode.com/problems/minimum-ascii-delete-sum-for-two-strings/

https://leetcode.com/problems/edit-distance/

https://leetcode.com/problems/distinct-subsequences/

https://leetcode.com/problems/shortest-common-supersequence/

### Group 5 (Interval dp):
Dp problem is solved on every single interval (subarray) of the array

https://leetcode.com/problems/longest-palindromic-subsequence/

https://leetcode.com/problems/stone-game-vii/

https://leetcode.com/problems/palindromic-substrings/

https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/ (hard to see interval)

https://leetcode.com/problems/strange-printer/ (hard)

https://leetcode.com/problems/burst-balloons/ (hard)

### Group 6 (linear sequence transition like N2 Longest Increasing Subsequence)
Dp problem is solved on every prefix of the array. Transition is from every index j < i.

https://leetcode.com/problems/count-number-of-teams/

https://leetcode.com/problems/longest-increasing-subsequence/

https://leetcode.com/problems/partition-array-for-maximum-sum/

https://leetcode.com/problems/largest-sum-of-averages/

https://leetcode.com/problems/filling-bookcase-shelves/

### Group 7 (knapsack-like)
Dp state is similar to the classical knapsack problem.

https://leetcode.com/problems/partition-equal-subset-sum/

https://leetcode.com/problems/number-of-dice-rolls-with-target-sum/

https://leetcode.com/problems/combination-sum-iv/

https://leetcode.com/problems/ones-and-zeroes/

https://leetcode.com/problems/coin-change/

https://leetcode.com/problems/coin-change-ii/

https://leetcode.com/problems/target-sum/

https://leetcode.com/problems/last-stone-weight-ii/

https://leetcode.com/problems/profitable-schemes/ (hard)

### Group 8 (topological sort with graphs. advanced, optional)
Solve dp on all subgraphs that are connected to each node

https://leetcode.com/problems/longest-string-chain/

https://leetcode.com/problems/longest-increasing-path-in-a-matrix/

https://leetcode.com/problems/course-schedule-iii/

### Group 9 (dp on trees. advanced, optional)
Solve dp problem on all subtrees.

https://leetcode.com/problems/house-robber-iii/

https://leetcode.com/problems/binary-tree-cameras/
