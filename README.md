from random import randint
tahmin = randint(1,99)
sayac=0
dogrutahmin=False
while dogrutahmin==False:
    sayac+=1
    sayi=int(input("Bir tahminde bulununuz:"))
    if   sayi<tahmin:
         print("kucuk sayi girdiniz,,")
    elif sayi>tahmin:
         print("buyuk sayi girdiniz..")
    else:
         print("Dogru tahminde bulundunuz..")
         dogrutahmin==True  
         print("Tahmin sayiniz:{}".format(sayac))
