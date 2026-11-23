# 🏆 E-Sports Arena Challenge — Torneio de FIFA & Simulador de Infraestrutura

> **Projeto Acadêmico — Centro Universitário Ítalo Brasileiro (UNIÍTALO)**  
> **Disciplina:** Análise e Desenvolvimento de Sistemas — Gestão de Projetos  
> **Professor Orientador:** Lucas Gomes Moreira  
> **Equipe / Empresa:** ITATECH  

---

## 📋 Sobre o Projeto

O **E-Sports Arena Challenge** é um sistema desenvolvido em lógica estruturada (**Visualg 3.0**) para automação de campeonatos de e-Sports (FIFA 1x1) e simulação financeira de infraestrutura de TI para arenas temporárias ou permanentes.

### Funcionalidades Principais (`v1.0`)
* **Cadastro de Equipes e Jogadores (`PB-01`):** Registro de até 10 equipes com 1 a 6 pro-players cada (limite global de 100 jogadores) e geração automática de IDs.
* **Gerenciamento CRUD e Exclusão em Cascata (`PB-02` / `PB-03`):** Edição de elencos e exclusão de equipes/jogadores com reorganização automática dos vetores em memória (sem lacunas de índice).
* **Relatório de Participantes (`PB-04`):** Listagem hierárquica por equipe com estatísticas individuais de gols.
* **Motor de Confrontos 1x1 e Ranking (`PB-05`):** Validação de elencos equivalentes, cálculo oficial de pontuação (3 pts vitória, 1 pt empate, 0 derrota) e ordenação dinâmica (Bubble Sort) com desempate por número de vitórias.
* **Apurador de MVP / Artilheiro (`PB-06`):** Varredura automática do jogador com maior saldo de gols no torneio.
* **Simulador Financeiro de Infraestrutura (`PB-07`):** Orçamento detalhado de consoles/PCs, monitores 144Hz, switches Gigabit, roteadores Wi-Fi 6, cabeamento Cat6, mão de obra e estimativa de prazo de montagem em dias.

---

## 👥 Integrantes da Equipe (ITATECH)

| Integrante | RA / ID | Papel no Projeto |
| :--- | :---: | :--- |
| **Geovanny Henrique Gonçalves de Cerqueira** | `327078` | Product Owner (PO) |
| **Thiago Pereira Da Silva** | `327581` | Scrum Master (SM) |
| **Ivan Silva Coelho** | `326330` | Lead Developer / Arquiteto |
| **Vinícius Mendes De Lima** | `324825` | QA / Analista de Testes |
| **Tino Ntussé Nhasse** | `322084` | Especialista de Infraestrutura |
| **Hiago Cavalcante Mota** | `311159` | Analista de Negócios / Documentação |

---

## 📂 Estrutura do Repositório

```text
esports-arena-challenge/
├── docs/
│   └── Documentacao_Projeto_ITATECH_Esports_Arena.pdf   # Documentação de Projeto (PDP v1.0 Final)
├── src/
│   └── EsportsArenaChallenge_FIFA.alg                   # Código-fonte principal no Visualg 3.0
├── LICENSE                                              # Licença MIT
└── README.md                                            # Documentação de apresentação e execução
