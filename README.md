# Importância de Boas Anotações
Este é o repositório tem como intenção demonstrar a importância de boas
anotações para detecção de objeto.

# Introdução
Para treinarmos uma IA para detecção em imagens necessitamos de um conjunto
de imagens específica para um determinado problema. Existem vários bancos
de dados de imagens de forma gratuita na internet, mas será que podemos confiar?
Nesse artigo vamos abordar a importância de possuirmos anotações bem realizadas
no dataset. Para isso vamos usar imagens encontradas em dataset para detecção
de células em esfregaço sanguíneo. Os dados foram obtidos em um repositório
do roboflow e copiados para um repositório pessoal, também no roboflow,
para fins de demonstração.


# Método
Usamos a arquitetura Yolov8 para detecção de hemácia nesse trabalho.
Treinamos um modelo usando imagens com marcações não adequadas e treinamos
outro modelo usando imagens com as marcações revisadas por mim, deixando
mais próximas do que eu acho adequado.


# Como rodar
Para executar este notebook, abra-o no Google Colab e ative o suporte para GPU.
Em seguida, basta executar as células sequencialmente.