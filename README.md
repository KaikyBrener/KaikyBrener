<div align="center">

# Kaiky Brener

**Desenvolvedor em formação · TI · QA · Backend**

Vila Velha, ES · Engenharia de Software

</div>

---

## Sobre mim

Estudo Engenharia de Software e trabalho com suporte de TI, incluindo sistemas de CFTV e controle de acesso. Fora do trabalho, construo projetos próprios, principalmente backend, APIs e integração de sistemas.

**Foco atual:** C# e .NET, APIs, integração de sistemas e testes de software (QA).

## Tecnologias

| | |
|---|---|
| **Linguagens** | C#, JavaScript, TypeScript, Python, Java |
| **Backend** | ASP.NET Core, Entity Framework Core |
| **Frontend** | React, Vite, Tailwind CSS, HTML, CSS |
| **Banco de dados** | SQLite, MySQL, PostgreSQL (Supabase) |
| **Ferramentas** | Git, GitHub, Docker |

## Projetos

### [CentralHub — integração de centrais de alarme](https://github.com/KaikyBrener/Integra-o-central-de-alarmes)
MVP para cadastrar prédios e centrais de alarme, testar a conexão, enviar comandos a saídas PGM e manter o histórico. O SDK usa o padrão de adaptadores (Intelbras, JFL e um adaptador fake para testes).
`ASP.NET Core 9` · `EF Core` · `SQLite` · `React` · `TypeScript` · `Vite`

### [BioControl — controle de presença por biometria](https://github.com/KaikyBrener/BioControl)
Leitor de digital com ESP32 que funciona sem internet: a própria placa cria a rede Wi-Fi e serve um painel web para cadastrar digitais, registrar entrada e saída e exportar o histórico em CSV. O firmware é dividido em módulos, com uma máquina de estados para o cadastro e uma API REST protegida por login de administrador. Projeto em grupo do Projeto Integrador da UniSales.
`ESP32` · `C++` · `PlatformIO` · `LittleFS` · `HTML` · `CSS` · `JavaScript`

### [Phoenix — conversor de imagens e Base64](https://github.com/KaikyBrener/phoenix-64)
App web que roda no navegador: converte imagem em Base64 e vice-versa, comprime imagens para até 200 KB e guarda um histórico local das conversões.
`HTML` · `CSS` · `JavaScript`

### [ConectJovem — gestão de ministério jovem](https://github.com/KaikyBrener/Conecta-Jovem)
Sistema web mobile-first para jovens, grupos, encontros, chamada de presença, alertas de faltas consecutivas e tarefas de acompanhamento. O banco recalcula as faltas ao salvar a chamada e abre o alerta sozinho; as regras de acesso ficam no Postgres (Row Level Security).
`React 19` · `TypeScript` · `Vite` · `Tailwind CSS` · `Supabase` · `Vitest` · `Playwright`

### [Comparador de nomes](https://github.com/KaikyBrener/comparador-nomes-control-id)
Compara a lista de nomes do sistema com a do dispositivo Control ID e indica quem deve ser removido do controle de acesso. API mínima em C# com normalização de acentos e espaços e detecção de nomes parecidos.
`C#` · `ASP.NET Core`

### [PHOENIX Converter — conversor de vídeo para Windows](https://github.com/KaikyBrener/phoenix-converter)
Aplicativo desktop para converter vídeos com FFmpeg, com detecção de GPU, backup e restauração das configurações e instalador próprio. Distribuído como executável com PyInstaller e Inno Setup.
`Python` · `PySide6` · `FFmpeg` · `SQLite` · `PyInstaller` · `pytest`

### [Kaiky Assistant — assistente pessoal no Discord](https://github.com/KaikyBrener/Kaiky-Assistent)
Bot de tarefas e lembretes que roda no plano gratuito do Cloudflare Workers, usando Interactions HTTP em vez de conexão permanente. Guarda tarefas e registros de bugs no D1, envia um relatório diário pela manhã e lembra prazos automaticamente, sem notificações duplicadas.
`JavaScript` · `Cloudflare Workers` · `D1` · `Cron Triggers` · `Discord API`

Veja todos os projetos em [meus repositórios](https://github.com/KaikyBrener?tab=repositories).

## Aprendendo agora

- Testes automatizados e QA
- Boas práticas de API e arquitetura em .NET
- Docker para ambientes de desenvolvimento
