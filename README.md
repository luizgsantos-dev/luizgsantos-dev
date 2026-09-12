# Olá, eu sou Luiz Guilherme!

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=007BFF&height=200&section=header&text=Desenvolvedor%20e%20Pesquisador%20em%20IA&fontSize=38&animation=fadeIn&fontAlignY=38&desc=UFMT%20|%20FATA%20|%20Vivart&descAlignY=55&descAlign=50" width="100%"/>
</div>

### Sobre Mim

Sou estudante de Ciência da Computação na **UFMT** e Técnico em Mecatrônica. Minha paixão é conectar software e hardware para resolver problemas reais.

- Atualmente, sou **Desenvolvedor no Grupo Vivart**, atuando em **TI e Automação de Processos**: construção de workflows com **n8n**, integrações via API (SharePoint/Graph API, ClickUp, WhatsApp), trackeamento de lead e suporte a sistemas internos.
- Também sou **Pesquisador no FATA**, desenvolvendo módulos de IA para os robôs **OTTO** e **BITI** (focados em alfabetização de crianças com TEA/TDAH).
- Responsável pelo **desenvolvimento eletrônico e mecânico** dos robôs, incluindo design de circuitos e manutenção de hardware.
- Atuo na liderança estudantil como **Presidente do Centro Acadêmico (CACOMP)** e **Vice-Presidente da Atlética (AAAIC - Trojan)**.
- Estou aprofundando estudos em **Clonagem de Voz (SVC)**, **Visão Computacional** e **Sistemas Embarcados**.
- Experiência com **integração de APIs**, **Active Directory**, **Windows Server** e **firewall Fortigate**.
- Experiência com **ERPs**, **APIs bancárias** e **CRMs**.
- **Foco:** Criar tecnologia acessível e eficiente.

---

### Projetos em Destaque

#### [Renomeador de Comprovantes](https://github.com/luizgsantos-dev/Renomear) · Python

Serviço que monitora uma pasta em segundo plano, lê comprovantes bancários em PDF, extrai data, recebedor e valor, e arquiva o arquivo já renomeado no padrão da empresa. Suporta quatro layouts — Itaú Sispag (boleto e concessionária) e Banco Inter (Pix e boleto) — através de uma camada de parsers plugável: adicionar um banco novo é escrever uma classe.

Comprovante não reconhecido não trava a fila, vai para `_REVISAR/` com os campos faltantes marcados. O monitoramento espera o arquivo estabilizar de tamanho antes de processar, para não pegar PDF ainda sendo escrito. Roda em máquina sem Python instalado, via executável standalone.

`pdfplumber` · `pypdfium2` · `openpyxl` · `pytest` · `PyInstaller`

#### [Armários do IC](https://github.com/luizgsantos-dev/gerenciar-armarios) · TypeScript

Sistema de reserva dos armários do Instituto de Computação da UFMT, feito para o CACOMP. O estudante escolhe um armário livre, anexa o comprovante do Pix e aceita o termo; a diretoria confere e aprova pelo painel. Reserva concorrente não duplica.

Sessão de admin em cookie `httpOnly` assinado, senhas com bcrypt, comprovantes servidos fora de `public/` por rota autenticada. Sobe com um `docker compose up`, com volumes persistentes e migrations idempotentes no entrypoint.

`Next.js 16` · `React 19` · `TypeScript` · `Prisma` · `Tailwind CSS 4` · `Docker` · `SQLite` · `JWT`

#### [Encurtador de Links com QR Code](https://github.com/luizgsantos-dev/Encurtador-de-Link-com-Qr-code) · Python

Encurtador self-hosted para uso corporativo: link curto com destino editável a qualquer momento, geração de QR code, UTM builder com prévia e estatísticas de clique por dia, dispositivo e referrer. Multiusuário com grupos — cada time só enxerga os próprios links.

Três containers com responsabilidades separadas: FastAPI para API e redirecionamento, PostgreSQL, e Nginx como proxy reverso e servidor do painel.

`FastAPI` · `SQLAlchemy` · `PostgreSQL` · `Docker Compose` · `Nginx` · `JWT`

#### [IC Assistant](https://github.com/luizgsantos-dev/IC-Assistant) · Python

Chat com RAG sobre documentos acadêmicos: responde dúvidas sobre processos burocráticos, aproveitamento de matérias e calendário do Instituto usando *apenas* o que está nos documentos carregados. Trocar o provedor de LLM é configuração — OpenAI, Anthropic ou Ollama local.

`LangChain` · `ChromaDB` · `FastAPI` · `sentence-transformers`

#### [Robô OTTO](https://github.com/ottoUFMT/OTTO_Project) · C++ / Arduino

Robô educacional open-source da UFMT: expressões faciais em matriz de LED, leitor RFID, teclado matricial, áudio via DFPlayer e coreografias com quatro servos. Atuei na refatoração do firmware, na revisão dos esquemas eletrônicos e na documentação técnica.

`Arduino` · `C++` · `Modelagem 3D`

#### [Swift iOS Labs](https://github.com/luizgsantos-dev/swift-ios-labs) · Swift

Experimentos em SwiftUI do programa Hackatruck (Instituto Eldorado): consumo de API com `async/await`, LLM com saída estruturada em JSON, OCR com o framework Vision e síntese de voz.

`SwiftUI` · `Vision` · `AVFoundation` · `Firebase AI`

---

### Pesquisa & Publicações

- Autor do artigo **"Vozes Familiares: O Potencial da Clonagem de Voz por IA para Acessibilidade na Educação Inclusiva"** — **ERI-MT 2025** (Encontro Regional de Informática de Mato Grosso), novembro de 2025. Estudo sobre a viabilidade da clonagem de voz como ferramenta de acessibilidade na educação inclusiva.
- Autor do artigo **"Otimização da Arquitetura de IA: Mais Eficiência e Menos Impacto Ambiental"** — **I Escola Regional de Sistemas de Informação de Mato Grosso (ERSI-MT 2025)**, abril de 2025. Revisão sistemática sobre Green AI e estratégias de otimização para LLMs.

---

### Tech Stack & Ferramentas

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/ClickUp-7B68EE?style=for-the-badge&logo=clickup&logoColor=white" />
  <img src="https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoftsharepoint&logoColor=white" />
  <img src="https://img.shields.io/badge/Baserow-7B68EE?style=for-the-badge&logo=baserow&logoColor=white" />
</div>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=luizgsantos-dev&show_icons=true&hide_border=true&count_private=true&include_all_commits=true" height="150" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=luizgsantos-dev&layout=compact&hide_border=true&count_private=true" height="150" />

</div>

---

### Vamos Conectar?

<div align="center">
  <a href="https://www.linkedin.com/in/luizgsantos-dev/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="mailto:luizgdsantos91@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" />
  </a>
  <a href="https://lattes.cnpq.br/8232203480408493">
    <img src="https://img.shields.io/badge/Lattes-Curriculo-blue?style=for-the-badge" target="_blank" />
  </a>
</div>
