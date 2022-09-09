

int n, s1, s2, s3, s4;

s1 = 0;

s2 = 1;

s3 = 3;

Console.WriteLine("fibonaccinin ilk kaç terimi olsun");

n = (int) inputValue();

Console.Write(s1);

Console.Write(s2);

while (s3 <= n)

{

s4 = s1 + s2;

Console.Write(s4);

s1 = s2;

s2 = s4;

s3 = s3 + 1;

}

}

