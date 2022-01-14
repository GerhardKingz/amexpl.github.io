---
layout: default
---
# Registro de Ejemplares, Dueños Responsables y Criaderos.
***
[Inicio Registro](./p_registra.md) | [Dueños Responsables](./p_r_duenos.md) | [Kennel](./p_r_kennel.md) | [Ejemplares](./p_r_ejemplares.md) |

### Ahora ya puedes registrar a uno o a varios de tus ejemplares (WD - WolfDog)(deberás proporcionar el Id del Kennel o el de Dueño Responsable generados en los pasos anteriores)
<form action="http://152.70.122.144/amexpl/ins_ejemplar.php" method="post" target="_blank">
Nombre de tu WD:<br><input type="text" name="ejemplar"><br><br>
Sexo de tu WD:<br>
<input type="radio" id="Hembra" name="sexo" value="Hembra">
<label for="Hembra">Hembra</label><br>
<input type="radio" id="Macho" name="sexo" value="Macho">
<label for="Macho">Macho</label><br><br>
Fecha de Nacimiento:<br><input type="date" name="fnacim"><br><br>

Porcentaje (Contenido de sangre de Lobo):<br>
<input type="radio" id="LC" name="porcentaje" value="LC">
<label for="LC">Bajo Contenido (LowContent) 15% - 49% </label><br>
<input type="radio" id="MC" name="porcentaje" value="MC">
<label for="MC">Medio Contenido (MidContent) 50% - 74% </label><br>
<input type="radio" id="UMC" name="porcentaje" value="UMC">
<label for="UMC">Medio Alto Contenido (UpperMid) 75% - 84% </label><br>
<input type="radio" id="HC" name="porcentaje" value="HC">
<label for="HC">Alto Contenido (HighContent) 85% - 99% </label><br><br>
  
Prueba de ADN:<br>
<input type="radio" id="Embark" name="prueba" value="Embark">
<label for="Embark">Embark</label><br>
<input type="radio" id="EasyDNA" name="prueba" value="EasyDNA">
<label for="EasyDNA">EasyDNA</label><br>
<input type="radio" id="MyHeritage" name="prueba" value="MyHeritage">
<label for="MyHeritage">MyHeritage</label><br>
<input type="radio" id="WisdomPanel" name="prueba" value="WisdomPanel">
<label for="WisdomPanel">WisdomPanel</label><br>
<input type="radio" id="Otra" name="prueba" value="Otra">
<label for="Otra">Otra</label><br><br>

Número de Registro (en caso de contar con Prueba de ADN):<br><input type="text" name="regprueba" value="0"><br>
Padre (Escribe el ID en caso de contar con él, si lo desconoces, deja el 1):<br><input type="number" name="fatherid" value="1"><br>
Madre (Escribe el ID en caso de contar con él, si lo desconoces, deja el 1):<br><input type="number" name="motherid" value="1"><br>
Kennel ID (Escribe el ID en caso de contar con él, si lo desconoces, deja el 1):<br><input type="number" name="kennelid" value="1"><br>
Responsable ID (Tu número de registro como Dueño Responsable):<br><input type="number" name="responsable"><br>
Foto del Ejemplar:<br> <input type="file" name="foto"><br>
Video del Ejemplar:<br><input type="url" name="video"><br>
<input type="submit">
</form><br>

### Buscar Ejemplar
<form action="http://152.70.122.144/amexpl/bus_pet.php" method="post" target="_blank">
Registro del Ejemplar:<br><input type="text" name="pet"><br>
<input type="submit"><br><br>
</form>

[inicio](./)

***
