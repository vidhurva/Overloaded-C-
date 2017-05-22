// Overloaded-C-
// C++ Program That uses the same name parameter twice (Overloaded)
// Click on "Raw" for fully typed code

   #include <iostream>
   #include <cmath>
   using namespace std;
   
   int value(int a, int b)
   {
          return (pow(a,b));
  }
  int value(float a, float b)  // the global prototype value can be used more than once (overloaded    ) 
  {
          return (a*b);
  }
  
  int main()
  {
          int x,y;
          x = 5;
          y = 3;
          float s,t; // the float values will be correlated to the earlier float function 
          s = 6;
          t = 8;
  
          cout << value (x,y) << endl;
          cout << value (s,t) << endl;
          return 0;
  }
