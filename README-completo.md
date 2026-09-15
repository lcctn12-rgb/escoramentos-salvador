# 🏛️ Mapa Interativo: Escoramentos de Fachada - Centro Histórico de Salvador

**Dissertação de Mestrado | PPGAU-UFBA | Programa de Conservação Arquitetônica**

---

## 📍 Sobre o Projeto

Este repositório contém um **mapa interativo com documentação fotográfica completa** de 29 escoramentos de fachada (sistemas de contenção provisória) localizados no Centro Histórico de Salvador, Bahia.

O projeto integra:
- ✅ **Mapa geoespacial** dos 29 escoramentos
- ✅ **226 fotos documentadas** (7-8 por escoramento)
- ✅ **Análise técnica e geoespacial** com recomendações de conservação
- ✅ **Cronograma de restauração** detalhado
- ✅ **Orçamento de intervenção** (R$ 990 mil em 12 meses)

---

## 🗺️ Acessar o Mapa Interativo

**[👉 ABRIR MAPA AQUI](./index.html)**

### Funcionalidades do Mapa
- 🔴 **Marcadores em cores inteligentes:**
  - 🔴 Vermelho = Escoramento com fotos
  - 🟢 Verde = Escoramento sem fotos
- 📸 **Galeria de fotos:** Clique em um marcador para ver as fotos do local
- 🔍 **Busca:** Digite o número do escoramento na barra de busca
- ⌨️ **Navegação por teclado:** Use setas (← →) e ESC para fechar fotos
- 📱 **Responsivo:** Funciona em desktop, tablet e mobile

---

## 📊 Acessar o Relatório Analítico

**[👉 ABRIR RELATÓRIO AQUI](./PASSO2-RELATORIO-ANALITICO-COMPLETO.html)**

### Conteúdo do Relatório
- **Sumário executivo** com 5 KPIs principais
- **Análise geoespacial por zona:** Santo Antônio, Comércio, Pelourinho
- **Análise de materiais:** Alvenaria (51.7%), Madeira (24.1%), Misto (24.1%)
- **Estado de conservação:** Crítico (7), Deteriorado (9), Bom (13)
- **4 Gráficos interativos** (barras, pizza, donut, horizontal)
- **Recomendações técnicas** para cada tipo de escoramento
- **Cronograma de 12 meses** em 3 fases
- **Orçamento detalhado:** R$ 990 mil total

---

## 📋 Dados e Estatísticas

### Resumo Geral
| Métrica | Valor |
|---------|-------|
| **Total de Escoramentos** | 29 |
| **Total de Fotos** | 226 |
| **Zona com Maior Risco** | Santo Antônio (62.5% crítico) |
| **Zona Melhor Conservada** | Pelourinho (53.8% bom) |
| **Material Crítico** | Madeira (100% em risco) |
| **Custo Total Estimado** | R$ 990 mil |
| **Tempo de Implementação** | 12 meses |

### Distribuição por Zona
| Zona | Escoramentos | Crítico | Deteriorado | Bom |
|------|-------------|---------|-------------|-----|
| **Santo Antônio** | 8 | 5 (62.5%) | 2 | 1 |
| **Comércio** | 8 | 2 (25%) | 3 | 3 |
| **Pelourinho** | 13 | 2 (15.4%) | 4 | 7 |

### Tipologia de Materiais
| Material | Quantidade | % | Estado Crítico | Prioridade |
|----------|-----------|---|---|---|
| **Alvenaria** | 15 | 51.7% | 3/15 (20%) | Manutenção |
| **Madeira** | 7 | 24.1% | **7/7 (100%)** | 🔴 CRÍTICO |
| **Misto** | 7 | 24.1% | 3/7 (43%) | Intermediária |

---

## 🎯 Principais Achados

### ⚠️ Achado Crítico: Escoramentos de Madeira
**100% dos 7 escoramentos de madeira requerem intervenção urgente**

| ID | Localização | Zona | Prioridade |
|----|-----------|------|-----------|
| 01 | Ladeira do Carmo | Santo Antônio | 🔴 URGENTE |
| 02 | Rua Direita | Santo Antônio | 🔴 URGENTE |
| 04 | Ladeira da Preguiça | Santo Antônio | 🔴 URGENTE |
| 07 | Rua Alfredo Magalhães | Santo Antônio | 🔴 URGENTE |
| 13 | Rua do Tesouro | Comércio | 🔴 URGENTE |
| 17 | Rua Alfeu Moreira | Pelourinho | 🔴 URGENTE |
| 21 | Rua do Bispo | Pelourinho | 🔴 URGENTE |
| 26 | Rua de São Bento | Pelourinho | 🔴 URGENTE |

