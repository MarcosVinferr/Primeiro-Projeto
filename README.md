# Primeiro-Projeto
projeto 01

exercicio C# Wile

using System;
using System.Globalization;
class Program
{
    static void Main()
    {
        int X, soma, cont;

        X = int.Parse(Console.ReadLine());
        soma = 0;
        cont = 0;
        while (X >= 0)
        {
            soma = soma + X;
            cont = cont + 1;
            X = int.Parse(Console.ReadLine());
        }
        double media = (double)soma / cont;
        Console.WriteLine(media.ToString("f2", CultureInfo.InvariantCulture));
    }
}
