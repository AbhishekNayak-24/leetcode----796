# leetcode----796
Rotate String
//code in C++
class Solution {
 public:
  bool rotateString(string s, string goal) {
    return s.length() == goal.length() && (s + s).find(goal) != string::npos;
  }
};
