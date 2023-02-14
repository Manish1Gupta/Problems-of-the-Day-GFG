class Solution{   

public:

    int minCost(vector<vector<int>> &c, int N) {

        for(int i=1;i<N;i++){

            for(int j=0;j<3;j++){

               c[i][j]=c[i][j]+min(c[i-1][(j+1)%3],c[i-1][(j+2)%3]);

            }

        }

        return min({c[N-1][0],c[N-1][1],c[N-1][2]});

    }

};
