<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-escuro.svg">
  <img src="assets/banner-claro.svg" width="100%" alt="Luiz Guilherme dos Santos. Desenvolvimento, automação e IA assistiva. UFMT, Grupo Vivart e FATA, Cuiabá, MT.">
</picture>

<br>
<br>

Sou estudante de Ciência da Computação na UFMT e técnico em Mecatrônica, em Cuiabá. Trabalho com desenvolvimento e automação no Grupo Vivart e pesquiso IA para educação inclusiva: síntese e clonagem de voz em português e os robôs educacionais OTTO e BITI.

### Hoje

- **Desenvolvedor no Grupo Vivart.** Faço os portais internos do financeiro, do comercial, do relacionamento e do marketing, o app de totem dos empreendimentos e as automações em n8n que ligam ERP, CRM, WhatsApp e SharePoint.
- **Pesquisador no FATA.** Desenvolvo os módulos de IA e cuido da eletrônica e da mecânica dos robôs OTTO e BITI, usados na alfabetização de crianças com TEA e TDAH.
- **Presidente do CACOMP**, o centro acadêmico de Computação da UFMT, e vice-presidente da Atlética AAAIC Trojan.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divisor-escuro.svg">
  <img src="assets/divisor-claro.svg" width="100%" alt="">
</picture>

### Projetos

<table>
<tr>
<td width="50%" valign="top">

