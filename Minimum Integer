class Solution {
  public:
    int minimumInteger(int N, vector<int> &A) {
        // code here
        long S = 0;
        for(int i=0;i<N;i++){
            S+=A[i];
        }
        long X = INT_MAX;
        for(int i=0; i<N; i++){
            if(S<=(long)N*A[i]){
                X = min((long)A[i], X);
            }
        }
        return X;
    }
};
