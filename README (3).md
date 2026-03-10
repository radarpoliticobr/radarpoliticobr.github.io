# 🔍 RadarPolítico BR

> **Transparência pública e fiscalização municipal brasileira — powered by Claude AI**

[![GitHub Pages](https://img.shields.io/badge/🌐_Site-radarpoliticobr.github.io-00e5ff?style=flat-square)](https://radarpoliticobr.github.io)
[![Feito com](https://img.shields.io/badge/Powered_by-Claude_AI-ff6b35?style=flat-square)](https://anthropic.com)
[![Licença](https://img.shields.io/badge/Licença-MIT-green?style=flat-square)](#licença)

---

## 📌 Sobre o Projeto

O **RadarPolítico BR** é uma ferramenta de inteligência pública que permite pesquisar políticos, analisar prefeituras e visualizar dados eleitorais de forma rápida e acessível — tudo em uma única página, sem instalação.

Utiliza a API da Anthropic (Claude) para gerar análises em tempo real com base em dados públicos brasileiros: TSE, CGU, TCU, Ficha Limpa, IBGE e pesquisas eleitorais.

---

## 🚀 Funcionalidades

### 👤 Políticos
- Pesquise qualquer político por nome, cargo e estado
- Visualize score de risco, processos, patrimônio declarado e histórico político
- Alertas automáticos para fichas com irregularidades documentadas
- Busca com web search em tempo real

### 🏙️ Prefeitura
- Análise completa de qualquer município brasileiro
- Dados do prefeito, vice, vereadores investigados
- Licitações suspeitas, obras paralisadas, contratos irregulares
- Score de risco municipal (0–100) com gráficos de distribuição de gastos

### 🗺️ Mapa da Corrupção
- Mapa interativo do Brasil com índice de risco por estado
- Filtragem por nível de risco e região
- Ranking de capitais — maior e menor risco
- Análise de IA por cidade ao clicar no mapa

### 🗳️ Eleições 2026
- Cenário presidencial com intenções de voto (1º e 2º turno)
- Favoritos por estado no mapa interativo
- Governadores, senadores e deputados federais com scores de integridade
- Alertas 🚨 para candidatos com alta intenção de voto e baixo score
- Botão **⚡ Atualizar com IA** — busca pesquisas em tempo real

---

## 🔑 Como Usar

1. Acesse **[radarpoliticobr.github.io](https://radarpoliticobr.github.io)**
2. Insira sua **chave da API Claude** no campo no topo da página
3. Pesquise à vontade — cada análise usa sua própria chave

> 💡 **Não tem chave?** Crie gratuitamente em [console.anthropic.com/keys](https://console.anthropic.com/settings/keys)

---

## 🔒 Privacidade & Segurança

- **Sua chave nunca sai do seu navegador** — vai diretamente da sua máquina para a API da Anthropic via HTTPS
- **Nenhum servidor intermediário** — zero backend, zero banco de dados
- **Modelo BYOK** *(Bring Your Own Key)* — cada usuário arca com o custo do próprio uso
- A chave é armazenada apenas na sessão atual (`sessionStorage`) e apagada ao fechar a aba

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 / CSS3 / JavaScript puro | Interface completa sem frameworks |
| [Claude API (Sonnet 4)](https://anthropic.com) | Análises de IA + web search |
| SVG | Mapas interativos do Brasil |
| Chart.js | Gráficos de distribuição de gastos |
| GitHub Pages | Hospedagem gratuita |

---

## 📊 Fontes de Dados

As análises geradas pela IA são baseadas em dados de:

- **TSE** — Tribunal Superior Eleitoral (candidaturas, patrimônio)
- **CGU** — Controladoria-Geral da União
- **TCU** — Tribunal de Contas da União
- **IBGE** — Dados demográficos e econômicos municipais
- **Ficha Limpa** — Lei Complementar nº 135/2010
- **Datafolha / Quaest / AtlasIntel** — Pesquisas eleitorais 2026
- **Portal da Transparência** — Gastos públicos federais

> ⚠️ Os dados são gerados por IA com base em informações públicas disponíveis. Sempre verifique nas fontes oficiais antes de tomar decisões.

---

## ⚙️ Rodando Localmente

Nenhuma instalação necessária. Basta abrir o arquivo:

```bash
# Clone o repositório
git clone https://github.com/radarpoliticobr/radar-politico-br.git

# Abra o arquivo no navegador
open radar-politico-br.html
```

> **Nota:** Algumas funcionalidades de API podem requerer um servidor local por restrições de CORS. Use `Live Server` no VS Code ou `python -m http.server 8080`.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Algumas ideias:

- [ ] Adicionar mais cidades ao banco de dados
- [ ] Integrar dados oficiais via APIs abertas (Portal Transparência, SICONFI)
- [ ] Histórico de pesquisas salvo localmente
- [ ] Versão mobile nativa (PWA)
- [ ] Comparador de candidatos lado a lado

Para contribuir:
1. Fork o repositório
2. Crie uma branch (`git checkout -b feature/minha-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona funcionalidade X'`)
4. Push para a branch (`git push origin feature/minha-funcionalidade`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## ⚠️ Aviso Legal

Este projeto é de **fins educacionais e informativos**. As análises geradas pela IA são baseadas em dados públicos e podem conter imprecisões. Não nos responsabilizamos pelo uso indevido das informações. Sempre consulte as fontes oficiais para decisões importantes.

---

<div align="center">
  <sub>Desenvolvido com 🇧🇷 e ☕ · Powered by Claude AI</sub>
</div>
