# Python-Hesap-Makinesi
Python ile tasarlanmış (Toplama,Çıkarma,Bölme,Çarpma ve Faktoriyel) Hesaplayabilen Uygulama.
//////////



print("Bu Program Rıdvan Can Gizli tarafından yapılmıştır.")

print(" Merhaba Hesap Makinesi Uygulamamıza Hoşgeldiniz!!\n")

print( " Toplama(1)\n","Çıkarma(2)\n","Bölme(3)\n","Çarpma(4)\n","Faktoriyel(5)\n")

while (True):


   soru= int(input("\nÜstteki İşlemlerden Herhangi Bir Rakamı Giriniz:\n"))


   if soru == 1:
      sayi1 = int(input("Lütfen İlk Rakamı Giriniz"))
      sayi2 = int(input("Lütfen İkinci Rakamı Giriniz:"))
      toplam = (sayi1+sayi2)
      print("Toplama Sonucunuz:",toplam)


   elif soru == 2:
      sayi1 = int(input("Lütfen İlk Sayı Giriniz"))
      sayi2 = int(input("Lütfen İkinci Sayı Giriniz:"))
      toplam = (sayi1-sayi2)
      print("Çıkarma Sonucunuz:",toplam)


   elif soru == 3:
      sayi1 = int(input("Lütfen İlk Sayı Giriniz"))
      sayi2 = int(input("Lütfen İkinci Sayı Giriniz:"))
      toplam = (sayi1/sayi2)
      print("Bölme Sonucunuz:",toplam)


   elif soru == 4:
      sayi1 = int(input("Lütfen İlk Sayı Giriniz"))
      sayi2 = int(input("Lütfen İkinci Sayı Giriniz:"))
      toplam = (sayi1*sayi2)
      print("Çarpma Sonucunuz",toplam)


   elif soru == 5:
       def faktoriyel(numara):
           faktoriyel = 1
           for i in range(1, numara + 1):
               faktoriyel *= i
           print("Faktoriyel", faktoriyel)


       numara = int(input("Lütfen Bir Rakam Giriniz"))
       faktoriyel(numara)
       break

   else:
      print("Hatalı Bir İşlem Girdiniz:")




