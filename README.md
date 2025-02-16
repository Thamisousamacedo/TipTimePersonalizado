
Este é um aplicativo Android criado em Kotlin utilizando Jetpack Compose. Ele calcula uma gorjeta personalizada com base no valor da conta e na porcentagem escolhida pelo usuário. As funcionalidades incluem:

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



