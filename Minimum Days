class Solution {
  public:
    int getMinimumDays(int N,string S, vector<int> &P) {
        // code here
        int days = 0;
        for(int i=0; i<N-1; i++){
            while(S[i+1] == S[i] && S[i] != '?'){
                S[P[days]] = '?'; // keep iterating over the days and keep filling with ? markks
                days++;
            }
        }
        return days;
    }
};
