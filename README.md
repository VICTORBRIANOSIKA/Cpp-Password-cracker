*/ # Cpp-Password-cracker */
 */ #C++ pasword Cracker  */
 */ Created by VICTOR BRIAN */
 */ vicbrio652@gmail.com */
 
 
 
  #include <iostream> 
 using namespace std;
  int main() 
  { 
      int password; 
  cout <<"+++++ all the credit to VICBRIO652@gmail.com +++++"<<endl; 
  cout<<"*******"<<endl;
  cout<<"******"<<endl;
  
  cout << "Enter a password to bruteforce.. : "; 
  cin >> password; 
  for (int i = 0; i < 999999; i++) 
       {
    if (i == password){
        
cout<<"****"<<endl;
  cout<<"*****"<<endl;
  cout<<"****"<<endl;
  cout<<"***"<<endl;
  cout<<"**"<<endl;
  cout<<"*"<<endl;
        cout << "The brute-forced password is = " << i << endl; 
         break; 
        } 
  cout << "Loading..[" << i << "]\n"; 
  } 
  return 0; 
  } 
