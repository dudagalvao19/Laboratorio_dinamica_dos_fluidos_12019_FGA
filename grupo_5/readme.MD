Grupo 5:
- Maria Eduarda B. Galvão - 16/0046947
- Carlos Yan - 13/0105333
- Daniel Moreira Carreira - 15/0122438

### 1.	Início:

**1.1 Integrantes do grupo**<br />
⦁	Maria Eduarda Galvão - 16/0046947<br />
⦁	Carlos Yan de Souza Gomes - 13/0105333<br />
⦁	Daniel Moreira Carreira - 15/0122438<br />


**1.2 Tema escolhido: Placa de orifício**<br />
Sobre o funcionamento das placas de orifício, DELMÉE, 1983, define:<br />
“O princípio de funcionamento de uma placa de orifício consiste em introduzir uma restrição localizada na tubulação onde a medição deve ser feita. Essa restrição, no caso, é provocada por um orifício feito em uma placa de pouca espessura adequadamente colocada no tubo, de maneira a obrigar o fluxo a mudar de velocidade e, em consequência, provocar um diferencial de pressões que, devidamente medido e interpretado, é representativo da vazão”.<br />
O escoamento de fluidos através de restrições ou orifícios, em medidores de vazão do tipo pressão diferencial, constitui uma classe particular de problemas em dinâmica de fluidos. A função da placa de orifício, é criar um diferencial de pressão, que seja relacionado à vazão e aos parâmetros próprios da placa de orifício.<br />

**1.3 Objetivo do experimento** <br />
O objetivo do experimento é analisar o comportamento estático e dinâmico do escoamento de um fluido conhecido através de placas de orifício concêntricas e juntamente pretende-se obter valores para velocidade média, número de Reynolds e coeficiente de vazão. 

