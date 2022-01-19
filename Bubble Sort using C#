using System;
namespace BubbleSort {
   class MySort {
      static void Main(string[] args) {
         int[] array = { 67, 87, 32, 0, 94, 53};
         int temp_var;
         for (int j = 0; j <= array.Length - 2; j++) {
            for (int i = 0; i <= array.Length - 2; i++) {
               if (array[i] > array[i + 1]) {
                  temp_var= array[i + 1];
                  array[i + 1] = array[i];
                  array[i] = temp_var;
               }
            }
         }
         Console.WriteLine("The bubble sorted list is:");
         foreach (int i in array)
            Console.Write(i + " ");
         Console.Read();
      }}}