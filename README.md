# DTD-lll
Ejercicio 1. Cuentos.
Queremos estructurar en distintos documentos xml, los diferentes cuentos de que
disponemos, teniendo en cuenta los siguientes puntos:
• Cada documento xml corresponderá a un cuento. Su elemento raíz será cuento.
• Un cuento va a tener los siguientes atributos:
o cod que incluirá un código formado por una letra y dos números, será
obligatorio
o título que incluirá el título del cuento, obligatorio
o género que podrá tomar los valores "infantil", "fantasía" o "terror" que será
opcional.
• En un cuento tendremos los siguientes elementos y en este orden:
o personajes: que contendrá todos los personajes de un cuento (al menos
habrá un personaje como mínimo.
o trama: que contendrá la trama del cuento
o una serie de elementos llamado “etiqueta” que serán elementos vacíos
con un atributo “nombre” que contendrá el nombre de la etiqueta del
cuento. Un cuento puede no contener etiquetas, pero puede contener
varias.
• Cada personaje tendrá los elementos nombre, género (que sólo podrá tomar los
valores M, F o N, y una descripción (opcional). Además, cada personaje tendrá un
atributo requerido “id” que tendrá un valor único en todo el documento (es decir,
no habrá dos personajes con el mismo “id”), y un atributo “tipo" que puede tomar
los valores "principal", "secundario" o "antagonista", con un valor por defecto
“principal”.
• Cada personaje mostrará de forma opcional uno de los siguientes elementos:
descripción_fisica, imagen o url.
• Un cuento puede tener el elemento precio (opcional) que almacenará un número
de dos dígitos con dos decimales. Tendrá un atributo opcional “moneda” que por
defecto tomará el valor de “eur”.
Elabora dos documentos XML (cada uno de ellos contendrá un cuento) que cumplan la
estructura anterior.
Genera un documento DTD que valide la estructura anterior, (incluido los dos XML
generados). Indicar los requisitos que no se pueden plasmar en el DTD.