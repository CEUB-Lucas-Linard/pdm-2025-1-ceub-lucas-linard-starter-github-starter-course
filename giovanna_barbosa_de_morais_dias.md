Principais recursos do GitHub:
Repositórios remotos: São como pastas online onde o código fica armazenado e acessível de qualquer lugar.

Pull Requests (PRs): Quando alguém faz uma mudança no código, pode criar um PR para que outra pessoa revise antes de incorporar as alterações.

Issues: Funciona como um sistema de anotações para organizar tarefas, relatar bugs e discutir melhorias.
Actions: Automatiza processos como testes e deploys, ajudando a manter o código sempre funcionando corretamente.

Forks: Se você quiser experimentar ou contribuir para um projeto sem alterar o original, pode criar uma cópia (fork) e trabalhar nela.

GitHub Pages: Permite hospedar sites simples diretamente do repositório, útil para páginas de documentação ou portfólios.




Como funciona o fluxo básico no GitHub?
Criar um repositório no GitHub para armazenar o código do projeto.




Clonar o repositório para trabalhar no código localmente, usando o comando:

sh
CopiarEditar
git clone <URL_DO_REPO>
Criar e modificar arquivos, fazendo as mudanças necessárias no projeto.
Salvar essas mudanças com um commit, que registra a nova versão:
sh
CopiarEditar
git add .  
git commit -m "Descrição das mudanças feitas"  
Enviar as mudanças para o GitHub com um push:
sh
CopiarEditar
git push origin main
