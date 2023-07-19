# lado
programming  
import sys

def admin():
  password = input("Введите пароль:")
  if password == 'lpwave20122016':
    print('Привет, админ!')
    print('переподключение к серверу...')
    code = input("Введите пароль:")
    if code == '890 345':
      print('ок')
  else:
    print('Не верный пароль!')

while True:
  command = input(">")
  if command == 'admin':
    admin()
  elif command == 'import minecraft':
     print('minecraft is close')
     print('cmd error:4985')
  elif command == 'exit':
    sys.exit()
  else:
    print('Wrong command!')
