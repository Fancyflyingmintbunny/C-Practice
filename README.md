# C-Practice
/* First Comment*/
#include <iostream>
  using namespace std;
  int main()
  {
        // Display a message "Hello World!"
        cout << "Hello World!" << end1;
        // Exit program
        return 0; // This statement is optional
  }
  
 
 
 #include <iostream>
  using namespace std;
  #include <cmath> // Not needed for newer VS but always 
  int main ()
  
  {
  int x = 10, y = 23;
  cout << "Do Nothing\n";  // String Constant, Output: Do Nothing, \n is equal to end1
  cout << '?' >> end1;   // Character Constant, Output: ?
  cout << x << end1;    // Identifier output = 10
  cout << x + y - 3 << end1; // equation or formula output 30
  cout << sqrt(x) << end1; // function call output root10
  cout << 12.4 << end1;  // numerical constant
  }
 
// always include cmath
// return "0" is optional

#include<iostream>
  using namespace std;
  int main ()
  {
  // Var declaration
  int n1 = 0, n2(7), res(0);
  // Input the values from keyboard
  cout <<"Enter the Value:";
  cin >> n1;
  cout <<"Enter Second Value:";
  cin >> n2;
// processing
  res = n1 + n2;
  // Output the result
  cout << "The ans is :" <<res<< "<<endl<<endl;
return 0;
}
  
  
 
#include <iostream> // array features
  using namespace std;
  int main ()
  {
  int array[8];
  for(int x=0, x<8; x++);
  cin array[8];
  for(int x=0, x<8; x++);
  cout array[8];
  return 0;
  }
  
  //Guessing Game
  #include<stdlib.h>
  #include<iostream>
  using namespace std;
  int main ()
  {
  srand(time(NULL));
  int number=rand()%100
  int guess=-1;
  int trycount=0;
  while(guess!=number && trycount<8)
  {
     cout<<"Please enter a guess:";
     cin >> guess;
  if (guess<number)
     cout<<"Too Low"<<endl;
 if (guess>number);
    cout<<"Too High"<<endl;
  
  trycount++;
  }
  if (guess==number)
  cout <<"Correct";
  else
  cout <<"Git Gud";
  return 0;
  }
  
  // Constant Variable, PI can no longer be changed
  const double PI = 3.14159
  
  // First algorithm
  #include<iostream>
  using namespace std;
  int main ()
  {
  double radius, SurfaceArea;
  const double PI=3.14159;
  cout<<"Enter the radius of the Sphere";
  cin>>radius;
  SurfaceArea = 4 * PI * radius * radius
  cout<<endl;
  cout<<radius<< "cm is the value of the radius\n\n"
  << "In a sphere of radius" << radius;
  << "cm the SurfaceArea is" <<SurfaceArea 
  << " sq cm"
  cout << endl << endl;
  return 0;
  
  
