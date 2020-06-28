# FindMotif - detección de motivos en cadenas de ADN
Estos notebooks contienen los pasos para la proposición de motifs (motivos) candidatos dentro de un conjunto de cadenas de ADN.

Se analizará dormancy survival regulator (DosR). Este factor de transcripción regula la expresión de genes bajo condiciones hipóxicas para la turbeculosis micobacteriana. Se analizarán una serie de 15-mers para detectar los puntos de partida de los enlaces que disparan la actuación de DosR.

Es posible ejecutar desde Google Colab (también basándose en el archivo "DorR.txt"). Se encuentran dos versiones del código.
*   **MotifsDetection.ipynb**: versión con greedy search.
*   **MotifsDetection_v2.ipynb**: se adicionan seudoconteos para resolver el error de las frecuencias iguales a cero. Este método está inspirado en la aplicación de la ley de Cromwell y los seudoconteos de Laplace.


