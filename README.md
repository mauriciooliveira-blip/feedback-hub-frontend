# Feedback Hub Frontend

Frontend do sistema de feedback, construído com HTML, CSS e JavaScript vanilla.

## 🚀 Deploy no Render (Static Site)

### 1. Conectar no Render
1. Acesse https://render.com
2. Clique em **New** > **Static Site**
3. Conecte seu repositório GitHub **do frontend**
4. Configure:
   - **Name**: `feedback-hub-frontend`
   - **Build Command**: `echo "Site estático - sem build"`
   - **Publish Directory**: `.`

### 2. Configurar Variáveis de Ambiente
No dashboard do Render, adicione:
```
API_URL=https://feedback-hub-backend.onrender.com/api
```

### 3. Deploy
1. Clique em **Deploy Static Site**
2. Aguarde o deploy finalizar
3. URL será: `https://feedback-hub-frontend.onrender.com`

## 📁 Estrutura de Arquivos

- `index.html` - **Com botões**: Testa API e mostra opções para continuar
- `index-auto.html` - **Automático**: Testa API e redireciona automaticamente
- `feedback_hub.html` - Aplicação completa

## 🎯 Opções de Inicialização:

### Opção 1: Com Botões (index.html)
- ✅ Testa API em background
- ✅ Mostra resultado do teste
- ✅ Botão "🚀 Entrar na Aplicação"
- ✅ Botão "⚡ Pular Teste"
- ✅ **Recomendado** para verificar se tudo funciona

### Opção 2: Automático (index-auto.html)
- ✅ Testa API em background
- ✅ Contagem regressiva (3 segundos)
- ✅ Redireciona automaticamente
- ✅ Clique para pular
- ✅ **Mais rápido** para usuários recorrentes

### Opção 3: Direto no App (feedback_hub.html)
- ✅ Vai direto para o app completo
- ✅ Sem testes ou redirecionamentos
- ✅ **Para desenvolvimento** local

## 🔧 Como Escolher a Opção:

### Para Deploy (Recomendado):
Use `index.html` - permite verificar se a API está funcionando antes de entrar no app.

### Para Desenvolvimento:
Use `feedback_hub.html` - vai direto para o app sem redirecionamentos.

### Para Usuários Frequentes:
Use `index-auto.html` - redireciona automaticamente após teste rápido.

## ✅ Status

- ✅ Múltiplas opções de inicialização
- ✅ Teste de API integrado
- ✅ Deploy como Static Site
- ✅ Conectado ao backend remoto
- ✅ Flexibilidade para diferentes usos
