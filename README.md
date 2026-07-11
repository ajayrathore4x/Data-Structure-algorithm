# Data-Structure-algorithm
normal to hard question 
reverse an array 
<br>
void reversearr(vector<int>& arr){
    int st=0,end=arr.size()-1;
    while(st<end){
        swap(arr[st],arr[end]);
        st++;
        end--;
    }
    return;
}
void printarr(vector<int>& arr){
    for(int val : arr){
        cout<<val<<" ";
    }
    return;
}
int main(){
    vector<int>arr={2,3,4,5,6};
    reversearr(arr);
    printarr(arr);
    return 0;
}
<br>
