## Comandos NPM

### Versão e Configuração do Projeto
- Versão do NPM: `npm -v`
- Criar projeto: `npm init`
- Criar projeto mais rápido: `npm init -y`
- Configurar módulo: `npm config set [atributo]`
- Exibe valores de configuração: `npm get`
- Excluir valores de configuração: `npm config delete [atributo]`
- Verificar scripts do projeto: `npm run`

### Instalação de Pacotes
- Instalar pacote: `npm install [pacote]`
- Instalar pacote como Dev: `npm install [pacote] --save-dev`
- Instalar pacote Global: `npm install [pacote] -g`
- Instalar pacote sem adicionar dependência: `npm install [pacote] --no-save`
- Linkar pacotes globais com local: `npm link [pacote]`
- Remover pacote Global: `npm remove [pacote] -g`
- Listar dependências: `npm list --depth=0`
- Listar dependências global: `npm list -g`
- Remover pacotes de node_modules não utilizados: `npm prune`
- Procurar por atualizações de pacote: `npm outdated`
- Atualizar pacotes: `npm update`
- Remover pacotes: `npm uninstall [pacote]`
- Remover redundância de dependências: `npm dedupe`

### Informações de Pacotes
- Procurar pacotes no NPM: `npm search [nome do pacote]`
- Visualizar informações: `npm view [pacote]`
- Acessar documentação: `npm docs [pacote]`
- Acessar home: `npm home [pacote]`

### Cache
- Verificar cache: `npm cache verify`
- LImpar cache: `npm cache clean --force`

### Segurança
- Auditoria: `npm audit`
- Correção: `npm audit fix --force`

### Npx
- Execução de pacotes: `npx cowsay -d "Mensagem" (executa o pacote cowsay)`
- Checar atualização de dependências: `npx npm-check-updates`