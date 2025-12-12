#  Tabela automatizada de horários
## Apresentação do produto

 O projeto foi pensado em conjunto na disciplina de desenvolvimento de sistema aplicado a dados, no qual desde o princípio foi pensando a avaliação gradual a partir do conteúdo. Nesse sentido, foi convocado Aedris Neto para poder ser o objeto de discursão sobre as indagações em torno do processo do trabalho. A partir disso tivemos um mapeamento em torno da rotina de trabalho e a partir disso tivemos o alinhamento do que poderia ser melhorado a partir de um desenvolvimento de um sistema que suprar uma lacuna. O sistema foi programado pelo professor Gabriel Uzeda a partir de uma base que o mesmo já tinha em torno do seu site, no qual se encontra no seguinte link: https://uzedasolucoes.com.br/efg/alocacao.html. O site foi pensado para poder otimizar a rotina em torno dos horários dos professores no qual irá receber um CSV com o horários dos professores e vai tentar calcular o melhor horário para adicionar uma nova disciplina junto a apitidão de cada professor para poder ministrar.O projeto detalhou em cada parte como cada componente foi pensado e desenvolvido sem que haja armazenamento de dados para não acarretar no descumprimento da LGPD.  

## Como iremos implementar isso? 
Separar duas tabelas com apitidão dos professores e outra tabela com horários do professores. 
Aba para verificar o limite de horário dos professores de acordo com o limite estabelecido de hora aula 
Colocar no site um gerador de horário dos professores
Aba para coodernação
Aba para gerar aptidão
Aba para gerar horário
Em outra aba realiza a união de todos os horários e as apitidão
Restrição - Não podemos armazenar dados dos professores por conta da LGPD


## Requisitos
### Funcionais
- Não pode armazenar dados no banco de dados.
- Interfase simples
- Não precisa de usuário e senha
- Três abas diferentes, sendo uma para gerar o horário do professor, outra para gerar apitidão e última para realizar a comparação da duas tabelas
- Especificar a matéria faltante 

### Não funcionais 
- Campo para anexar todos os CSVs de uma vez
- 
- 


