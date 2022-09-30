# Problema 1 - Consumo de água inteligente
 Repositorio relacionado ao primeiro problema da disciplina TEC 502 Concorrência e Conectividade 202
 
 
 ## Objetivo 
 - O objetivo desse trabalho foi construir um sistema que viza automatizar a coleta de dados. Os mesmos são gerados a partir de um hidrômetro inteligente, que enviará determinadas informações para o nosso servidor.
 ## Descrição
 -- Esse sistema foi desenvolvido baseando-se na arquitetura Cliente-Servidor.
    -- Foi realizada a implementação manual de uma api rest utilizando python e sockets. Que fazia o tratamento de requisições http, recebendo e enviando dados especificos.
    
 ## Sobre as Interfaces
 * A interface do cliente deve permitir:
   * Vizualização do consumo feito de cada cliente.
   * Gerar a fatura a ser paga.
   * Alertar sobre um possível vazamento de água em determinada zona da cidade.
   * Usuários do serviço podem acessar o sistema de forma online para acompanhar o 
     consumo da água, com datas/horários específicos do consumo e o total acumulado.
 ##  
 * A interface do administrador deve permitir:
   *  O administrador poderá cortar o fornecimento de água da residência caso o usuário possua alguma conta em aberto.
   *  Caso o usuário quite o débito, o sistema deve liberar o fornecimento de água imediatamente.


 ## Conclusão e Resultados:
 - O trabalho foi desenvolvido e entregue entre 23/08 e 29/09 de 2022. Foi muito interessante o trabalho com sockets, pois, era algo que nunca tinha desenvolvido, o tratamento das requisições http também foi muito interessante, pois, podemos ver como um servidor trata das requisições.
 - Alguns pontos não foram totalmente concluidos e podem ser melhorados em próximas versões, são eles:
   - Uso do docker e portainer.
   - Respostas das requisições do Insominia. 
   - Verificar Vazamento na rede.
   - Log de vazamentos.
