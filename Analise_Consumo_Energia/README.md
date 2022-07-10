
## Projeto de Análise de Consumo de Energia por uma Industria de Aço.

#### Contexto do Projeto
- Desenvolvido para controlar de forma automática a irrigação de uma cisterna, mas tambem sendo possível o controle da mesma por meio de um modo manual, assim reduzindo desperdicio e custos.

#### Desenvolvimento de Problema
- Reduzindo o consumo de energia elétrica, seria uma das melhores formas de reduzir tambem, o consumo de propriedades, como a produção de Dióxido de Carbono (C02), prejudicial de diversas formas tanto a fauna como a floara de qualquer ecossistema, como também a produção de Potencia Reativa, originada de equipamento bobinados e indutivos, como Motores elétricos, que acarretam na geração de ruídos da rede elétrica (harmonicas), sendo tanto prejudicial para a consecionario que administra a rede como a própria empresa, que receberá altas taxa pela produção excessiva deste recuso. Por consequência da redução de reativos, os capacitivos que são utilizados para contrabalanceá-los, também serão reduzidos.
Portanto, podendo predizer quais vão ser os futuros valores de energia consumida, pode-se tomar medidas, de diminuí-la ou até, interrompe-la em determinados horário do dia, quando o consumo é efetuado em grande parte pelas empresas
#### Introdução:
  - O dataset a ser trabalhado é foi produzido por uma empresa de geração de diversos tipos de bobinas e chapas de aço, chapas de ferro. Com isso, foram armazenadas informações do consumo de energia elétrica, com o mesmo consumo, a tambem a geração de outras propriedades como Potencia Reativa de Corrente de Fuga (kVarh) e Potência Reativa de Corrente Principal (kVarh), assim como a produção de dióximo de carbpno (C02). Abaixo, estão todas das as Features do dataset e suas respectivas definições:

  - date -> feature de dia e hora da leitura efetuada;
  - Usage_kWh -> Consumo de energia elétrica de potência ativa (kW) no decorrer do tempo;
  - Lagging_Corrent_Reactive_Power -> Potência Reativa de Reatância Indutiva, medida em kVarh no decorrer do tempo;
  - Leading_Corrent_Reactive_Power -> Potência Reativa de Reatancia Capacitiva, medida em kVarh no decorrer do tempo;
  - CO2(tCO2) -> Dióxido de carbono, volume (ou massa) de dióxido de carbono na produção.
  - Lagging_Current_Power_Factor -> Fator de Potência de Corrente Atrasada, referente ao uso de Potência Reativa pelo sistema;
  - Leading_Current_Power_Factor -> Fator de Potência de Corrente Principal, referente ao uso de Potencia Ativa pelo sistema;
  - NSM -> Número de segundos a partir da meia-noite - unidade de medida, em S(Segundos) com intervalo de 15s;
  - WeekStatus -> Feature categórica que indica, se o registro da leitura efetuado ocorrem em Weekend (Fim de Semana) ou Weekday (Dia da Semana);
  - Day_of_week -> Feature Categórica que indica em qual dia da semana, sendo final de semana ou durante a semana;
  - Load_Type -> Feature Categoria indicado três tipo de carga para o consumo de energia elétrica.

