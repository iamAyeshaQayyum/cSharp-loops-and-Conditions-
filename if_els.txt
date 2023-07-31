Example 1: Find Largest Number Using if...else Statement

 int n1, n2, n3;

    Console.WriteLine("Enter three numbers: ");
    n1=Convert.ToInt32(Console.ReadLine());
    n2=Convert.ToInt32(Console.ReadLine());
    n3=Convert.ToInt32(Console.ReadLine());

    // check if n1 is the largest number
    if(n1 >= n2 && n1 >= n3)
        Console.WriteLine("Largest number: " + n1);

    // check if n2 is the largest number
    else if(n2 >= n1 && n2 >= n3)
     Console.WriteLine("Largest number: " + n2);
    
    // if neither n1 nor n2 are the largest, n3 is the largest
    else 
    Console.WriteLine("Largest number: " + n3);