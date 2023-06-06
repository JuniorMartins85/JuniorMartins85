st=>start: Definir o tema da pesquisa
e1=>operation: Definir o título da pesquisa
e2=>operation: Definir a pergunta de pesquisa
e3=>operation: Definir o objetivo da pesquisa
e4=>operation: Introdução: Justificativa

st->e1->e2->e3->e4

m1=>operation: Metodologia
m2=>operation: Definir questionário
m3=>operation: Aprovar questionário na comissão de ética
m4=>operation: Definir forma de pontuação do questionário
m5=>operation: Definir componentes do circuito do protótipo
m6=>operation: Montar circuito
m7=>operation: Programar Arduino
m8=>operation: Testar e verificar gravação
m9=>operation: Utilizar protótipo
m10=>operation: Validar protótipo
m11=>operation: Confeccionar placas com circuito aprovado
m12=>operation: Instalar nas residências dos usuários
m13=>operation: Solicitar preenchimento dos questionários
m14=>operation: Salvar datalog dos cartões de memória após uma semana de uso
m15=>operation: Realizar rodízio dos equipamentos entre as casas dos usuários
m16=>operation: Formatar dados dos questionários
m17=>operation: Analisar resultados e verificar temperatura ótima
m18=>operation: Verificar consumo de energia na temperatura definida

m1->m2->m3->m4->m5->m6->m7->m8->m9->m10->m11->m12->m13->m14->m15->m16->m17->m18

r=>operation: Resultados
r1=>operation: Analisar dados coletados entre circuito do Arduino e os questionários
r2=>operation: Criar métodos estatísticos
r3=>operation: Demonstrar consumo de energia
r4=>operation: Demonstrar preferências dos usuários

r->r1->r2->r3->r4

c=>operation: Conclusão

r4->c

b=>operation: Bibliografia

c->b
