# MATRIX FACTORIZATION TECHNIQUES FOR RECOMMENDER SYSTEMS
La lectura comienza mencionando que los sistemas recomendadores mas populares se suelen dividir en  item based o user based y luego nos presenta un acercamiento distinto llamado "latent factor" que nos permute usar tanto usuarios como items.

Luego se nos explica que una de las realizaciones son las que son basdas en una matriz de factorización, logrando escalabilidad y precision. En esta matriz cada item i se asocia a un vector q y cada usario a un verctor p donde su producto punto sería el rating estimado para ese usuario hacia ese item.
Y finalmente se nos describen problemas de este algoritmo y maneras de resolverlo.

En concreto me llamó la atención el problema de que un usuario puede no proveer suficientes ratings como para lograr una conclusión y se dice que se deben obtener datos de otras partes, lo que yo creo que nos lleva a un problema de privacidad. Creo que manejar información a la cual un usuario no accedió de manera explicita puede llegar a faltar enormemente a la ética. En el texto se habla de incluso pueden ser usados los movimientos del ratón.
