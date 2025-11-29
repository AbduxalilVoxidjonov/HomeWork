# HomeWork
// 1 masala.

Console.WriteLine("Raidusni kiriting: ");

double radius = Convert.ToDouble(Console.ReadLine());

double area = Math.PI * Math.Pow(radius, 2);

Console.WriteLine($"Aylananing yuzi: {area}");

double aylana = 2  Math.PI  radius;

Console.WriteLine($"Aylananing uzunligi: {aylana}");

// 2 masala.

Console.WriteLine("Qiymat kiriting: ");

int qiymat = Convert.ToInt16(Console.ReadLine());

Console.WriteLine("Convert Summa kiriting: ");

int summa = Convert.ToInt16(Console.ReadLine());

Console.WriteLine($"Summasi :{summa * qiymat}");

// 3 masala.

Console.WriteLine("Yoshni kiriting: ");

int yosh = Convert.ToInt16(Console.ReadLine());

Console.WriteLine($"Kunlar soni:{365*yosh} ");
