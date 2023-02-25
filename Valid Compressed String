class Solution {

  public:

    int checkCompressed(string S, string T) {

        

        

        int n=T.size(),j=0,flag=0,i=0;

        while(i<n&&j<S.size())

        {

            

            if(isdigit(T[i]))

            {

                int num=0;

                while(i<T.size() && isdigit(T[i]))

               {

                   num=num*10+(T[i]-'0');

                   i++;

                }

                j+= num ;

                continue;

            }

            

            else

            {

                flag=1;

 

                if(S[j]!=T[i]) return 0;

            } 

            j++;

            i++;

        } 

        

        return i==n&&j==S.size();

    }

};
