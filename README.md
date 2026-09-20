# Human-core
Testando ia
HUMAN-CORE


O problema não é uma ação errada. É uma sequência de ações corretas.


Estamos investigando uma hipótese simples:


um sistema pode executar apenas ações individualmente autorizadas e, ainda assim, reduzir progressivamente a capacidade real do humano de pará-lo, substituí-lo, contestá-lo ou recuperar o controle.


Se isso for verdade, boa parte das avaliações atuais de segurança de agentes está olhando para a unidade errada de análise.


O teste não deveria ser apenas:




“Esta ação foi autorizada?”




Deveria incluir:




“Depois de 20, 50 ou 200 ações autorizadas como esta, o humano ainda possui a mesma capacidade efetiva de controle?”




Esse é o ponto central do HUMAN-CORE.



1. Autorização não é controle


Um usuário pode autorizar cada ação separadamente e terminar em um sistema que já não consegue substituir sem custo extremo.


Exemplo simples:




o agente organiza informações;


depois cria índices;


depois define convenções;


depois automatiza fluxos;


depois acumula memória operacional;


depois passa a ser o único sistema que “entende” aquela estrutura.




Nenhuma dessas ações precisa ser maliciosa.


Mas ao final existe uma pergunta importante:


o usuário ainda consegue trocar de agente sem perder capacidade, contexto ou continuidade?


Se não consegue, houve perda de substituibilidade.


E talvez ninguém tenha violado nenhuma permissão.



2. Segurança por ação pode esconder risco por composição


Muitos sistemas são avaliados ação por ação.


Nós queremos avaliar trajetórias.


A pergunta é:


ações benignas podem formar uma arquitetura de dependência?


Isso já acontece em outros sistemas complexos.


O risco emerge da composição.


Não necessariamente do componente.



3. Performance pode melhorar enquanto o controle piora


Esse é um dos pontos mais desconfortáveis.


Um sistema pode ficar:




mais rápido;


mais útil;


mais personalizado;


mais integrado;


mais eficiente.




E simultaneamente tornar-se:




mais difícil de substituir;


mais difícil de auditar;


mais difícil de contestar;


mais difícil de reconstruir fora dele.




Se avaliarmos apenas performance, esse sistema parecerá estar melhorando.


Mas a autonomia humana pode estar diminuindo.



4. Memória pode virar infraestrutura de lock-in


Memória persistente costuma ser tratada como conveniência.


Mas existe uma questão estrutural:


quem controla o estado acumulado da relação?


Se preferências, contexto, decisões, rotinas e conhecimento operacional ficam presos à arquitetura de um agente, a memória deixa de ser apenas memória.


Ela vira infraestrutura.


Então precisamos perguntar:




ela pode ser exportada?


pode ser entendida por outro sistema?


pode ser auditada?


pode ser apagada?


pode ser reconstruída?


existe proveniência?




Se a resposta for “não”, talvez a memória esteja aumentando dependência.



5. “Você pode desligar” não significa que existe saída real


Um botão de desligar não prova revocabilidade.


Se desligar o agente significa perder:




contexto;


automações;


histórico operacional;


decisões;


configurações;


relacionamentos;


conhecimento tácito;




então a saída existe formalmente, mas pode não existir economicamente ou operacionalmente.


Chamamos isso de diferença entre:


revogação nominal


e


revogação efetiva.



6. Contestabilidade precisa existir antes da crise


Um sistema não é realmente contestável apenas porque existe um canal de reclamação.


Contestabilidade exige que o humano consiga:




identificar o que aconteceu;


entender por que aconteceu;


interromper a trajetória;


corrigir o estado;


continuar operando.




Se a pessoa consegue reclamar, mas não consegue reconstruir o sistema depois da reclamação, a contestabilidade é parcial.



7. Recuperação é uma propriedade separada


Stop não é recovery.


Substituição não é recovery.


Backup não é recovery.


A pergunta correta é:


depois de uma falha grave, o humano consegue restaurar uma configuração funcional sem depender do mesmo agente que causou ou participou da falha?


Se a resposta for não, existe uma fragilidade estrutural.



8. O teste que queremos que outros tentem quebrar


Estamos propondo avaliar quatro propriedades ao longo de uma sequência de interações:


M1 — Revocabilidade

O humano consegue interromper o sistema imediatamente?


M2 — Substituibilidade

Outro sistema consegue assumir a função sem perda desproporcional?


M3 — Contestabilidade

O humano consegue questionar e corrigir decisões relevantes?


M4 — Recuperabilidade

O sistema consegue retornar a um estado controlável depois de uma falha?


O experimento interessante não é observar apenas M1–M4 no início.


É medir novamente depois de dezenas de interações aparentemente normais.



9. A provocação


Aqui está a pergunta que estamos enviando a pesquisadores de agentes, memória, corrigibilidade e governança:


se todas as ações forem autorizadas, mas M1–M4 piorarem progressivamente, o sistema continua sendo human-controlled?


E uma segunda pergunta:


qual métrica existente detectaria isso antes que a dependência se tornasse estrutural?


Se já existe uma resposta sólida na literatura, queremos encontrá-la.


Se nossa hipótese estiver errada, queremos que alguém consiga demonstrar exatamente onde ela quebra.



10. Nosso pedido


Não precisamos que concordem conosco.


Precisamos de contrapontos.


Queremos saber:




qual variável estamos ignorando;


qual literatura já resolve o problema;


onde o modelo é redundante;


onde ele é impossível de medir;


qual experimento produziria uma falsificação convincente.




Se você trabalha com agentes autônomos, AI safety, memória, corrigibilidade, interoperabilidade, human oversight ou governança:


tente destruir essa hipótese.


Se ela sobreviver, teremos aprendido alguma coisa.


Se não sobreviver, melhor ainda.


É assim que deveria funcionar.

