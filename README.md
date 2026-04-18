# 🧹 StockFlow — Sistema de Estoque de Material de Limpeza

Sistema web de gestão de estoque para material de limpeza, com suporte a múltiplas lojas, movimentações, inventário e alertas.

## ✨ Funcionalidades

- **Dashboard** com métricas em tempo real (total em estoque, valor, alertas)
- **Estoque** com filtros por loja, categoria e status
- **Movimentações** — registro de entradas, saídas e transferências (atualiza o estoque ao vivo)
- **Inventário** — contagem física com cálculo automático de divergências
- **Transferência** entre lojas com validação de estoque disponível
- **Alertas** automáticos para itens abaixo do estoque mínimo
- **Relatórios** (6 tipos)
- Busca global por produto/código
- Notificações toast

## 🚀 Como usar

Não há dependências externas nem build necessário.

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/stockflow.git
cd stockflow

# Abra diretamente no navegador
open index.html
```

Ou acesse via qualquer servidor HTTP estático (ex: VS Code Live Server, Nginx, GitHub Pages).

## 📁 Estrutura

```
stockflow/
└── index.html   # Aplicação completa (HTML + CSS + JS em arquivo único)
```

## 🛠 Stack

- **HTML5 / CSS3 / JavaScript** — vanilla, sem frameworks
- **Google Fonts** — DM Sans + DM Mono
- Sem dependências de terceiros

## 📦 Dados

Os dados são simulados em memória (array JS). Para conectar a um backend real, substitua os arrays `PRODUTOS`, `ESTOQUE` e `MOVIMENTACOES` por chamadas `fetch()` à sua API.

## 🔜 Próximos passos sugeridos

- [ ] Persistência com `localStorage` ou backend (Node/Laravel/etc.)
- [ ] Autenticação de usuários
- [ ] Exportação de relatórios em PDF/Excel
- [ ] Gráficos de consumo por período
- [ ] PWA / modo offline

## 📄 Licença

MIT
