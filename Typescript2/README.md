<!-- Data type in Typescript -->

Number Data Type

# Apply number data type
# Redeclare issue
# How to Add number with data type
# How to use binary and hexadecimal numbers
# Convert string to number
# Type Inference with number
# Decimal with number data type

Categories

# primitive Types
# object Types
# Special Types
# Advanced Types
# Function Types


# 1 Primitive Types
 . number -- let age: number = 25;  
   → numbers (integer, decimal) store karne ke liye

 . string -- let name: string = "vinay";  
   → text / characters store karne ke liye

 . boolean -- let isLogin: boolean = false;  
   → true ya false value ke liye

 . null -- let data: null = null  
   → empty value intentionally assign karne ke liye

 . undefined -- let value: undefined = undefined;  
   → jab value assign hi na ho

 . bigint -- let bigNumber: bigint = 12345678901234567890n;  
   → bahut bade numbers store karne ke liye

 . symbol -- let id: symbol = Symbol("id");  
   → unique value create karne ke liye


# 2 Object Types
 . Array -- let numbers: number[] = [1, 2, 3];  
   → same type ke multiple values store karne ke liye

 . Tuple -- let user: [number, string] = [1, "Aman"];  
   → fixed length aur fixed types ke data ke liye

 . Object -- let person: { name: string; age: number } = { name: "Rohit", age: 22 };  
   → key–value pair me data store karne ke liye


# 3 Special Types
 . any -- let value: any = 10;  
   → kisi bhi type ka data allow karta hai (type checking off)

 . unknown -- let data: unknown = "vinay";  
   → any jaisa hai but use karne se pehle type check karna padta hai

 . void -- function logMessage(): void { console.log("Hello"); }  
   → function kuch return na kare tab use hota hai

 . never -- function throwError(): never { throw new Error("Error"); }  
   → function jo kabhi complete hi nahi hota


# 4 Advanced Types
 . union -- let id: number | string = 101;  
   → variable me multiple types allow karne ke liye

 . intersection -- type Person = { name: string } & { age: number };  
   → multiple types ko combine karne ke liye

 . Type Alias -- type User = { id: number; name: string };  
   → custom reusable type banane ke liye

 . Enum -- enum Status { Pending, Success, Failed }  
   → fixed named constants define karne ke liye

 . Literal Types -- let direction: "up" | "down" | "left" | "right";  
   → specific fixed values ko hi allow karne ke liye


# 5 Function Types
 . Define the type of a function  
   → function ke parameters aur return type define karne ke liye

   Example:
   let add: (a: number, b: number) => number;

   add = (x, y) => {
     return x + y;
   };




# One-Line Revision Trick
Primitive → simple values  
Object → structured data  
Special → special behavior  
Advanced → powerful type combinations  
Function → function ke input aur output ke types


# code runer
 npx tsc <file name>.ts