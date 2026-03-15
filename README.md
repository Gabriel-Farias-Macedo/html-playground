Quiz Quadrado
Aplicação web de treino matemático baseada no currículo do ensino fundamental e médio brasileiro (BNCC), construída como um arquivo HTML único, sem dependências externas.
Sobre o projeto
Este projeto nasceu como uma ferramenta pessoal de estudo para treinar raciocínio matemático de forma rápida e progressiva, no estilo de flashcards. Todo o código foi desenvolvido em sessões de pair programming com IA (Claude, da Anthropic), sem framework, sem bundler, sem npm — apenas HTML, CSS e JavaScript vanilla em um único arquivo.
É um projeto vibecoded: a arquitetura, a lógica e o design foram construídos de forma iterativa através de conversa, refinando funcionalidades a cada rodada.
Funcionalidades

Conteúdos do EF e EM pela BNCC: 4 operações, inteiros, frações, decimais, potências, raízes, equações, PA/PG, juros, trigonometria, combinatória, logaritmos e mais
Seção de velocidade mental: frações equivalentes, múltiplos, divisores, expressões algébricas, lógica matemática e lógica clássica
Regra de 3 (direta, inversa, porcentagem, velocidade)
Modos: Digitar, Alternativas, Progressivo (dificuldade 1–10 automática) e Batalha (foca nos erros)
Dificuldade ajustável de 1 a 10 — números de 0 a 1 bilhão no nível máximo
Estatísticas por operação com gráficos de barras, pizza e taxa
Tema claro e escuro
Progresso salvo via localStorage
Atalhos de teclado para uso sem mouse

Como usar
Baixe o arquivo quiz-quadrado.html e abra no navegador. Não precisa de servidor, instalação ou conexão com internet.
Atalhos
TeclaAçãoEnterConfirmar resposta→Pular (sem penalidade)←Voltar à questão anterior↑ / ↓Aumentar / diminuir dificuldadeTabAlternar entre Digitar e Alternativas
Tecnologias

HTML + CSS + JavaScript puro (vanilla)
Fonte: DM Sans + DM Mono (Google Fonts)
Persistência: localStorage
Zero dependências, zero build step

Próximos passos (ideias)

 Backend em Python (Flask) com banco de dados real
 Login e histórico entre dispositivos
 Modo cronometrado
 Exportar relatório de desempenho

Licença
MIT
