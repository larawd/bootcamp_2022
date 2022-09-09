{

double işlem, sayı1, sayi2, sonuc;

Console.Write("ilk sayıyı giriniz");

sayı1 = inputValue();

Console.Write("ikinci sayıyı giriniz");

sayi2 = inputValue();

Console.Write("Lütfen seç + için 1,- için 2,/ için 3,x için lütfen 4giriniz");

işlem = inputValue();

if (işlem == 1)

{

sonuc = sayı1 + sayi2;

}

else

{

if (işlem == 2)

{

if (sayı1 >= sayi2)

{

sonuc = sayı1 - sayi2;

}

else

{

sonuc = sayi2 - sayı1;

}

}

else

{

if (işlem == 3)

{

sonuc = sayı1 \* sayi2;

}

else

{

if (işlem == 4)

{

sonuc = sayı1 / sayi2;

}

}

}

}

Console.Write(sonuc);

}
