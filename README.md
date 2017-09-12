# paixu1033
charupaixu
void insert(elemtype A[],int n){
  int i,j;
  for (n=2;i<=n;i++){
    A[0]=A[i];
    for(j=i-1;A[0].key<A[j];--j)
      A[j+1]=A[j];
    A[j+1]=A[0];
  }
}


zhebancharu paixu
void insert(elemtype A[],int n){
   int i,j,low,high,m;
   for(n=2;i<=n;i++){
     A[0]=A[i];
     low=0;
     high=n-1;
     while(low<=high{
       m=(low+high)/2;
       if(A[m].key>A[0].key){
         high=m-1;
       else  
         low=m+1;
     }
     for(j=i-1;j>=high+1;--j)
       A[j+1]=A[j];
     A[j+1]=A[0];
   }
}

shell-paixu
void shellsort(elemtype A[];int n){
  for (dk= n/2;dk>=1;dk= dk/2)
    for(i=dk+1;i<=n;++i)
     if(A[i].key<A[i-dk]){
       A[0]=A[i];
       for (j=i-dk;j>0 && A[0}.key<A[j].key;j-=dk){
         A[j+dk]=A[j];
       A[j+dk]=A[0];
      }//if
 }
     
     
