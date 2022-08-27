# Proyecto
App para catalogo, compra y venta.
Problema: Crear una aplicación para un negoción que requiere tener a dispocicion en una app el catalogo de sus productos y precios. Al mismo tiempo requiere que el usuario pueda realizar la compra en linea y esperar por el producto desde casa o poder pasar a tienda por el producto seleccionado.

Contexto: El tema de este proyecto es debido a que varios negocios pequeños o antiguos, aun no cuentan con este servicio, así que a la vez este proyecto se me hace interesante el proceso de creacion de una app con esta descripción.

Algoritmo 

Entrada :
  Palabras clava o descripcion del producto a buscar.
  Datos de pago
  Direccion de entrega 
  
Proceso:
  Pedir las Palabras clava o descripcion del producto a buscar.
  Comparar los datos ingrsados con la base de datos del catalogo donde se encuentra toda la información.
  Dar como respuesta los datos completos del producto buscado en caso de que si se encuentre en la base de datos y en caso de que no, solamneteindicar que no se encuentra lo que busca el usuario en este negocio.
  En caso positivo, dar las especificaciones del producto y proceder con el pago. Si se realiza el pago dar las opciones de entrega y fechas.
  Crear un numero de folio
  
  Salidas
  Número de folio para el seguimiento de su paquete e igual funciona para recoger su paquete en tienda.
# A partir de esta parte empieza mi codigo
def MARCAAUTO(MA):
    input("Ingresa la marca de tu auto:")
    print("En esta función compara la marca del carro correspondiente, con la base de datos.")
    
def MODELOAUTO(MODELOAUTO):
    input("Ingresa EL MODELO de tu auto:")
    print ("En esta función se compara EL MODELO DEL AUTO del carro correspondiente, con la base de datos.")
    
def AÑOAUTO(AÑOAUTO):
    input("Ingresa EL AÑO de tu auto:")
    print ("En esta función se compara EL AÑO del carro correspondiente, con la base de datos.")
    
def TIPOAUTO(TIPOAUTO):
    input("Ingresa tu TIPO DE auto:")
    print ("En esta función se compara EL TIPO DE AUTO del carro correspondiente, con la base de datos.")
     
def TRANSMISIONAUTO(TRANSMISIONAUTO):
    input("Ingresa la TRANSMISIÓN de tu auto:")
    print ("En esta función se compara la TRANSMISION del carro correspondiente, con la base de datos.")
    
def main():
    
    MA= MARCAAUTO(MARCAAUTO)
    MOA= MODELOAUTO(MODELOAUTO)
    AA= AÑOAUTO(AÑOAUTO)
    TT= TIPOAUTO(TIPOAUTO)
    TA= TRANSMISIONAUTO(TRANSMISIONAUTO)
    
    

main()
