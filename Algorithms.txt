1. 
Staircase detail

This is a staircase of size n = 4 :
   #
  ##
 ###
####
Its base and height are both equal to . It is drawn using # symbols and spaces. The last line is not preceded by any spaces.

Write a program that prints a staircase of size .

SOLUTION
 public static void staircase(int n)
    {
        for(var i=0;i < n; i++)
        { 
            for(var k = n-i;k > 1; k--){
                 Console.Write(" ");
            }
            for(var j=0; j<i+1;j++){
                Console.Write("#");
            }
            Console.WriteLine();
        
        }
    }



2.     