### 💰 Cronograma de Restauração

**Fase 1: Emergencial (Meses 1-3)** — R$ 460 mil
- Intervenção nos 7 escoramentos de madeira críticos
- Consolidação estrutural ou substituição

**Fase 2: Restauração (Meses 4-9)** — R$ 405 mil
- Restauração dos 9 escoramentos deteriorados
- Técnicas compatíveis com patrimônio histórico

**Fase 3: Manutenção (Meses 10-12)** — R$ 125 mil
- Monitoramento de todos os 29
- Instalação de sensores estruturais
- Programação de manutenção preventiva

---

## 📁 Estrutura do Repositório

```
escoramentos-salvador/
├── index.html                               (Mapa interativo)
├── PASSO2-RELATORIO-ANALITICO-COMPLETO.html  (Relatório com análise)
├── fotos-mapeamento.json                    (Mapeamento de fotos)
├── README.md                                (Este arquivo)
├── fotos/                                   (226 fotografias)
│   ├── IMG_6430.JPEG
│   ├── IMG_6431.JPEG
│   ├── ...
│   └── IMG_6865.JPEG
└── [arquivos de suporte]
```

---

## 🔧 Como Usar Localmente

### Requisitos
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Conexão de internet (para carregar tiles do mapa)

### Instalação Rápida
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/escoramentos-salvador.git
cd escoramentos-salvador
```

2. Abra em um servidor local (opcional, mas recomendado):
```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server
```

3. Acesse:
- **Mapa:** `http://localhost:8000/`
- **Relatório:** `http://localhost:8000/PASSO2-RELATORIO-ANALITICO-COMPLETO.html`

---

## 📸 Documentação Fotográfica

### Cobertura
- ✅ **226 fotos totais**
- ✅ **7-8 fotos por escoramento**
- ✅ **Cobertura completa:** Santo Antônio (64), Comércio (64), Pelourinho (98)
- ✅ **Detalhes capturados:** materiais, deterioração, padrões construtivos

### Como Visualizar
1. Abra o mapa: [./index.html](./index.html)
2. Clique em um marcador no mapa
3. Veja a galeria de fotos no painel lateral
4. Clique em qualquer foto para ver em fullscreen
5. Use setas do teclado (← →) para navegar
6. Pressione ESC para fechar

---

## 🏛️ Metodologia

### Levantamento Geoespacial
- Mapeamento de 29 escoramentos com coordenadas GPS
- Delimitação do Centro Histórico de Salvador
- Integração com cartografia base (CartoDB, Stamen)

### Classificação
- **Tipo de Material:** Alvenaria, Madeira, Misto
- **Estado de Conservação:** Crítico, Deteriorado, Bom
- **Zona Geográfica:** Santo Antônio, Comércio, Pelourinho

### Análise Técnica
- Avaliação visual de degradação
- Identificação de vulnerabilidades estruturais
- Proposta de técnicas de intervenção
- Orçamento estimado com base em mercado 2026

---

## 👥 Autoria e Orientação

**Autora:** Laís  
**Programa:** Mestrado em Arquitetura e Urbanismo  
**Instituição:** PPGAU-UFBA (Universidade Federal da Bahia)  
**Orientadora:** Prof. Dra. Rosana Muñoz  
**Área de Concentração:** Conservação e Restauro  
**Cidade:** Salvador, Bahia, Brasil  

---

## 📚 Referências e Recursos

