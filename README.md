# Diagrama_Guardia_Imperial
## Enunciado
El adeptus Administratum tiene un problema grave respecto a la organización del ejercito de la Guardia Imperial destinado en Cadia.<br>
Por lo tanto necesitamos un sistema para volver a organizarlos, por rangos y cargos en el planeta del sistema Cadiano, además de los vehiculos. Debemos de crear una clase *Persona*, *Vehiculo* y *regimiento* principalmente. En el que derivaremos los soldados, oficiales y estado mayor a *Persona* (estos tambien seran clases). En *Vehiculo* tenemos que crear clases relacionadas con los vehiculos blindados, ligeros y aéreos. No hay que olvidar que la clase Ingeniero es *Persona*.<br>
Varios soldados ocupan un solo regimiento, un oficial ocupa un regimiento, varios vehiculos pueden estar en un regimiento y un solo miembro del estado mayor puede dirigir a varios oficiales.<br>
Cada clase tiene unos atributos:
- **Persona:** Nombre, Apellido, Edad, Planeta de Nacimiento, Identificación
- **Soldado:** Arma
- **Oficial de regimiento:** Rango
- **Estado mayor:** Rango
- **Ingeniero:** Cargo
- **Vehiculo:** Nombre, Matricula
- **Blindado, Ligero y Aéreo:** Arsenal y Blindaje (Aéreo tiene propulsión)
- **Regimiento:** Planeta, Num. Regimiento

### Bibliografia:
[Planeta Cadia](https://warhammer40k.fandom.com/es/wiki/Cadia)<br>
[Guardia Imperial](https://warhammer40k.fandom.com/es/wiki/Guardia_Imperial)<br>
[Jerarquía de la Guardia Imperial](https://warhammer40k.fandom.com/es/wiki/Jerarqu%C3%ADa_de_la_Guardia_Imperial)<br>
[Vehiculos de la Guardia Imperial](https://warhammer40k.fandom.com/es/wiki/Categor%C3%ADa:Veh%C3%ADculos_de_la_Guardia_Imperial)<br>

## Imagen del diagrama
![guardia_imperial drawio](https://user-images.githubusercontent.com/114684233/224086542-2450df82-d1a6-468c-8c50-8422bf7fefb9.png)

### Leyenda del diagrama
- **Extense:** Quiere decir que las clases derivan de X. Por ejemplo: Soldado e Ingeniero derivan de Persona.
- **Correspondencia de cardinalidades:** Uno a Uno (1,1), Uno a Varios (1,N), Varios a Uno (N,1), Varios a Varios (N,M).
