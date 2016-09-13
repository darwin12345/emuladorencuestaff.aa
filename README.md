# -*- coding: utf-8 -*-

# emuladorencuestaff.aa

#variables

gr = "-GRACIAS"

inf = "-PARA MAS INFORMACION INGRESA A www.dscompany.com/inscripciones/ff.aa"

print ("-HOLA, BIENVENIDO AL ASISTENTE DE INSCRIPCION PARA EL SERVICIO MILITAR 2016")

saludo = raw_input()

print ("-CUAL ES TU NOMBRE:")

nombre = raw_input()

print ("-CUAL ES TU EDAD"),(nombre)

edad = int(input())

#A UTILIZAR = > < == != >=

if edad>17:

    print ("-ENTONCES ERES MAYOR DE EDAD")
    
else:

    print ("-MENOR DE EDAD")
    
#if else

if edad>17:

    if edad <30:
    
        print ("-PUEDES HACER EL SERVICIO MILITAR")
        
        print ("-HAORA QUIERO DARTE EL LUGAR EN DONDE DEBES INSCRIBIRTE DE ACUERDO A TU PAIS")
        
        print ("-INGRESE LOS 3 PRIMERAS LETRAS DE TU PAIS:")
        
        pais = raw_input()
        
        pais = pais.lower()
        
        if pais == "ecu":
        
            print("-ECUADOR: DEBES INSCIBIRTE EN QUITO")
            print(inf)
            print (gr)
        elif pais == "col":
            print("COLOMBIA: DEBES INSCRIBIRTE EN CALI")
            
            print(inf)
            
            print (gr)
            
        elif pais == "per":
        
            print("-PERU:.DEBES INSCRIBIRTE EN LIMA")
            
            print(inf)
            
            print (gr)
            
        elif pais == "mex":
        
            print ("-MEXICO: DEBES INSCRIBIRTE EN EL DISTRITO FEDERAL")
            
            print(inf)
            
            print (gr)
          
        else:
        
            print("-NO TENGO REGISTRADO TU PAIS EN MI BASE DE DATOS")
            
            print("-INGRESE EN OTRO MOMENTO")
            
            print(inf)
            
            print (gr)
            
    else:
    
        print ("-PERO YA ESTAS DEMASIADO CARCAMAL PARA HACER EL SERVICIO MILITAR")
        
        print(inf)
        
        print (gr)

else:

    print("-ERES DEMASIADO PUBERTO PARA HACER EL SERVICIO MILITAR")
    
    print("-CONSULTE SU EDAD CON SU 'IDE' DE CEDULA O PASAPORTE")
    
    print(inf)
    
    print (gr)
