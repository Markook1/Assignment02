using System;

class Program
{
    static void Main(string[] args)
    {
        float R1, G1, B1, R2, G2, B2, R3, G3, B3, R4, G4, B4, R, G, B, A1, A2, A3, A4, L, W;

        Console.WriteLine("please enter length and width of rectangle:");
        string[] dimensions = Console.ReadLine().Split();
        L = float.Parse(dimensions[0]);
        W = float.Parse(dimensions[1]);

        Console.WriteLine("please enter the first colour values:");
        string[] color1 = Console.ReadLine().Split();
        R1 = float.Parse(color1[0]);
        G1 = float.Parse(color1[1]);
        B1 = float.Parse(color1[2]);

        Console.WriteLine("please enter the second colour values:");
        string[] color2 = Console.ReadLine().Split();
        R2 = float.Parse(color2[0]);
        G2 = float.Parse(color2[1]);
        B2 = float.Parse(color2[2]);

        Console.WriteLine("please enter the third colour values:");
        string[] color3 = Console.ReadLine().Split();
        R3 = float.Parse(color3[0]);
        G3 = float.Parse(color3[1]);
        B3 = float.Parse(color3[2]);

        Console.WriteLine("please enter the fourth colour values:");
        string[] color4 = Console.ReadLine().Split();
        R4 = float.Parse(color4[0]);
        G4 = float.Parse(color4[1]);
        B4 = float.Parse(color4[2]);

        // calculating areas
        A1 = (1 - L) * (1 - W);
        A2 = L * W;
        A3 = (1 - L) * (1 - W);
        A4 = L * W;

        // calculating R G B
        R = (R1 * A1) + (R2 * A2) + (R3 * A3) + (R4 * A4);
        G = (G1 * A1) + (G2 * A2) + (G3 * A3) + (G4 * A4);
        B = (B1 * A1) + (B2 * A2) + (B3 * A3) + (B4 * A4);

        Console.WriteLine("The values of R, G, B are: {0}, {1}, {2}", R, G, B);
    }
}
