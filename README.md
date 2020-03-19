#include <iostream>
using namespace std;
int main(){
  
  int A[3][3], B[3][3], C[3][3];
  int m,n; 
  
  cout<<"      Program Penjumlahan 2 Matriks\n";
  cout<<"      =============================\n"<<endl;
  cout<<"Berikan Matriks Pertama (3x3): \n\n";
  
  for(m=0; m<3; m++) {
  	for(n=0; n<3; n++){
            cin>>A[m][n];
        }
  }
  cout<<endl;
  cout<<"Berikan Matriks Kedua (3x3): \n\n";
  
  for(m=0; m<3; m++){
        for(n=0; n<3; n++){
            cin>>B[m][n];
