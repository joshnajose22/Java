#Java
Hardware -> OS -> JDK(Consists JRE (Consist of JVM and libraries))
JVM is platform dependant and Java is platform independant
Variables
Class
Objects
Literals
Type casting is explicitly converting data types
Type conversion is implicitly converting data types
Examples: byte a;
          int b = 257;
          a = (byte) b;//output will be a=1 ie 257%256 = 1 (modulus operator is used and 256 is max range value)
Similarly, float f = 5.6f;
           int a = (int) f;//output will be a=5
Assignment/arithmetic operators examples:
num1 + num2;          num1 / num2;
num1 - num2;          num1 % num2;
num1 * num2;          char1 + 1;
num++ -> post increament / num += 1 -> fetch the value and then increament
++num -> pre increament -> increament and then fetch the value
These get reflected only when assigning / fetcching the data
Relational operators: >,<,>=,<=,==,!= -> returns boolean value true / false
Logical operators:
AND                 OR                  NOT
T T -- T            T T -- T            T -- F
T F -- F            T F -- T
F T -- F            F T -- T
F F -- T            F F -- F
