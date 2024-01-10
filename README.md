//This is for getting index location of an array 
// for particular element 

#include<stdio.h>
    int main(){
        int nums[4]={1,5,4,6};
        int target=5;
        for(int i=0 ; i<4 ; i++){
            if(target==nums[i]){
            printf("The output is %d \n",i);
          }
        }
        return 0;
    }