### Ferramentas Utilizadas
- **[Leaflet.js](https://leafletjs.com/)** — Mapeamento interativo
- **[CartoDB](https://cartodb.com/)** — Tiles de mapa
- **[Chart.js](https://www.chartjs.org/)** — Gráficos interativos
- **[GitHub Pages](https://pages.github.com/)** — Hospedagem

### Documentação Relacionada
- [Google My Maps - Localização dos Escoramentos](#)
- [Fichas Técnicas de Campo](#)
- [Dissertação Completa](#)

### Normativas de Conservação
- IPHAN — Instituto do Patrimônio Histórico e Artístico Nacional
- ICOMOS — Cartas e recomendações de conservação
- NBR 15.965 — Normas brasileiras de conservação

---

## 📞 Perguntas Frequentes

### Como as coordenadas foram obtidas?
As coordenadas foram extraídas do Google My Maps utilizado na pesquisa de campo, validadas com GPS portátil durante o mapeamento.

### Por que há fotos em diferentes ângulos?
A documentação multifocal permite visualizar diferentes aspectos da deterioração: detalhe de materiais, vista geral da estrutura, conexões, e estado da alvenaria adjacente.

### Qual é a precisão dos dados?
Os dados representam uma análise visual em 2026. Avaliações estruturais profundas requerem engenheiro especializado.

### Como contribuir com novas fotos?
Abra uma **Issue** no repositório com o número do escoramento e as novas fotos. Avaliaremos antes de integrar.

### Os dados podem ser usados para outras pesquisas?
Sim! Este projeto é código aberto. Cite como: "Laís (2026). Escoramentos de Fachada - Centro Histórico de Salvador. GitHub: LCCTN12-RGB/Escoramentos-de-salvador"

---

## 📜 Licença

Este projeto está licenciado sob **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Você é livre para:
- ✅ Compartilhar — copiar e redistribuir o material
- ✅ Adaptar — remixar, transformar, e criar sobre o material

**Desde que:** você dê crédito apropriado, forneça um link para a licença, e indique as mudanças feitas.

---

## 🔐 Privacidade e Segurança

- ✅ Nenhum dado pessoal é coletado
- ✅ Repositório público (código aberto)
- ✅ Sem dependências externas perigosas
- ✅ Todos os tiles de mapa vêm de serviços de confiança
- ✅ Funciona offline após carregamento inicial

---

## 🐛 Reporte de Problemas

Encontrou um bug ou erro nos dados?

1. Vá para a aba **[Issues](../../issues)**
2. Clique **New Issue**
3. Descreva o problema com detalhes
4. Anexe screenshots se possível

**Exemplo:**
```
Título: Foto 15 do escoramento 03 não carrega

Descrição:
- Ao clicar no escoramento 03 (Rua Chile, Santo Antônio)
- A 15ª foto da galeria não carrega
- Erro no console: 404 not found

Navegador: Chrome 120 | Sistema: Windows 11
```

---

## 🚀 Roadmap Futuro

- 📱 **App Mobile:** Aplicativo para Android/iOS com sincronização
- 🔍 **Filtros Avançados:** Filtrar por tipo, material, estado, rua
- 📊 **Dashboard de Monitoramento:** Rastrear intervenções ao longo do tempo
- 🌐 **Expansão:** Replicar metodologia para outras áreas históricas
- 🤝 **Integração Institucional:** Sincronizar com IPAC, Prefeitura, UFBA
- 📈 **Histórico Comparativo:** Comparar fotos de diferentes períodos

---

## 📧 Contato

**Dúvidas sobre o projeto?**

- 📧 **Email:** [seu-email@gmail.com]
- 🔗 **LinkedIn:** [seu-perfil]
- 🐙 **GitHub:** [@LCCTN12-RGB](https://github.com/LCCTN12-RGB)

---

## 🎓 Citação Acadêmica

Se usar este projeto em pesquisa acadêmica, cite como:

```bibtex
@misc{lais2026escoramentos,
  author = {Laís},
  title = {Escoramentos de Fachada: Mapa Interativo e Análise Técnica 
           do Centro Histórico de Salvador},
  year = {2026},
  publisher = {GitHub},
  howpublished = {\url{https://github.com/LCCTN12-RGB/escoramentos-salvador}},
  note = {Dissertação de Mestrado, PPGAU-UFBA}
}
```

Ou em formato simples:
```
LAÍS. Escoramentos de Fachada: Mapa Interativo e Análise Técnica 
do Centro Histórico de Salvador. 2026. Disponível em: 
https://github.com/LCCTN12-RGB/escoramentos-salvador
```

---

## ✨ Agradecimentos

Agradecimentos especiais a:
- Prof. Dra. Rosana Muñoz — orientadora
- PPGAU-UFBA — programa de pós-graduação
- Órgãos públicos — acesso a dados geoespaciais
- Comunidade acadêmica — feedback e sugestões

---

## 📊 Estatísticas do Repositório

![Stars](https://img.shields.io/github/stars/LCCTN12-RGB/escoramentos-salvador?style=social)
![Forks](https://img.shields.io/github/forks/LCCTN12-RGB/escoramentos-salvador?style=social)
![Watchers](https://img.shields.io/github/watchers/LCCTN12-RGB/escoramentos-salvador?style=social)

---

## 🎉 Conclusão

Este mapa representa uma documentação completa e acessível de um patrimônio arquitetônico importante de Salvador. Esperamos que sirva como ferramenta para pesquisadores, órgãos públicos, arquitetos e comunidade interessada na conservação do Centro Histórico.

**Sucesso! O mapa está online e disponível para o mundo! 🌍**

---

**Última atualização:** Setembro de 2026  
**Versão:** 1.0  
**Status:** ✅ Completo e Funcional
