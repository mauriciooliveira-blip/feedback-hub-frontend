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

- `index.html` - Página inicial de teste
- `feedback_hub.html` - Aplicação completa
- `render.yaml` - Configuração do Render

## 🎯 Funcionalidades

- ✅ Página de login/cadastro
- ✅ Dashboard com gráficos
- ✅ Sistema de feedback
- ✅ Relatórios
- ✅ Perfil do usuário
- ✅ Configurações
- ✅ Modo escuro

## 🔧 Configuração

A aplicação está configurada para funcionar com:
- **Backend**: `https://feedback-hub-backend.onrender.com/api`
- **CORS**: Habilitado para todas as origens
- **Responsivo**: Funciona em desktop e mobile

## 📱 Como Usar

1. Acesse `https://feedback-hub-frontend.onrender.com`
2. Será redirecionado para `feedback_hub.html` (app completo)
3. Faça login ou cadastre-se
4. Use todas as funcionalidades

## ✅ Status

- ✅ Deploy como Static Site no Render
- ✅ Conectado ao backend remoto
- ✅ Página de teste funcional
- ✅ Aplicação completa integrada
