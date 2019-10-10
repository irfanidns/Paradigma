# Paradigma
project
# Paradigma
project
>>> class Person: 
	def __init__(self, name, age): 
		self.name = name
		self.age = age

		
>>> p1 = Person("John", 36)
>>> print(p1.name)
John
>>> print(p1.age)
36
>>> 
Penjelasan : syntax diatas adalah membuat kelas bernama Person dengan objek berupa self, name dan age.
Setiap class memiliki fungsi __init yang digunakan untuk menetapkan nilai ke properti objek. 
dalam fungsi init tersebut menetapkan nilai untuk name dan age, yang kemudian akan dipanggil menggunakan self (syntax pendeklarasian).
Kemudian p1 adalah variable yang berisi pemanggilan class Person yang objeknya berisi John sebagai name dan 36 sebagai age.
Perintah print digunakan untuk menampilkan variable dan objek yang dipanggil.

>>> class Complex:
	def __init__(self, realpart, imagpart):
		self.r = realpart
		self.i = imagpart

		
>>> x = Complex(3.0, -4.5)
>>> x.r, x.i
(3.0, -4.5)

Penjelasan : syntax diatas adalah membuat kelas bernama Complex dengan objek berupa self, realpart dan imagpart.
Setiap class memiliki fungsi __init yang digunakan untuk menetapkan nilai ke properti objek.
Dalam fungsi init tersebut menetapkan nilai untuk realpart dan imagpart, yang kemudian akan dipanggil menggunakan self (syntax pendeklarasian)
dan menambahkan variable r untuk memanggil objek realpart serta variable i untuk memanggil objek imagpart. 
Kemudian x adalah variable yang berisi pemanggilan class Complex yang objeknya berisi 3.0 sebagai realpart dan -4.5 sebagai imagpart. 

>>> class Dog:
	kind = 'canine'
	def __init__(self, name):
		self.name = name

		
>>> d = Dog('Fido')
>>> e = Dog('Buddy')
>>> d.kind
'canine'
>>> e.kind
'canine'
>>> d.name
'Fido'
>>> e.name
'Buddy'


