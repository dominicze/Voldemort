# Voldemort
def pobierz_zdanie():
    zdanie=input('Podaj dowolnie dlugie zdanie: ')
    lista=zdanie.split(' ')
    print(lista)
    return lista
    
    '''for slowo in lista:
        print(slowo.capitalize())
    return lista'''
        

def przyjmuj_liste(lista):
    for slowo in lista:
        print(slowo.capitalize())
