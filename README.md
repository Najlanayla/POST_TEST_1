# POST_TEST_1
# Mengambil input
#Login sederhana


nama = input("Siapa nama kamu: ")
nim = input("Berapa nim kamu: ")
password = input("Berapa password kamu: ")

# Menampilkan output
print ("Hello",nama,"Nim kamu",nim,"Pass kamu adalah",password,"6 angka")

# Berikut ini adalah contoh program Program Python untuk menghitung volume bangun ruang.

print ('Program Menghitung Volume Bangun Ruang\n')
print ('[1].Menghitung Volume Bola\n')
print ('[2].Menghitung Volume Tabung\n')
print ('[3].Menghitung Volume Limas Segitiga\n')

p= input ('Silakan Pilih Bangun Ruang yang akan dihitung : ')

if p==1: # bola
     b = "Bola" 
     print ('\nMenghitung Volume',b,) 
     print ('\nRumus Menghitung Volume',b,'= 4/3 x π xr3')
     r=input ('\nMasukkan jari-jari : ') 
     v=4/3*3,14*r*r*r 

elif p==2:  # tabung
    b = "tabung"
    print ('\nMenghitung Volume',b,)
    print ('\nRumus Menghitung Volume',b,'= luas alas x tinggi') 
    print ('\nMenghitung Luas Alas') 
    print ('Rumus Menghitung Luas Alas = phi x jari2 x jari2') 
    r=input ('\nMasukkan nilai jari-jari : ') 
    L=(22/7.0)*r*r 
    print ('\nLuas alas',b,'=',L) 
    g=input ('\nMasukkan nilai tinggi : ') 
    v=L*g

elif p==3:  # limas segitiga
    b = "Limas segitiga" 
    
    print ('\nMenghitung Volume',b,)
    print ('\nRumus Menghitung Volume',b,'= 1/3(luas alas x tinggi)')
    print ('\nMenghitung Luas Alas')
    print ('Rumus Menghitung Luas Alas = 1/2(alas x tinggi)')
    a=input ('\nMasukkan nilai alas    : ')
    t=input ('Masukkan nilai tinggi  : ')
    L=(a*t)/2.0  
else: 
    print ("pilihan tidak sesuai, Silahkan coba lagi") 
