class Solution{
public:
    int prefixSuffixString(vector<string> &s1,vector<string> s2){
        // Code here
        unordered_set<string>st;
        for(int i = 0 ; i < s2.size() ; i++){
            st.insert(s2[i]);
        }
        for(int i = 0 ; i < s1.size() ; i++){
            string fr = "";
            string bk = s1[i];
            for(int j = 0 ; j < s1[i].length() ; j++){
                if(st.find(fr)!=st.end()) st.erase(fr);
                if(st.find(bk)!=st.end()) st.erase(bk);
                fr = fr + s1[i][j];
                bk.erase(0,1);
            }
        }
        return s2.size() - st.size();
    }
};
