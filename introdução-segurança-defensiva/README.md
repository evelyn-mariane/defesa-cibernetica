# Análise de Incidente e Inteligência de Ameaças - TryHackMe

Resolução prática do laboratório "Introdução à Segurança Defensiva" da plataforma TryHackMe, focado nas atribuições de um Analista de SOC (Security Operations Center) N1.

## 1. Monitoramento e Detecção de Alertas
O incidente começou com a identificação de múltiplos alertas de tentativas de login suspeitas (Ataque de Força Bruta) no painel de monitoramento do SOC.

## 2. Investigação e Triagem do Incidente
Ao analisar os detalhes do alerta, identifiquei o usuário afetado (dave.saunders) e a origem da ameaça, mapeada sob o codinome do atacante (ShadowFigures). A conta do usuário foi bloqueada preventivamente para conter o ataque.

## 3. Inteligência de Ameaças (Threat Intelligence)
Realizei uma busca no banco de dados de inteligência de ameaças para correlacionar as táticas, técnicas e procedimentos (TTPs) e os endereços de IP maliciosos vinculados ao grupo cibercriminoso ShadowFigures.

## 4. Relatório de Incidente (Incident Report)
Com todas as evidências coletadas (IP de origem, usuário alvo, página atacada /login e tipo de vetor Bruteforcing), preenchi o relatório oficial de incidentes para documentação interna e auditoria de segurança.

## 5. Mitigação e Conclusão
O relatório foi enviado com sucesso, garantindo a contenção da ameaça, o isolamento dos IPs maliciosos e a validação da conformidade do ambiente afetado.

## Ferramentas e Conceitos Praticados:
* Triagem de Alertas em SOC (SIEM Simulado)
* Contenção de Contas Comprometidas
* Análise de TTPs e IPs com Cyber Threat Intelligence (CTI)
* Documentação de Incidentes de Segurança
