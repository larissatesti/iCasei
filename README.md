# iCasei

Considere a página https://teste-qa.icasei.com.br/depoimentos. Recebemos relatos de usuários que não conseguem enviar um depoimento. De que forma você identificaria o erro e o que faria depois de identificado?


1. **De que forma você identificaria o erro:**

Primeiramente, iria reproduzir o passo-a-passo do usuário.

Entrar na página e clicar em "Enviar depoimento":

![image](https://github.com/larissatesti/iCasei/assets/99557283/4e280d23-09f7-4360-b583-cb5551af4655)

Preencher todos os campos:

![image](https://github.com/larissatesti/iCasei/assets/99557283/b7459ba7-f862-4a2b-a31c-1e9a6a2a4148)

E clicar em enviar:

![image](https://github.com/larissatesti/iCasei/assets/99557283/013b31a1-4af2-4494-9eb7-60e6cf4468a9)

Erro identificado, depoimento não está sendo enviado.
  <br/> 
  <br/> 
2. **O que faria depois de identificado**

Iria abrir a ferramenta de desenvolvedor do próprio Chrome para identificar se há erros.
Neste caso, verifiquei que a API send-testimonials está retornando erro 500 com o response {"message":"Internal Server Error"}
Assim, indica um erro interno do servidor, o que pode ser erros no código ou outras falhas.

![image](https://github.com/larissatesti/iCasei/assets/99557283/98c1f6e3-c58b-4e95-9262-e48878e01a3f)

Dessa forma, coletaria todas as evidências detalhadamente, logs, e encaminharia para equipe responsável realizar uma análise mais profunda para identificar e corrigir o problema.

*Larissa Christina Batista Testi Silva*
