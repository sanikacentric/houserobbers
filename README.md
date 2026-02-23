# 🏠 House Robber

Python solution for the House Robber dynamic programming problem — maximize robbery amount without robbing adjacent houses.

## 🎯 Problem

Given an array representing money in each house, determine the maximum amount you can rob without robbing two adjacent houses.

## 💡 Approach

- **Dynamic Programming** — O(n) time, O(1) space with two variables tracking max profit
- - **State Transition**: `dp[i] = max(dp[i-1], dp[i-2] + nums[i])`
 
  - ## 🛠️ Tech Stack
 
  - - **Language**: Python
    - - **Category**: Dynamic Programming
      - - **Difficulty**: Medium (LeetCode #198)
       
        - ## 📄 License
       
        - This project is open source and available for educational purposes.