**[timao-api](https://github.com/luizgsantos-dev/timao-api)** <sub>· Go</sub>

API aberta sobre o Corinthians, do masculino às Brabas. Um importador monta o banco SQLite com dados do Wikidata, da Wikipédia, do RSSSF e do openfootball, e cada registro aponta para a fonte de onde veio.

`net/http` `SQLite` `OpenAPI 3.1` `Docker`

</td>
<td width="50%" valign="top">

**[ic-assistente](https://github.com/luizgsantos-dev/ic-assistente)** <sub>· Python</sub>

Assistente do Instituto de Computação da UFMT. Responde só com o que está nos documentos oficiais, cita a fonte e, quando não encontra, diz que não sabe. Usa busca híbrida (vetorial e textual) e uma bateria de testes que mede acerto e alucinação.

`PostgreSQL` `pgvector` `bge-m3` `Claude API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Renomeador de comprovantes](https://github.com/luizgsantos-dev/Renomear)** <sub>· Python</sub>

Vigia uma pasta, lê comprovantes bancários em PDF do Itaú e do Inter, extrai data, recebedor e valor e arquiva cada arquivo renomeado no padrão da empresa. O que ele não reconhece vai para revisão sem travar a fila.

`pdfplumber` `pytest` `PyInstaller`

</td>
<td width="50%" valign="top">

**[Encurtador de links](https://github.com/luizgsantos-dev/Encurtador-de-Link-com-Qr-code)** <sub>· Python</sub>

Encurtador self-hosted com destino editável, QR code, montador de UTM e estatística de clique por dia, dispositivo e origem. Cada equipe só enxerga os links do próprio grupo.

`FastAPI` `PostgreSQL` `Nginx` `Docker Compose`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Armários do IC](https://github.com/luizgsantos-dev/gerenciar-armarios)** <sub>· TypeScript</sub>

Reserva dos armários do Instituto de Computação, feita para o CACOMP. O estudante anexa o comprovante do Pix, a diretoria aprova pelo painel, e dois cliques no mesmo armário ao mesmo tempo não viram duas reservas.

`Next.js 16` `Prisma` `SQLite` `Docker`

</td>
<td width="50%" valign="top">

**[Robô OTTO](https://github.com/ottoUFMT/OTTO_Project)** <sub>· C++</sub>

Robô educacional open source da UFMT, com expressões em matriz de LED, leitor RFID, áudio e quatro servos. Trabalhei na refatoração do firmware, nos esquemas eletrônicos e na documentação.

`Arduino` `C++` `Modelagem 3D`

</td>
</tr>
</table>

Também tem o [swift-ios-labs](https://github.com/luizgsantos-dev/swift-ios-labs), com os experimentos em SwiftUI do Hackatruck (OCR com Vision, síntese de voz e LLM respondendo em JSON), e o [Blink](https://github.com/LucasLimaT/Blink), projeto final do programa, feito em equipe, em que integrei o modelo Core ML ao app.

### Fora do GitHub público

Quase tudo o que faço na Vivart fica em repositórios privados. Alguns exemplos:

- **Portais internos** em TypeScript: envio de boletos por WhatsApp e e-mail com confirmação de recebimento, painel de desempenho de SDRs e corretores, disparos pela API oficial da Meta e central de links do marketing.
- **App de totem** em Flutter para os empreendimentos, com pesquisa de satisfação do atendimento.
- **Arena Vivart**, sistema de reservas da quadra de tênis do Shopping Estação Cuiabá.
- **Automações em n8n**: rastreamento da origem dos leads, alerta de tempo de atendimento e atendimento com IA no WhatsApp.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divisor-escuro.svg">
  <img src="assets/divisor-claro.svg" width="100%" alt="">
</picture>

### Publicações

**Clonagem de Voz por IA para o Português Brasileiro em Contexto Assistivo: Desafios Comparativos em Cinco Ferramentas de Síntese de Fala**<br>
<sub>**L. G. dos Santos**, N. Borges, M. Sales, L. C. L. F. Borges, T. R. Kempner, E. P. S. Nunes · STIL 2026 · [doi:10.5753/stil.2026.26551](https://doi.org/10.5753/stil.2026.26551)</sub><br>
Compara cinco ferramentas de síntese de fala em português com um corpus de 170 gravações. Somar um dataset multilíngue de fonemas ao StyleTTS 2 melhorou a qualidade fonética regional.

**Vozes Familiares: O Potencial da Clonagem de Voz por IA para Acessibilidade na Educação Inclusiva**<br>
<sub>**L. G. dos Santos**, L. C. L. F. Borges, T. R. Kempner, E. P. S. Nunes · ERI-MT 2025 · [doi:10.5753/eri-mt.2025.17200](https://doi.org/10.5753/eri-mt.2025.17200)</sub><br>
Analisa a viabilidade da clonagem de voz como recurso de acessibilidade na educação inclusiva.

**Otimização da Arquitetura de IA: Mais Eficiência e Menos Impacto Ambiental**<br>
<sub>**L. G. dos Santos**, H. R. P. Carneiro · ERSI-MT 2025 · [doi:10.5753/ersimt.2025.8821](https://doi.org/10.5753/ersimt.2025.8821)</sub><br>
Revisão sistemática sobre Green AI e estratégias para deixar LLMs mais eficientes.

### Stack

<table>
<tr>
<td><b>Linguagens</b></td>
<td>
<img alt="Python" src="https://img.shields.io/badge/Python-1B2330?style=flat-square&logo=python&logoColor=FFD43B">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1B2330?style=flat-square&logo=typescript&logoColor=3178C6">
<img alt="Go" src="https://img.shields.io/badge/Go-1B2330?style=flat-square&logo=go&logoColor=00ADD8">
<img alt="Dart" src="https://img.shields.io/badge/Dart-1B2330?style=flat-square&logo=dart&logoColor=29B6F6">
<img alt="Swift" src="https://img.shields.io/badge/Swift-1B2330?style=flat-square&logo=swift&logoColor=F05138">
<img alt="C++" src="https://img.shields.io/badge/C%2B%2B-1B2330?style=flat-square&logo=cplusplus&logoColor=659AD2">
<img alt="Java" src="https://img.shields.io/badge/Java-1B2330?style=flat-square&logo=openjdk&logoColor=ED8B00">
</td>
</tr>
<tr>
<td><b>Web e mobile</b></td>
<td>
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-1B2330?style=flat-square&logo=fastapi&logoColor=05998B">
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-1B2330?style=flat-square&logo=nextdotjs&logoColor=FFFFFF">
<img alt="React" src="https://img.shields.io/badge/React-1B2330?style=flat-square&logo=react&logoColor=61DAFB">
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-1B2330?style=flat-square&logo=tailwindcss&logoColor=38BDF8">
<img alt="Prisma" src="https://img.shields.io/badge/Prisma-1B2330?style=flat-square&logo=prisma&logoColor=FFFFFF">
<img alt="Flutter" src="https://img.shields.io/badge/Flutter-1B2330?style=flat-square&logo=flutter&logoColor=47C5FB">
</td>
</tr>
<tr>
<td><b>Dados e IA</b></td>
<td>
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-1B2330?style=flat-square&logo=postgresql&logoColor=699ECA">
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-1B2330?style=flat-square&logo=mysql&logoColor=5B9BD5">
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-1B2330?style=flat-square&logo=sqlite&logoColor=7CC5E8">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-1B2330?style=flat-square&logo=mongodb&logoColor=47A248">
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-1B2330?style=flat-square&logo=langchain&logoColor=FFFFFF">
</td>
</tr>
<tr>
<td><b>Infra</b></td>
<td>
<img alt="Docker" src="https://img.shields.io/badge/Docker-1B2330?style=flat-square&logo=docker&logoColor=2496ED">
<img alt="Nginx" src="https://img.shields.io/badge/Nginx-1B2330?style=flat-square&logo=nginx&logoColor=1FA855">
<img alt="Linux" src="https://img.shields.io/badge/Linux-1B2330?style=flat-square&logo=linux&logoColor=FCC624">
<img alt="Git" src="https://img.shields.io/badge/Git-1B2330?style=flat-square&logo=git&logoColor=F05032">
<img alt="Grafana" src="https://img.shields.io/badge/Grafana-1B2330?style=flat-square&logo=grafana&logoColor=F46800">
<img alt="Fortigate" src="https://img.shields.io/badge/Fortigate-1B2330?style=flat-square&logo=fortinet&logoColor=EE3124">
<img alt="Windows Server" src="https://img.shields.io/badge/Windows_Server-1B2330?style=flat-square">
<img alt="Active Directory" src="https://img.shields.io/badge/Active_Directory-1B2330?style=flat-square">
</td>
</tr>
<tr>
<td><b>Automação</b></td>
<td>
<img alt="n8n" src="https://img.shields.io/badge/n8n-1B2330?style=flat-square&logo=n8n&logoColor=EA4B71">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-1B2330?style=flat-square&logo=whatsapp&logoColor=25D366">
<img alt="ClickUp" src="https://img.shields.io/badge/ClickUp-1B2330?style=flat-square&logo=clickup&logoColor=9B8CFF">
<img alt="Baserow" src="https://img.shields.io/badge/Baserow-1B2330?style=flat-square&logo=baserow&logoColor=5190EF">
<img alt="SharePoint" src="https://img.shields.io/badge/SharePoint-1B2330?style=flat-square">
</td>
</tr>
<tr>
<td><b>Hardware e design</b></td>
<td>
<img alt="Arduino" src="https://img.shields.io/badge/Arduino-1B2330?style=flat-square&logo=arduino&logoColor=00B5BE">
<img alt="Figma" src="https://img.shields.io/badge/Figma-1B2330?style=flat-square&logo=figma&logoColor=F24E1E">
</td>
</tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divisor-escuro.svg">
  <img src="assets/divisor-claro.svg" width="100%" alt="">
</picture>

### Contato

<p>
<a href="https://www.linkedin.com/in/luizgsantos-dev/"><img src="assets/contato-linkedin.svg" width="260" alt="LinkedIn: in/luizgsantos-dev"></a>
<a href="mailto:luizgdsantos91@gmail.com"><img src="assets/contato-email.svg" width="260" alt="E-mail: luizgdsantos91@gmail.com"></a>
<a href="https://lattes.cnpq.br/8232203480408493"><img src="assets/contato-lattes.svg" width="260" alt="Currículo Lattes no CNPq"></a>
</p>
