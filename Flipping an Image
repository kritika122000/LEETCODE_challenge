class Solution {
public:
    vector<vector<int>> flipAndInvertImage(vector<vector<int>>& A) {
        vector<vector<int>> res;
        int n = A.size();
        int m = A[0].size();
        for(int i=0;i<n;i++){
            int low=0, high =  m-1;
            while(low<=high){
                if(A[i][low] == A[i][high]){
                    A[i][low] = 1-A[i][low];
                    A[i][high] = A[i][low];
                }
                low++;
                high--;
            }
        }
        return A;
        
    }
};
