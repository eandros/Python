def misiles(tirada,misiles,dificultad=5):
    bono = round(misiles/4)
    bono -= 1
    if(bono<1):
        bono = 0
    tirada+=bono
    resultado=tirada-dificultad
    dificultadTotal = dificultad + 15
    if(tirada>dificultadTotal):
        print ('Camarada, Impactaron todos los misiles, por el Padre Espacio')
    elif (tirada<dificultad):
        print ('Camarada, es una deshonra para la Unión!')
    else:
        subtotal = tirada - dificultad
        porcentajeImpactos = (subtotal * 100) / 15
        impactos = (porcentajeImpactos * misiles) / 100
        if(impactos == 0):
            if(misiles == 1):
                print ('Camarada, el misil impacto, Siga avanzando!')
            elif (misiles > 10):
                print ('Camarada, 1 misil impacto, Es una verguenza para el comunismo!')
            else:
                print ('Camarada, un misil impacto, mejore esa punteria camarada!')
        else:
            print ('Camarada, {0} misiles impactaron, Siga avanzando!'. format(round(impactos)))

def weaponSystems(tirada,dificultad,objetivos=1):
    totalObjetivos=((dificultad-tirada)/5)+1
    if(round(totalObjetivos) == 1):
        print('Camarada, usted fijo un objetivo')
    else:
        print('Camarada, usted fijo {0} objetivos'.format(round(totalObjetivos)))

