<div align="center">

<img src="https://img.shields.io/badge/Toyota-TechLearn-E60012?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMDAgMTAwIj48cmVjdCB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgcng9IjIyIiBmaWxsPSIjRTYwMDEyIi8+PHRleHQgeT0iLjllbSIgZm9udC1zaXplPSI4MCIgeD0iMTAiIGZpbGw9IndoaXRlIj5UPC90ZXh0Pjwvc3ZnPg==&logoColor=white" alt="Toyota TechLearn"/>

# 🏭 Toyota TechLearn

**Plataforma de treinamento técnico para colaboradores da Toyota Motor**

[![Status](https://img.shields.io/badge/status-protótipo-orange?style=flat-square)](https://damascobruno.github.io/Projeto_TechLearn/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-online-brightgreen?style=flat-square&logo=github)](https://damascobruno.github.io/Projeto_TechLearn/)
[![HTML](https://img.shields.io/badge/HTML-100%25-E34F26?style=flat-square&logo=html5&logoColor=white)](.)
[![Licença](https://img.shields.io/badge/uso-interno-blueviolet?style=flat-square)](.)

[🔗 Ver Demo ao Vivo](https://damascobruno.github.io/Projeto_TechLearn/) · [📄 Relatório do Projeto](#) · [🐛 Reportar Bug](https://github.com/DamascoBruno/Projeto_TechLearn/issues)

</div>

---

## 📋 Sobre o Projeto

O **Toyota TechLearn** é uma plataforma web de treinamento técnico desenvolvida para capacitar colaboradores da área de **Automação Industrial** da Toyota Motor. O projeto nasceu da necessidade de tornar o aprendizado técnico mais dinâmico, gamificado e acessível — tanto no computador quanto no celular, inclusive em ambientes com sinal de internet instável.

> 💡 *Projeto desenvolvido como iniciativa interna para digitalizar e modernizar o processo de treinamento de aprendizes e técnicos da linha de produção.*

---

## ✨ Funcionalidades

### 👨‍🔧 Perfil do Aprendiz
- **Login com matrícula Toyota** (`TY-XXXXX`) para identificação real do colaborador
- **Foto de perfil** via câmera do celular ou galeria
- **Dashboard de progresso** por módulo com barras visuais
- **Pontuação e ranking** em tempo real
- **Sistema de conquistas** (badges desbloqueáveis)

### 📖 Módulos de Estudo
| # | Módulo | Conteúdo |
|---|--------|----------|
| 01 | 🦺 Segurança no Trabalho | EPIs, NR-10, NR-12, LOTO, emergências |
| 02 | ⚙️ Linguagem Ladder | Rungs, contatos, bobinas, temporizadores, contadores |
| 03 | 💻 Programação em C | Tipos, estruturas de controle, ponteiros, embarcados |
| 04 | 🤖 CLP Toyota | Programação de CLPs, I/O, comunicação industrial |
| 05 | 🏭 Toyota Way | Kaizen, Kiken Yochi, Yoshi Yoshi, Genchi Genbutsu, 3Ms |

Cada módulo conta com:
- 📚 **Aula interativa** com conteúdo rico (tabelas, código, cards, highlights)
- 🃏 **Flashcards** com flip animado para revisão rápida
- 🎯 **Quiz** com pontuação, feedback imediato e confete ao acertar
- 🎮 **Desafios interativos** com timer e gamificação

### 👨‍💼 Painel do Supervisor
- **Dashboard** com métricas do setor em tempo real
- **Gestão de aprendizes** com progresso individual
- **Banco de questões** — adicionar/remover perguntas dos quizzes
- **Relatório PDF** profissional com KPIs e tabela de desempenho
- **Exportação CSV** para análise em planilhas

### 📱 Mobile & Offline
- **100% responsivo** — funciona em qualquer tela
- **Menu hamburger** com drawer lateral animado
- **Bottom navigation bar** para navegação rápida no celular
- **Modo offline** — progresso salvo localmente via `localStorage`
- **Banner de status** de conexão em tempo real
- **Notificações push** nativas do navegador (lembretes de treino)

---

## 🚀 Como Usar

### Acesso rápido (GitHub Pages)
Acesse diretamente pelo navegador — nenhuma instalação necessária:

```
https://damascobruno.github.io/Projeto_TechLearn/
```

### Rodar localmente
```bash
# Clone o repositório
git clone https://github.com/DamascoBruno/Projeto_TechLearn.git

# Entre na pasta
cd Projeto_TechLearn

# Abra no navegador (sem necessidade de servidor)
open index.html
# ou no Windows:
start index.html
```

### Login de demonstração
| Campo | Valor |
|-------|-------|
| Matrícula | qualquer número (ex: `04821`) |
| Senha | qualquer valor |
| Perfil | **Aprendiz** ou **Supervisor** |

---

## 🗂️ Estrutura do Projeto

```
Projeto_TechLearn/
│
├── index.html          # Aplicação completa (single-file)
└── README.md           # Este arquivo
```

> O projeto é intencionalmente construído como **single-page application em um único arquivo HTML** para facilitar a distribuição interna e o uso offline sem necessidade de servidor.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| **HTML5** | Estrutura da aplicação |
| **CSS3** | Estilização, animações, responsividade |
| **JavaScript (Vanilla)** | Lógica de negócio, gamificação, estado |
| **Google Fonts** | Syne · DM Sans · JetBrains Mono |
| **localStorage** | Persistência offline de progresso |
| **Service Worker API** | Cache para uso offline |
| **Notification API** | Lembretes push nativos |
| **FileReader API** | Upload de foto de perfil via câmera |
| **GitHub Pages** | Hospedagem gratuita |

---

## 🎮 Sistema de Gamificação

| Ação | Pontos |
|------|--------|
| ✅ Resposta correta no Quiz | +40 pts |
| 🎯 100% no Quiz de módulo | +bônus + confete |
| 🏅 Badge desbloqueado | reconhecimento |
| 📖 Módulo completo | progresso registrado |

O sistema conta com **ranking em tempo real** do setor, **pódio dos 3 melhores**, e **badges temáticos** desbloqueáveis por conquistas.

---

## 📸 Screenshots

| Tela de Login | Dashboard Aprendiz | Módulo de Estudo |
|:---:|:---:|:---:|
| *(em breve)* | *(em breve)* | *(em breve)* |

| Quiz | Ranking | Painel Supervisor |
|:---:|:---:|:---:|
| *(em breve)* | *(em breve)* | *(em breve)* |

---

## 🗺️ Roadmap

- [x] Autenticação por matrícula Toyota
- [x] 5 módulos de conteúdo completos
- [x] Sistema de quiz e flashcards
- [x] Gamificação (pontos, ranking, badges)
- [x] Design responsivo para mobile
- [x] Modo offline com localStorage
- [x] Exportação de relatórios PDF e CSV
- [x] Foto de perfil via câmera
- [x] Notificações push de lembrete
- [ ] Backend real com autenticação corporativa
- [ ] Integração com sistema RH Toyota
- [ ] Certificados digitais de conclusão
- [ ] Módulo de vídeo-aulas
- [ ] App nativo (PWA instalável)
- [ ] Painel administrativo completo

---

## 👤 Autor

**Bruno Damasco**
Colaborador · Área de Manutenção · Mecatrônica · Toyota Motor

[![GitHub](https://img.shields.io/badge/GitHub-DamascoBruno-181717?style=flat-square&logo=github)](https://github.com/DamascoBruno)

---

## 📄 Licença

Este projeto é de **uso interno** e foi desenvolvido como iniciativa pessoal para melhoria dos processos de treinamento da Toyota Motor. Não é destinado à distribuição pública.

---

<div align="center">

Feito com ❤️ para a Toyota Motor · *Kaizen — melhoria contínua*

</div>
