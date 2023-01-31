// Задача 64: Задайте значение N. Напишите программу, которая 
// выведет все натуральные числа в промежутке от N до 1. 
// Выполнить с помощью рекурсии.
// N = 5 -> "5, 4, 3, 2, 1"
// N = 8 -> "8, 7, 6, 5, 4, 3, 2, 1"



// int N = ReadInt("Введите натуральное число больше 1: ");

// //Метод вывода натуральных чисел от N до 1:
// void NumberCount (int N)
// {
    
//     if (N == 0)     
//         return;
//     {
//         Console.Write("{0,5}", N);
//     }
//     NumberCount (N - 1);
// }

// NumberCount(N);

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }



// Задача 66: Задайте значения M и N. Напишите программу, 
// которая найдёт сумму натуральных элементов в 
// промежутке от M до N.
// M = 1; N = 15 -> 120
// M = 4; N = 8. -> 30


// int M = ReadInt("Введите число M : ");
// int N = ReadInt("Введите число N : ");

// ///Метод нахождения суммы натуральных элементов в промежутке от M до N
// void NumbersSum (int M, int N, int sum)
// {
//     if (M > N) 
//     {
//         Console.WriteLine($"Сумма натуральных элементов в промежутке от M до N: {sum}"); 
//         return;
//     }
//     sum = sum + (M++);
//     NumbersSum(M, N, sum);
// }

// NumbersSum(M, N, 0);

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }



// Задача 68: Напишите программу вычисления функции Аккермана с 
// помощью рекурсии. Даны два неотрицательных числа m и n.
// m = 2, n = 3 -> A(m,n) = 9
// m = 3, n = 2 -> A(m,n) = 29


// int m = ReadInt("Введите неотрицательное число m : ");
// int n = ReadInt("Введите неотрицательное число n : ");

// int functionAkkerman = Akk(m, n);

// Console.Write($"Функция Аккермана (Akk(m,n)) = {functionAkkerman} ");

// int Akk(int m, int n)
// {
//   if (m == 0)
//   { 
//     return n + 1;
//   }
//   if (n == 0)
//   { 
//     return Akk(m - 1, 1);
//   }
//   else
//   { 
//   return Akk(m - 1, Akk(m, n - 1));
//   }
// }

// int ReadInt(string message)
// {
//     Console.Write(message);
//     return Convert.ToInt32(Console.ReadLine());
// }