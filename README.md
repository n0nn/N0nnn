while True:
	zx = input("Devam etmek için bir tuşa çıkmak için q tuşuna basın..")
	if zx == "q":
		break
	else:
		user1 = input("kullanıcı adı: ")
		pswd = input("Parola: ")

uzunluk = len(user1+pswd)

msz = "Kullanıcı adı ve parolanız toplamda {} karakter içeriyor."
print(msz.format(uzunluk))
		
if user1 == "skepy" and pswd == "skepy": #if - and komutlarını kullanırken karakter dizilerinde " " işaretlerini
	print("Başarıyla giriş yaptınız.")   #kullanmayı unutmamamız gerekli.
	input("Devam etmek için bir tuşa basın...")

else:
	print("Lütfen yazdığınız verilerin doğru olup olmadığını kontrol edin.")

v1 = input("Gün\t:")
v2 = input("Gidiş\t:")
v3 = input("Dönüş\t:")

gün = int(v1)
gidiş = int(v2)
dönüş = int(v3)

masraf = gün * (gidiş+dönüş)

if gün<5:
	gün2 = str(v1)
	gün4 = str(v2)
	gün6 = str(v3)

	print("-"*len(gün2))
	print("""
Gün: {}
Gidiş: {}
Dönüş: {}""".format(gün,gidiş,dönüş),sep="")
	print("-"*len(gün6),)
	print("Masrafınız: ",masraf,sep="")

else:
	print("Yav şu üstteki varyaaa")
	gün2 = str(v1)
	gün4 = str(v2)
	gün6 = str(v3)

	print("-"*len(gün2))
	print("""
Gün: {}
Gidiş: {}
Dönüş: {}""".format(gün,gidiş,dönüş),sep="")
	print("-"*len(gün6))
	print("Masrafınız: ",masraf)

input()


