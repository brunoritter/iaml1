# IA e Machine Learning - Material Didático

Este repositório contém material educacional para aprendizado prático de conceitos fundamentais de Machine Learning, desenvolvido especificamente para o curso de IA e Machine Learning.

## Sobre o Curso

**Instituição:** Harve - Florianópolis  
**Professor:** Bruno Ritter  
**Foco:** Aplicação prática de algoritmos de ML com Python

## Objetivo

O material foi desenvolvido para ser usado em aulas presenciais, fornecendo:
- Exemplos práticos e executáveis
- Análise exploratória de dados estruturada
- Comparação de diferentes abordagens de modelagem
- Foco em métricas de erro como guia para melhorias

## Estrutura do Projeto

```
iaml1/
│
├── notebook.ipynb          # Notebook principal com todo o conteúdo
├── data/
│   └── raw/
│       └── titanic.csv     # Dataset utilizado nas análises
└── README.md              # Este arquivo
```


## Tutorial Git + VS Code

### Instalação Inicial

1. **Instalar Git:**
   - Windows: Baixe de [git-scm.com](https://git-scm.com/)
   - Mantenha as configurações padrão durante a instalação

2. **Configurar Git (primeira vez):**
   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu.email@exemplo.com"
   ```

3. **Extensões recomendadas para VS Code:**
   - **Git Graph** - Visualiza histórico de commits
   - **GitLens** - Informações detalhadas do Git inline

### Fluxo de Trabalho no VS Code

#### Obtendo o Projeto
1. `Ctrl+Shift+P` → "Git: Clone"
2. Cole a URL do repositório
3. Escolha pasta de destino
4. Abra o projeto clonado

#### Fazendo Alterações
1. Edite os arquivos normalmente
2. Na aba **Source Control** (`Ctrl+Shift+G`):
   - Arquivos modificados aparecem em "Changes"
   - Clique no `+` para adicionar ao stage
   - Digite uma mensagem de commit
   - Clique em "✓ Commit"

#### Sincronizando com GitHub
- **Pull (baixar mudanças):** `Ctrl+Shift+P` → "Git: Pull"
- **Push (enviar mudanças):** `Ctrl+Shift+P` → "Git: Push"
- Ou use os ícones na barra de status

#### Trabalhando com Branches
1. **Criar branch:** `Ctrl+Shift+P` → "Git: Create Branch"
2. **Trocar branch:** Clique no nome da branch na barra de status
3. **Merge:** `Ctrl+Shift+P` → "Git: Merge Branch"

#### Visualizando Histórico
- **Git Graph:** `Ctrl+Shift+P` → "Git Graph: View Git Graph"
- **GitLens:** Hover sobre linhas de código para ver histórico

### Comandos Git Essenciais (Terminal)

```bash
# Verificar status
git status

# Adicionar arquivos
git add .                    # Todos os arquivos
git add arquivo.py          # Arquivo específico

# Fazer commit
git commit -m "Mensagem descritiva"

# Enviar para GitHub
git push origin main

# Baixar mudanças
git pull origin main

# Ver histórico
git log --oneline

# Criar e trocar branch
git checkout -b nova-branch
git checkout main           # Voltar para main
```

### Dicas VS Code + Git

1. **Explorer Git:** Use `Ctrl+Shift+G` para ver mudanças visuais
2. **Diff inline:** Clique em arquivos modificados para ver diferenças
3. **Undo:** `Ctrl+Z` funciona mesmo após commits (com cuidado!)
4. **Git Graph:** Visualize o histórico graficamente
5. **Commit template:** Use mensagens claras como "Adiciona análise de outliers"

### Problemas Comuns

**Erro de autenticação:**
- Configure Personal Access Token no GitHub
- Settings → Developer Settings → Personal Access Tokens

**Conflitos de merge:**
- VS Code mostra conflitos visualmente
- Escolha "Accept Current Change" ou "Accept Incoming Change"
- Ou edite manualmente e faça commit

**Arquivo muito grande:**
- Use `.gitignore` para excluir datasets grandes
- Considere Git LFS para arquivos > 100MB

## Contribuições

Este é um material educacional aberto. Sugestões e melhorias são bem-vindas através de:
- Issues para reportar problemas
- Pull requests para melhorias
- Discussões para novas ideias

## Licença

Este material é disponibilizado para fins **educacionais e não-comerciais**.

### Atribuição Obrigatória:
Ao usar este material, cite:
> "Material didático desenvolvido por Bruno Ritter para o curso de IA e Machine Learning - Harve, Florianópolis"

## Sobre o Autor

**Professor Bruno Ritter**  
Especialista em Machine Learning e Ciência de Dados  
Harve - Florianópolis, SC

---

**Nota:** Este repositório faz parte de um conjunto de materiais educacionais para ensino de Machine Learning com foco prático e didático.
