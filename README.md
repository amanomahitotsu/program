Console.WriteLine("---->ASTERISCOS<----");
Console.WriteLine("Introduce un numero limite de filas: ");
int n = int.Parse(Console.ReadLine());
//Generando el bucle for para la primer iteracion..
for (int i = 1; 1 <= n; i++)
{
    //Generando el bucle for para imprimir los asteriscos
    //sera desde 1 hasta "i" que es el numero de Linea actual
    for (int j = 1; j <= i; j++)
    {
        Console.WriteLine("*");
    }
    Console.WriteLine(); //Genera un salto de Linea
}

//*
//**
//***
//****
