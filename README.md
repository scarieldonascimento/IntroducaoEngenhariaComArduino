# IntroducaoEngenhariaComArduino
 esse repositorio e para estudo

------------------------ 
# Introdução
Aula 01: Apresentação do Curso
O professor explicou o formato do curso, detalhando como ele funciona, os tópicos que serão abordados e a forma de aprendizado que será aplicada.

Aula 02: Compra de Materiais
Foi discutido onde adquirir os materiais necessários para as atividades práticas. Optei por focar na AliExpress, por ser uma opção comum e confiável para esse tipo de compra.

Aula 03: Conhecendo o Simulador Tinkercad
Nesta aula, foi apresentada a ferramenta Tinkercad, um simulador online para projetos eletrônicos. Também foi solicitado que os alunos criassem uma conta para começar a utilizá-lo.

![image](https://github.com/user-attachments/assets/c0501151-9eef-4eed-b9ea-e5d226b1f17c)

------------------------------
# Componentes Básicos

Este módulo oferece uma introdução à eletrônica básica, abordando tanto o uso do Tinkercad quanto o funcionamento dos principais componentes. Ele ajuda os alunos a se familiarizarem com a ferramenta e com conceitos essenciais.

# LED, Resistor e Botão

Nesta aula, aprendemos:
As funcionalidades do LED e a voltagem necessária para seu funcionamento correto.
Como configurar um resistor para evitar que o LED queime devido ao excesso de corrente.
O funcionamento do botão, explicando como ele permite ou interrompe a passagem de voltagem no circuito.
O módulo combina teoria e prática, tornando mais fácil entender os fundamentos da eletrônica e aplicá-los no simulador.


add uma imagem aqui

--------------------


# Protoboard 

Essa aula nos ensina com funciona a protoboard e seus benefcios dentre eles:
Benefícios da Protoboard

Sem Solda: Permite montar circuitos sem precisar soldar.
Reutilizável: Pode ser usada várias vezes para diferentes projetos.
Fácil Montagem: Montar e desmontar circuitos rapidamente.
Flexível: Suporta diversos componentes eletrônicos.
Ótima para Aprender: Ideal para estudantes visualizarem circuitos.
Integração: Funciona bem com Arduino e outros microcontroladores.
Redução de Erros: Ajuda a testar e corrigir projetos antes do PCB.

![image](https://github.com/user-attachments/assets/a2a16150-bf43-432b-b718-0d32554c522f)

--------------------

# Jumpers barras e pinos

Essa aula foi uma breve explicação sobre oque são jumpers barras e pinos 

Benefícios dos Jumpers

Facilita a ligação de componentes em protoboards e microcontroladores.
Permite ajustes rápidos em conexões sem necessidade de solda.
Disponíveis em diferentes tamanhos e tipos (macho-macho, macho-fêmea, fêmea-fêmea).
Benefícios das Barras

Ideal para distribuir energia ou sinal em circuitos.
Facilita a organização de conexões em protoboards ou PCBs.
Pode ser cortada ou ajustada conforme a necessidade do projeto.
Benefícios dos Pinos

Funciona como ponto de conexão para jumpers e outros componentes.
Facilita o encaixe de cabos e conectores em sistemas eletrônicos.
Disponível em diferentes tamanhos e materiais, garantindo durabilidade.


-------------------
# Interruptores 

Essa aula explica oque são os interruptores e sua diferenças com os buttoes 
interuptor liga e desliga
butao manter pressionado

Diferença entre Interruptor Comum e DIP Switch

Interruptor Comum: Usado em casa ou na indústria, como para ligar ou desligar luzes.
Tem um único botão maior e é fácil de operar.
Controla a energia elétrica de forma simples.


DIP Switch: Usado em eletrônicos, como placas-mãe ou Arduino.
É pequeno, com vários botõezinhos que podem ser ligados ou desligados.
Serve para configurar dispositivos ou ajustar funções específicas.
Resumo:
O interruptor comum é maior e controla energia, enquanto o DIP switch é pequeno e usado para configurações.

![image](https://github.com/user-attachments/assets/596b7ec0-4722-4098-a546-4bdd5c927cc0)


--------------------------------------

# Potenciometro

Um potenciômetro é um tipo de resistor ajustável que controla o fluxo de corrente elétrica em um circuito. 
Ele possui um botão ou alavanca que você pode girar para aumentar ou diminuir a resistência, ajustando coisas 
como o volume de um som, a intensidade de uma luz ou a velocidade de um motor. 
É muito usado em controles manuais e dispositivos eletrônicos.

- calculo de tensão
  
![image](https://github.com/user-attachments/assets/076c3393-41b9-4e0f-8b9c-e0f1505b3ef1)


- potenciometro


  ![image](https://github.com/user-attachments/assets/1c632f00-fc3b-4231-9719-45c4b3711a6e)


-------------


# Diodo
Um diodo é um componente eletrônico que permite a passagem de corrente elétrica em apenas uma direção, bloqueando no sentido contrário.

Benefícios:

Evita danos em circuitos ao impedir correntes reversas.
Usado para retificar corrente alternada (transformá-la em corrente contínua).
Protege componentes contra sobrecargas e polarização reversa.
Funciona em diversas aplicações, como carregadores, fontes de energia e LEDs.



![image](https://github.com/user-attachments/assets/356344d0-5cbb-433e-b09b-01fa732a232c)


# Transistor

O transistor de junção bipolar (TJB ou BJT - Bipolar Junction Transistor) é um componente eletrônico muito usado em circuitos de amplificação e chaveamento. Ele é chamado de "bipolar" porque o funcionamento depende do movimento de dois tipos de portadores de carga: elétrons (carga negativa) e lacunas (carga positiva).

Estrutura Básica
O TJB é formado por três camadas de material semicondutor dopado, dispostas em uma sequência que pode ser NPN ou PNP:

Emissor (E): É fortemente dopado e emite os portadores de carga (elétrons ou lacunas) para a base.
Base (B): É muito fina e levemente dopada. Ela controla a quantidade de corrente que flui do emissor para o coletor.
Coletor (C): Moderadamente dopado e maior em tamanho, coleta os portadores de carga vindos do emissor.
Funcionamento
O TJB tem dois estados principais:

Amplificação de sinal: Pequenas variações de corrente na base resultam em grandes variações na corrente entre o emissor e o coletor. Isso permite amplificar sinais elétricos.
Chaveamento: O transistor pode ser usado como uma chave, ficando "ligado" (saturação) ou "desligado" (corte) dependendo do sinal na base.
Configurações do TJB
Os transistores podem ser usados em três configurações principais, dependendo da aplicação:

Base comum: Oferece alta tensão de saída.
Coletor comum (seguidor de emissor): Oferece alta corrente e é usado para adaptar impedâncias.
Emissor comum: Mais utilizado para amplificação de sinais.
Diferença entre NPN e PNP
No NPN, o fluxo de corrente é de elétrons e geralmente é ativado com um sinal positivo na base.
No PNP, o fluxo de corrente é de lacunas e é ativado com um sinal negativo na base.


![image](https://github.com/user-attachments/assets/182299be-753c-42c4-9264-720ae888764b)

------------------------------------------------------



# Introdução a Programação com Arduino
--------------------------

# variaveis , tipos de dados , Constantes 

- uma variavel é um rotulo que faz referencia a um local de memoria do hardware.
- Ajudam a ler e escrever valores na memória através de um nome dados pelo programador.
- o nome nao pode ter espaços nem caracteres especiais nem inicar com um numero.
- cada variavel deve ter um tipo especifico.
- cada tipo define como o dado poderá ser tratado pelo programa.
  


















