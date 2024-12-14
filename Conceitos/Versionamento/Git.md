O Git surge como um modo de controlarmos as versões do nosso código, ele gerencia e rastrear alterações em projetos.
Antes de algum versionador de código existir, era usado para guardar versões de código a seguinte maneira:![[Versionamento_antigo.png]]


Suas principais características:
- **Distribuído**: Cada desenvolvedor possui uma cópia completa do repositório, incluindo o histórico completo de alterações, permitindo trabalho offline.
- **Rastreamento de alterações**: Registra cada modificação feita nos arquivos, permitindo reverter mudanças ou comparar versões.
- **Branching e Merging**: Facilita o trabalho em diferentes versões ou funcionalidades simultaneamente, com suporte robusto para unir alterações de forma segura.
- **Desempenho**: Processa operações como commits, diffs e merges rapidamente, mesmo em projetos grandes.

Seus principais comandos:
- `git init`: Inicializa um repositório Git.
- `git clone`: Faz uma cópia de um repositório existente.
- `git add`: Adiciona alterações ao estágio (staging area).
- `git commit`: Registra alterações no histórico do repositório.
- `git push`: Envia commits para um [[Repositório remoto]].
- `git pull`: Atualiza o repositório local com alterações do remoto.
- `git branch`: Gerencia ramificações.
- `git merge`: Mescla branches.
- `git log`: Registro de todas alterações de nosso repositório.
- `git commit --amend` : é usado para modificar o último commit no histórico do Git. Basicamente, ele reescreve o último commit como se fosse novo.
### Estágios de um arquivo.

- Estágio 1 - Modified
	- Acontece quando algum arquivo que já existia em dentro do seu repositório sofrer alguma modificação.
	- Ele ficara com o status Modified/Modificado.
- Estágio 2 - Staged
	- Arquivos Staged, são arquivos que estão em uma área de preparo, esses serão os arquivos que você informa para o Git que quer salva-los no seu versionamento.
- Estágio 3 - Commit
	- Esses são os arquivos que você se comprometeu de fato com o versionamento deles, está informando para o Git salvar suas mudanças e guarda-las no seu controle de versionamento.

### `.gitignore`

No Git podemos colocar tudo que não queremos que ele versione no arquivo `.gitignore`
