ProcesadorDeTextoAVocabularios
==============================

Trabajo práctico de TSB. La idea es que uno o varios archivos de texto sean la entrada del programa. 
Y se arme un vocabulario con todas las palabras de todos los textos procesados.

Para la lectura de las palabras, las opciones son: Caracter por Caracter, Scanner, StringTokenizer o Expresiones regulares.
La recomendada seria Scanner o StringTokenizer

Para la BD las tablas serian: Vocabulario, Palabras por Documento, y Documento

Estructura:
HashSet
HashMap   <- Elegida
HashTable

HashMap hm = new HashMap();
hm.put(key, value);
hm.put<String, MiObj>
