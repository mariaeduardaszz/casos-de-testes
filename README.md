Sobre o Projeto

Este repositório contém casos de teste manuais realizados em um sistema web de cadastro e login.
O objetivo foi validar funcionalidades críticas do sistema, identificar falhas e documentar bugs encontrados durante a execução dos testes.

Objetivo dos Testes

Garantir o funcionamento correto das seguintes funcionalidades:
-Login com e-mail e CPF
-Cadastro de novo usuário
-Validação de CPF
-Validação de idade mínima
-Campo Nome Social
-Navegação entre páginas

Bugs Reportados
-Bug 01 – Campo apagado ao pressionar Enter
Descrição: Ao pressionar a tecla "Enter", o sistema apaga o campo preenchido.
Impacto: Interfere no fluxo de login/cadastro.
Severidade: Baixa
Prioridade: Baixo

-Bug 02 – Inconsistência na validação de CPF
Descrição: Sistema informa que o CPF já está utilizado no cadastro, porém ao tentar realizar login com o mesmo CPF e senha, apresenta mensagem de credenciais incorretas.
Impacto: O erro impede o acesso à conta e impossibilita a candidatura à vaga de emprego, bloqueando o fluxo principal do sistema.
Severidade: Crítica
Prioridade: Alta

-Bug 03 – Delay no carregamento da página
Descrição: Página apresenta demora excessiva ao carregar.
Impacto: Prejudica a experiência do usuário.
Severidade: Baixa
Prioridade: Baixo

-Bug 04 – Botão "Próximo" não funciona ao inserir Nome Social
Descrição: Após preencher o campo Nome Social, o botão "Próximo" não permite avançar para a próxima página.
Impacto: Bloqueia o fluxo de cadastro.
Severidade: Média
Prioridade: Médio

Ambiente de Teste
-Navegador: Opera
-Teste Manual
-Ambiente Web


