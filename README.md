Atividade do Android Developers.
Unidade 2: Interacting with UI and state

Continuação do app da calculadora Tip Time que foi personalizada com um botão de arredondar o valor.

O que aprendi:
- Como pensar sobre o estado em uma interface.
- Como o Compose usa o estado para mostrar dados.
- Como adicionar uma caixa de texto ao app.
- Como adicionar um botão de ação a um teclado virtual.
- O que é um elemento combinável Switch e como usá-lo.
- Adicionar ícones principais aos campos de texto.

As funcionalidades incluem:
1.	Tela Principal (TipTimeLayout):
o	O layout possui dois campos de entrada:
- Valor da conta: O usuário insere o valor total.
- Porcentagem da gorjeta: O usuário insere a porcentagem desejada.
- Um interruptor (Switch) permite arredondar a gorjeta para o valor inteiro mais próximo.
- O cálculo é exibido como uma gorjeta formatada na moeda local.


2.	Função de cálculo (calculateTip):
-	Calcula a gorjeta com base no valor inserido e na porcentagem definida.
-	Se o arredondamento estiver ativado, usa kotlin.math.ceil para arredondar o valor.


3.	Componentes Composables:
-	EditNumberField: Um campo de entrada estilizado com ícones e labels configuráveis.
-	RoundTheTipRow: Um layout com texto e o interruptor de arredondamento.
-	TipTimeLayout: Gerencia os estados e organiza os elementos da tela.


4.	Estilo e Navegação:
- O layout utiliza Material Design para estilização.
- Adapta-se a diferentes tamanhos de tela com scrolling e padding.


5.	Preview (@Preview):
-	Permite visualizar o layout da calculadora no Android Studio antes de rodar no dispositivo.

Confira o app nesta imagem:

![image](https://github.com/user-attachments/assets/7c55299d-048c-4549-b17d-e6b56bfb4ee3)

