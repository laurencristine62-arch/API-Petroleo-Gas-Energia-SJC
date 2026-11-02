# Fontes de Dados - API Petróleo, Gás e Energia - SJC

### 1. Dados do mercado de trabalho
- **Fonte:** RAIS / MTE - Relação Anual de Informações Sociais - Ministério do Trabalho e Emprego (Base tratada via Base dos Dados)
- **Link:** https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/estatisticas-trabalho/rais e https://basedosdados.org/dataset/br-me-rais
- **Período analisado:** 2025
- **Informações utilizadas:** Quantidade de vínculos formais CLT por CNAE 2.0 subclasse em São José dos Campos/SP. Atividades relacionadas: 3511501 Geração de energia elétrica, 3514000 Distribuição de energia elétrica, 1921700 Fabricação de produtos do refino de petróleo, 4731800 Comércio varejista de combustíveis, 4682600 Comércio atacadista de GLP, 4221902/4221903 Construção e manutenção de redes de distribuição, entre outras. Base: `Empregos_Petroleo_Gas_Energia1.xlsx`.

### 2. Dados do perfil dos trabalhadores
- **Fonte:** RAIS/MTE e Relatório de Empregados Petrobras 2025
- **Link:** https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/estatisticas-trabalho/rais e https://www.petrobras.com.br/quem-somos/relatorio-anual
- **Período analisado:** 2025
- **Informações utilizadas:** Características dos trabalhadores do setor. Exemplo extraído da base `perfil_profissional.xlsx`: 1.665 vínculos nas 5 atividades locais mapeadas (Energia elétrica 713 vínculos, Comércio de combustíveis 952 vínculos). Total de empregados Petrobras no Brasil em 2025: 50.687. Utilizado para contextualizar que os dados de SJC são do mercado local e não representam apenas funcionários da Petrobras.

### 3. Dados das empresas e instalações
- **Fonte:** Receita Federal (Consulta CNPJ), ANP - Agência Nacional do Petróleo, ANEEL, ARSESP e Portal Oficial Petrobras
- **Link:** https://casadosdados.com.br, https://www.gov.br/anp/pt-br, https://www2.aneel.gov.br, https://www.petrobras.com.br
- **Período analisado:** 2025 (consulta atual)
- **Informações utilizadas:** Identificação e localização das empresas relacionadas ao setor em SJC. Base: `Instalacoes_Petroleo_Gas_Energia_SJC.xlsx` com 5 instalações validadas:
    - Refinaria Henrique Lage (REVAP) - Rodovia Presidente Dutra Km 143 - Refino (CNAE 1921-7/00) - Fonte: Receita Federal CNPJ 33.000.167/0036-04 / Petrobras
    - Comgás Unidade SJC - Distribuição de Combustíveis Gasosos (CNAE 3520-4/01)
    - EDP São Paulo Base SJC - Distribuição de Energia Elétrica (CNAE 3514-0/00)
    - NTS Ponto de Entrega de Gás Natural - Transporte de Gás Natural
    - Ultragaz Base de Envase - Comércio Atacadista de GLP (CNAE 4682-6/00)

## Finalidade
As bases foram utilizadas para organizar, analisar e juntar informações que contribuam para compreender o setor de Petróleo, Gás e Energia em São José dos Campos/SP. Os dados permitem analisar a dimensão do mercado de trabalho local, o perfil dos vínculos e a localização geográfica das principais instalações, com destaque para a REVAP como referência principal, conforme backlog `Base_Tratada.xlsx`.
