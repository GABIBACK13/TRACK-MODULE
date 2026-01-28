# Módulo de Transcrição e Organização de Áudios

#### Descrição
Este módulo permite a gravação de áudios, transcrição automática via **Google AI APIs** e organização do conteúdo em arquivos de texto estruturados por data (dia, mês, etc).  

Ele é desenvolvido em **TypeScript (Node.js)**, utilizando **BullMQ** e **Redis** para processamento assíncrono, com frontend em **React + TypeScript**.

> ⚠️ Este módulo é **independente** e não faz parte dos pacotes oficiais da Aplicação.

---

#### Funcionalidades
- Gravação de áudio diretamente no navegador ou aplicativo.
- Transcrição automática usando IA do Google.
- Organização e armazenamento de textos transcritos por data.
- Processamento assíncrono e confiável com BullMQ e Redis.
- Frontend responsivo e moderno em React + TypeScript.

---

#### Tecnologias
- **Backend:** Node.js, TypeScript, BullMQ, Redis
- **APIs:** Google Text-to-Speach (transcrição de áudio) 
- **Frontend:** React, TypeScript

---

#### Instalação
```bash
# Clonar o repositório
git clone ""repo""

# Instalar dependências backend necessárias
cd backend
npm install

# Instalar dependências frontend
cd ../frontend
npm install
