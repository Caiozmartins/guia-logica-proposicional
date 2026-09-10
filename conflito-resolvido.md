\# Conflito Resolvido



\## Situação



Foi criado um conflito controlado no arquivo `README.md`.



A branch `main` e a branch `feature/ajuste-readme` alteraram a mesma frase da seção de objetivo do projeto.



\## Conflito



Na branch `main`, o texto foi alterado para:



> Apresentar conceitos fundamentais de lógica proposicional e tabelas-verdade para estudantes iniciantes.



Na branch `feature/ajuste-readme`, o texto foi alterado para:



> Ensinar os fundamentos da lógica proposicional, dos conectivos lógicos e das tabelas-verdade.



Ao executar o merge, o Git identificou que as duas branches haviam modificado a mesma região do arquivo.



\## Decisão



Foi decidido combinar as duas versões, preservando as informações mais importantes de ambas.



A versão final escolhida foi:



> Este guia apresenta os fundamentos da lógica proposicional, dos conectivos lógicos e das tabelas-verdade para estudantes iniciantes.



\## Resolução



Os marcadores de conflito foram removidos manualmente:



\- `<<<<<<< HEAD`

\- `=======`

\- `>>>>>>> feature/ajuste-readme`



Em seguida, o arquivo foi adicionado novamente à área de preparação com `git add` e o merge foi finalizado com um novo commit.



\## Aprendizado



A atividade demonstrou como identificar, analisar e resolver manualmente conflitos de merge no Git, preservando uma versão coerente do conteúdo.

