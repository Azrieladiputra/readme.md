![mata uang drawio](https://github.com/Azrieladiputra/readme.md/assets/144753236/69a07391-32bc-411f-a69a-6ca9554bba1c)
Program :::

## Konversi mata uang Rupiah ke USD dan sebaliknya
#Nama : Azriel adi putra
#Nim : 2309116057
#Sistem informasi kelas B

#Login
x : input("masukkan nama kalian : ")
y : input("masukkan NIM : ")
z : input("masukkan kelas : ")

def convert(before,after,total):
    #Dollar
    if before=="dollar" and after=="rupiah":
        result = total * 15000
        
        #Yen
    elif before=="Yen" and after=="rupiah":
        result = total * 103
        
        #Ringgit
    elif before=="Ringgit" and after=="rupiah":
        result = total * 3275
    
        #Dollar
    elif before=="rupiah" and after=="dollar":
        result = total / 15000 
               
        #Yen
    elif before=="rupiah" and after=="yen":
        result = total / 103
        
        #Ringgit
    elif before=="rupiah" and after=="ringgit":
        result = total / 3275
        
    return result

before = input("mata uang yang akan di konversikan (dollar, yen, ringgit, or rupiah) : ")
after = input("Dikonversi menjadi? (dollar, yen, ringgit, or rupiah) : ")
total = int(input("berapa jumlah uang : "))
final = convert(before,after,total)
print("hasil konversi : ", final)







 


   


    
    


   


    
    
