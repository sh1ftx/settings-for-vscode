<<<<<<< HEAD
# Documentação das Configurações de Personalização do Visual Studio Code

Essa documentação apresenta as configurações personalizadas do Visual Studio Code que melhoram a experiência de desenvolvimento do usuário, aumentando a produtividade e personalizando o ambiente de trabalho.

## Estrutura do Arquivo

O arquivo de configuração tem um formato JSON e contém diversas entradas que controlam aspectos visuais, funcionais e comportamentais do editor.

### Configurações Principais:

1. *Visual e Layout do Editor*
   - "workbench.sidebar.location": "left": Define a localização da barra lateral à esquerda, facilitando o acesso a arquivos e pastas.
   - "editor.fontfamily": "fira code": Altera a fonte do editor para 'Fira Code', uma fonte projetada para programação, que oferece legibilidade e suporte a ligaduras.
   - Exibição do título da janela: 
     - "window.titlebarstyle": "hidden": Oculta a barra de título padrão do sistema operacional.
     - "window.title": "${activeeditorshort}": Define o título da janela para mostrar apenas o nome do arquivo ativo.

2. *Configurações do Editor*
   - "editor.fontsize": 15: Define o tamanho da fonte do editor.
   - "editor.lineheight": 1.8: Altera a altura da linha para melhor legibilidade.
   - "editor.tabsize": 2: Define o tamanho da tabulação para 2 espaços, favorecendo a padronização de código.
   - "editor.minimap.enabled": false: Desativa o minimap para uma aparência mais limpa.
   - "editor.snippets": Personalização de snippets para facilitar a inserção de símbolos matemáticos.

3. *Extensões e Funcionalidades*
   - "eslint.validate": ["javascript", "javascriptreact", "graphql"]: Integração com ESLint, uma ferramenta para identificar e corrigir problemas no código.
   - "code-runner.runinterminal": true: Permite que o código seja executado no terminal integrado.
   - Configurações relacionadas ao Tailwind CSS e Emmet.

4. *Controle de Arquivos e Pastas*
   - "files.exclude": Especifica quais arquivos e pastas não devem ser exibidos no explorer, mantendo a organização.
   - "files.associations": Define associações de arquivos específicos, como .env para dotenv e .prettierrc para json, facilitando o trabalho com diferentes tipos de arquivos.

5. *Integração com Git*
   - "git.openrepositoryinparentfolders": "always": Abre repositórios Git em pastas pai, facilitando o acesso.
   - "gitlens.codelens.recentchange.enabled": false: Desativa a janela de informações de mudanças recentes, para um ambiente mais limpo.

6. *Terminal Integrado*
   - "terminal.integrated.defaultprofile.osx": "fish": Define o shell padrão para Fish no macOS.
   - "terminal.integrated.fontsize": 14: Define o tamanho da fonte no terminal.
   - "terminal.integrated.showexitalert": false: Oculta o alerta de saída do terminal, evitando interrupções.

## Temas e Extensões Recomendadas

Para aproveitar ao máximo as configurações personalizadas, algumas extensões e temas essenciais devem ser instalados:

- *Extensões*
  - *Prettier*: Para formatação de código.
  - *ESLint*: Para linting e correção de código JavaScript.
  - *GitLens*: Para melhorar a funcionalidade do Git dentro do VSCode.
  - *Tailwind CSS IntelliSense*: Para suporte a autocompletar e dicas no desenvolvimento com Tailwind.

- *Temas*
  - *Styx*: Um tema escuro e atraente para um visual elegante e moderno.

## Importância da Personalização

Personalizar seu ambiente de desenvolvimento é fundamental para criar um espaço que se adapte ao seu estilo de trabalho. Um ambiente confortável não só melhora a produtividade como também torna o processo de codificação mais agradável. Com as configurações apresentadas, o usuário pode atender suas preferências pessoais, evitando distrações e focando no que realmente importa: o desenvolvimento de software de qualidade.

## Conclusão

Este guia resume as configurações de personalização do Visual Studio Code, destacando como essas escolhas impactam positivamente a experiência de desenvolvimento. Ajustar seu ambiente à sua maneira é um passo essencial para se tornar um programador mais eficiente e satisfeito com seu trabalho. Se precisar de mais personalizações ou suporte, não hesite em explorar a rica biblioteca de extensões e temas disponíveis no Marketplace do Visual Studio Code.
=======
# script-json-para-personaliza-o-do-ambiente-do-Visual-Studio-Code
Quer codar em um ambiente mais bonito, limpo, minimalista e agradável? Basta usar o atalho de teclado: Ctrl + Shift + P em seu vscode e depois inserir o código do repositório no arquivo aberto.
>>>>>>> 3380247d56843361af1dfd2d9c9f26c96df42fff
