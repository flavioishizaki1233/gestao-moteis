# Gestão dos Motéis

Sistemas de gestão para Sfera, Rio, Real e Éden:

- `/escala/`: gerador de escala de trabalho (12x36, 5x2 e 6x1).
- `/vales/`: controle de VT e VA por quinzena, com desconto das faltas e a planilha de pedido da Caju.

- Página: https://escala.sferamoteis.com.br/ (vai mudar para gestao.sferamoteis.com.br)
- Dados: Supabase (projeto `gestao-moteis`), com login por e-mail e acesso por motel.
- A demanda de limpeza e os funcionários novos vêm do Motel+ toda segunda-feira, por uma tarefa agendada no Claude.

- Os dados dos funcionários (nome completo e CPF) ficam só no Supabase, protegidos por login. Nunca coloque CPF ou planilhas do RH neste repositório, porque ele é público.
