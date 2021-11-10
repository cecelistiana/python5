# python5
1. aplikasi terbilang

Source code

numbers = input("masukkan angka : ")

numbers_napping = {
    "1": "satu",
    "2": "dua",
    "3": "tiga",
    "4": "empat",
    "5": "lima",
    "6": "enam",
    "7": "tujuh",
    "8": "delapan",
    "9": "sembilan",
} 

output = " "

for n in numbers:

    terbilang = numbers_napping.get(n, "invalid")

    output = output + terbilang + " "

print(output)

vs code dan output
![p25](https://user-images.githubusercontent.com/92987122/141112043-b757f8ce-aab3-47aa-98ea-232617401475.png)

2. emoji converter

Source code
message = input(">>>")

emoji_mapping = {
    ":)": "😊",
    ":D": "😁",
    ":|": "😐",
}

words = message.split(" ")

output = " "

for w in words:

    output = output + emoji_mapping.get(w, w) + " "

print(output)

vs code dan output
![p26](https://user-images.githubusercontent.com/92987122/141112132-c5f81e7e-9b9b-424c-826b-6023dc7073fb.png)

3. fungsi

Source code

def halo_user():

    print("halo user")
    
    print("selamat belajar python")

print("start")

halo_user()

print("finish")

vs code dan output
![p27](https://user-images.githubusercontent.com/92987122/141112240-580569f8-04cf-44b9-b7a2-4fdce2804421.png)

4. parameter fungsi

Source code
def halo_user(name):

    print(f"halo {name}")
    
    print("selamat belajar python")

print("start")

halo_user("cece")

print("finish")

vs code dan output
![p28](https://user-images.githubusercontent.com/92987122/141112604-fa18f6d2-e447-4ae2-bb9a-16b5142f7400.png)

5. keyword argument

Source code

def halo_user(name, level):

    print(f"halo {name} - {level}")
    
    print("selamat belajar python")

print("start")

halo_user("cece", 10)

print("finish")

vs code dan output
![p29](https://user-images.githubusercontent.com/92987122/141112722-c684711b-6e04-4185-9782-09ecfafbfa1d.png)

6. return value

Source code

def halo_user(name, level):

    print(f"halo {name} - {level}")
    
    print("selamat belajar python")
    
    return 100

temp = halo_user("cece", 10)

print(temp) 

vs code dan output
![p30](https://user-images.githubusercontent.com/92987122/141112872-b3036710-dd08-4bee-a2a1-204514709652.png)