**1.4 Escopo do experimento** <br />
Executar o experimento segundo a norma ABNT NBR ISO 5167-2.<br />
Serão obtidos valores de vazão provenientes da análise das seções a montante e a jusante da placa juntamente com os diferenciais de pressão aplicando as equações de continuidade e Bernoulli.  Dessa maneira, a partir dos dados obtidos serão calculados os parâmetros de  número de Reynolds e de coeficiente de vazão,  representados pelas equações (1.1) e (1.2) respectivamente.<br /><br />
Equação (1.1): <br />![Equação (1.1)](https://github.com/dudagalvao19/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/8b44a7803bf156089d9c3f35385b30d45e644ada/grupo_5/CodeCogsEqn.png)<br /><br />
Equação (1.2): <br />![Equação (1.2)](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/CodeCogsEqn%20(1).png)<br />

Onde:<br />


Qd = Coeficiente de vazão:<br>
Qo= Vazão volumétrica (m³/s)<br>
Ad = Área do duto (m²);<br />
Re = Número de Reynolds baseado no diâmetro do orifício;<br />
d = Diâmetro do orifício (m);<br />
v = Viscosidade cinemática do fluido;<br />
A= Área do orifício.<br>

Após verificar os resultados teóricos obtidos a partir das equações serão realizados os procedimentos experimentais. Para isto utilizaremos os recursos do laboratório de Termofluido para a execução do experimento, sendo necessário a bancada de fluxo, tubos para medição de pressão e demais equipamentos que podem se tornar necessário durante a execução. <br />
Assim, será possível verificar resultados da vazão teórica esperada e da vazão real obtida.<br />

### 2.	Planejamento e Preparação:<br />
Entre os medidores de vazão mais antigos e mais utilizados atualmente estão os medidores do tipo pressão diferencial, onde pode-se estimar que 70% dos medidores de vazão instalados no mundo sejam do tipo pressão diferencial, distribuídos entre placas de orifício, venturis e bocais de fluxo (Lomas [1]).<br />
As placas de orifício são muito utilizadas por oferecerem uma medição de vazão confiável e precisa na aplicação de vapor, líquido e gases. A manutenção e instalação deste tipo de medidores de vazão são simples e econômicas  pois não há a necessidade de encaixes, tubulações de impulso, válvulas e manômetros, sendo fornecido apenas um conjunto embalado em um único dispositivo para uma instalação simplificada.<br /><br>
**2.1 Funcionamento do medidor de vazão do tipo Placa de orifício<br />**
O fluido percorre a tubulação homogênea de maneira constante até se aproximar ao local onde a placa de orifício está instalada, primeiramente há um pequeno aumento na pressão e, logo após há uma súbita queda após a passagem pelo orifício. A pressão continua a cair até atingir um ponto de pressão mínimo chamado "vena contracta". Após este posto a pressão começa novamente a subir até atingir a pressão máxima após a placa.  Sabe-se que a pressão final medida após a passagem pela placa orifício sempre será menor que a pressão inicial do fluido antes de passar pela placa. Essa diferença de pressão é chamada de "perda de carga". Essa perda de carga significa uma energia perdida devido a restrição imposta na linha pela placa.<br />
É possível observar o fenômeno de perda de carga a partir da "figura 1" abaixo:<br>
Figura 1:"Funcionamento Placa de Orifício" <br>![Figura 1](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/f21.jpg)<br>
Além disso, tem-se que a redução da pressão do fluido quando o mesmo passa pela placa explica-se pelo aumento de sua velocidade passando pela área reduzida da placa. O fluído que passa pela tubulação tende a querer passar pelo orifício que possui a área reduzida. Dessa maneira, o fluido é acelerado, causando a diminuição da pressão.<br /><br>
**2.2 Procedimento numérico:<br />**
Um dos objetivos do presente experimento é calcular o coeficiente de vazão do medidor de pressão do tipo placa de orifício. Sabe-se que Cq = vazão real / vazão teórica. Podemos calcular a vazão teórica aplicando a equação derivada de bernoulli, considerando o fluido que escoa na tubulação como uma fluído ideal, ou seja, com viscosidade nula, portanto sem perda de carga. 
A partir da equação derivada de bernoulli temos:<br>
Equação (2.1):<br>![Equação 2.1](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/729f9eba2a0a44baf9d6decae0f3d1090113edb4/grupo_5/ber%20ofc.png)<br>
Nesta equação já foram simplificadas as cargas potenciais, já que trabalha-se, neste caso, num plano horizontal sem variação de energia potencial. 
Reorganizando a equação simplificada de bernoulli temos:<br>
Equação (2.2):<br>![Equação 2.2](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/reor%20be.png)<br>
Agora, a partir da equação manométrica, pode-se calcular o valor do diferencial da pressão:<br>
A equação manométrica é na realidade , a aplicação das leis de Stevin e de Pascal. Ela nos fornece de forma simplificada, um caminho para calcular o diferencial de dois pontos em um escoamento a partir de um diferencial de altura de um fluido manométrico. No caso do experimento em questão, o diferencial da altura será obtido em um manomêtro diferencial em formato "U".
Obtém-se então os valores de (P2-P1) a seguir:<br>
Equação(2.3):<br>![Equação 2.3](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/MANO.png)<br>
Agora,  a partir da equação da continuidade é possível obter uma relação entre as velocidades presentes na Equação (2.2).<br>
A equação da continuidade expressa uma lei de conservação que relaciona a velocidade de escoamento de um fluido e a área disponível para tal escoamento. Utilizando a equação da continuidade e, já simplificando para o caso de escoamento incompressível temos:<br>
Equação(2.4):<br>![Equação 2.4](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/cont.png)<br>
Observa-se que para o caso do medidor de pressão placa de orifício, os valores a serem calculados no ponto "2", não correspodem ao local onde está instalada a placa de orifício. A partir da Figura 2 pode-se observar que a menor área onde o fluido percorrerá durante o escoamento não é a área do orifício da placa, e sim uma área definida como área contraída. Essa área contraída é difícil de se determinar numericamente e ela é representada na figura abaixo localizado no diâmetro  "D2":<br>
Figura 2:"Posicionamento Placa de orifício"<br>![Figura 2](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/explica%20de%20acodo%20d2%20d0.png)<br>
Logo, obtém -se  a partir das Equações (2.2), (2.3) e (2.4) um valor de velocidade teórica no ponto 2 , sugeridos na Equação(2.5)a seguir:<br>
Equação(2.5):<br>![Equação 2.5](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/master/grupo_5/v2teofin.png)<br>
Finalizando, para se obter o coeficiente de vazão será utilizada uma relação entre a vazão real, já fornecido pelo experimento e a velocidade teórica temos:<br>
Equação(2.6):<br>![Equação 2.6](https://github.com/lgnsparda/Laboratorio_dinamica_dos_fluidos_12019_FGA/blob/729f9eba2a0a44baf9d6decae0f3d1090113edb4/grupo_5/CodeCogsEqn%20(1).png)<br>
Onde :<br>
A= é a área do orifício da placa.<br><br>

**2.3 Procedimentos experimentais:**<br>
⦁Estimativa do tempo necessário para a montagem e execução do procedimento:<br>
Tempo estimado para ligar a bancada deixando-a pronta para a execução do experimento: 15 minutos são necessários para conferir a ligação eletrica da bomba, verificar o nível de fluido no reservatório e abrir o registro da linha a ser realizada o experimento.<br>
Tempo estimado para execução do experimento e coleta de dados: 20 minutos para que seja ligado a bomba, o escoamento seja uniformizado no tubo sem apresentar entradas de ar e coleta dos dados de pressão.<br>
Tempo estimado para desligar a bancada e voltar as ferramentas utilizadas para os locais de origem: 15 minutos reservados para organizar a bancada e deixá-la como estava antes de iniciarmos o experimento.<br>
Tempo total do experimento: 50min.<br><br>
⦁Membro do grupo responsável pelo procedimento de montagem e execução:<br>
Carlos Yan<br><br>
⦁Cronograma estimado para a montagem e realização do experimento completo:<br>
-Identificação da bancada - HD98B;<br>
-Verificar a tensão de funcionamento da bomba (110/220v);<br>
-Identificar qual linha de fluxo será utilizada no experimento;<br> 
-Abrir o registro somente da linha que será utilizada;<br>
-Identificar o sentido do fluxo;<br>
-Verificar o nível de fluido de trabalho no reservatório, neste caso utilizaremos como fluido de trabalho a água;<br>
-Verificar as tomadas de pressão, a jusante e a montante da placa;<br>
-Tomar as medidas dos seguintes componentes:<br>
-Diâmetro interno e externo do tubo:<br> 
Externo - 32mm <br>
Interno -  29mm<br>
-Distância de tomada de pressão:<br>
A montante - 153 mm <br>
A jusante - 137 mm <br>
-Distância de tomada de pressão para a placa de orifício :<br>
A montante - 5mm <br>
A jusante - 5mm <br>
-Dimensão da placa de orifício (este, devido a não poder desmontar a bancada para aferirmos a dimensão utilizando paquímetro iremos realizar o experimento e dos resultados obtidos saber o valor do diâmetro interno da placa de orifício.)<br>
-Monitorar o tempo de funcionamento utilizando um cronômetro observando a pressão de saída do fluxo após a placa de orifício para posteriormente os resultados experimentais serem comparado com os resultados analiticos.<br>
-Coletar os dados de pressão a montante e a jusante da placa para realizar os cálculos das variáveis a serem encontradas. <br><br>
⦁Dados a serem calculados:<br>
-Diâmetro da placa de orifício.<br>
-Coeficiente de vazão.<br>
-Número de Reynolds. <br>














### 3.	Execução:

### 4.	Análise e conclusão:
