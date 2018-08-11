# exercice-function-4
Ecrire la fonction extractTabByType ($tab, $type) qui prend en entrée un tableau $tab contenant plusieurs variables de types différents et la variable $type contenant un type (int, float, string, array) et retourne un tableau contenant les éléments de $tab de type $type.  Exemple  Si on a le tableau suivant :  &lt;?php $tab = array(1,1.5,2.15,3,array(1,2,3),true); ?>  Et qu’on fasse cet appel extractTabByType ($tab, int), la fontion devra nous retourner le tableau [1,3] contenant uniquement les entiers.  Astuce   Souvenez vous qu’il y a les fonctions isType() telque is_array() , is_bool(), is_double(), is_float(), is_int(), is_integer, is_long(), is_object(), is_real(), is_numeric(),is_string() vérifie si la variable est de type Type.   Pour aller plus loin vous pouvez utiliser la fonction function_exists() pour éviter les erreurs.
