# Assignment-008-1-Password-Reminder-
name = str.capitalize(input("lütfen isminizi yazınız: "))
password = str(input("lütfen şifrenizi belirleyin: "))
new_user = str.capitalize(input("hoşgeldiniz lütfen isminizi giriniz: "))
if new_user == name :
    print("Hello {}!The password is: {}".format(new_user,password))
else:
    print("Hello Amina!See you later.")  
