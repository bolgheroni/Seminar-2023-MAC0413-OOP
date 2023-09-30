* Código é um passivo, não um ativo
	* Quanto mais código, mais complexidade, mais difícil de agregar valor
	* veja que o código dos testes automatizados também faz parte disso: quanto mais testes, mais complexo o sistema
* Testes automatizados: amenizam a curva de complexidade de um sistema
	* bons testes auxiliam a incrementar ou alterar a base de código 
	* testes ruins apenas aumentam a complexidade do sistema, e devem ser removidos
	* boa base de testes: 
		* proteção contra regressões
			* exercitam a maior parte do código possível
			* cobrem regras de negócio 
			* mudanças no comportamento observável do código quebram os testes
		* resistentes a refatoração
			* mudanças nos detalhes de Implementação não quebram os testes
		* fáceis de manter (baixa complexidade do código de testes)
		* executam rápido 
* como reconhecer um bom teste
* como escrever um bom teste
	* refatoração 
	* identificar o tipo de teste necessário 
	* escrever o teste
# TODO
- [ ] Listar os tópicos listados nas seções de "Conclusão" de cada capítulo (sobre testes unitários)
	eles contém resumos em tópicos sobre o conteúdo passado, perfeito pra montar slides
- [ ] Listar tópicos das minhas anotações do livro (kindle)