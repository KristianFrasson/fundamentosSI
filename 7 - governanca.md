# Governança de TI, Ética e Privacidade de Dados (O impacto da LGPD no Desenvolvimento de Software)

## Conceitos e fundamentos
* O que é Governança de TI (COBIT/ITIL)?
* Princípios da LGPD para Desenvolvedores?
* O que é Privacy by Design
* O que são Dados Sensíveis?

## Para refletir
A MedAgenda é uma plataforma SaaS hospedada na AWS (IaaS) que gerencia consultas médicas. O sistema armazena o histórico clínico dos pacientes. Para economizar, a equipe de desenvolvimento usa o mesmo banco de dados de produção nos ambientes virtuais de testes locais dos programadores. Um dos desenvolvedores baixou o dump/cópia do banco de dados na sua máquina pessoal para corrigir um bug em casa, mas teve seu notebook furtado. O banco continha nomes, CPFs e diagnósticos de 10.000 pacientes.

Desafio:

   1. Identificação: Quais dados sensíveis foram expostos e quais princípios de segurança/privacidade foram violados?
   2. Mitigação Tecnológica: Como o uso correto de infraestrutura (Docker, ambientes isolados) e técnicas de banco de dados (Anonimização/Mascaramento de dados) poderia ter evitado o desastre?
   3. Governança: Qual processo ou política de acessos (quem pode ver o quê) deveria ser implementado na nuvem (PaaS/IaaS) da empresa?

