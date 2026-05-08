# 🔐 Sistema de Gestão de Segurança da Informação (SGSI)
## 📘 ISO/IEC 27001, 27002 e 27701

---

## 📌 Descrição
Este projeto apresenta a implementação de um Sistema de Gestão de Segurança da Informação (SGSI), com base nas normas ISO/IEC 27001, 27002 e 27701, considerando aspectos de segurança da informação e proteção de dados pessoais.

---

# 🧩 Identificação de Ativos de TI

|Ativo de TI | Justificativa |
|------------|--------------|
|Servidores de aplicativos e banco de dados | Esses servidores hospedam os sistemas de pagamento e empréstimo e armazenam informações sobre transações, dados pessoais dos clientes e históricos de empréstimos, sendo vitais para a operação da empresa. Uma violação pode comprometer a confidencialidade, integridade ou disponibilidade dessas informações. |
|Aplicativo móvel e portal web | Esses sistemas são a principal interface com os usuários e permitem a realização de transações financeiras e solicitação de empréstimos. Qualquer falha pode impactar diretamente a disponibilidade do serviço, a integridade das transações e a confiança dos clientes. |
|Armazenamento | Responsável por armazenar arquivos, documentos e informações institucionais da empresa. No cenário apresentado, está hospedado em nuvem, aumentando a dependência do provedor e os riscos relacionados à confidencialidade e disponibilidade dos dados. |
|Sistema de e-mail | Utilizado para comunicação interna e externa, podendo conter informações sensíveis. É um dos principais vetores de ataques como phishing, podendo comprometer a segurança da organização. |
|Sistemas de monitoramento | Responsáveis por identificar falhas, incidentes e atividades suspeitas. No cenário apresentado, dependem de ferramentas do provedor, o que pode limitar a visibilidade e a resposta a incidentes. |

---

# 🔄 Correlacionar Processos

| Processo | Descrição |
|----------|----------|
| Definição do escopo e política de segurança da informação | O primeiro passo é definir claramente o escopo do SGSI e estabelecer uma política de segurança da informação que forneça uma direção geral para a organização. |
| Avaliação de riscos e implementação de controles de Segurança da Informação | A organização deve identificar, analisar e avaliar os riscos, considerando ameaças, vulnerabilidades e impactos. Com base nisso, implementar controles conforme ISO/IEC 27001 e 27002. |
| Desenvolvimento de um plano de tratamento de riscos | Definir ações para mitigar, transferir, aceitar ou evitar riscos, priorizando os mais críticos e estabelecendo responsáveis e prazos. |
| Monitoramento, revisão e melhoria contínua | Monitorar controles, realizar auditorias internas e revisar o SGSI continuamente para garantir sua eficácia. |
| Implementação de medidas de proteção da privacidade e treinamento e conscientização | Implementar medidas de proteção de dados pessoais conforme ISO/IEC 27701 e promover treinamentos para os colaboradores. |

---

# 🏢 Processo e Responsabilidades

| Departamento | Processo | Responsabilidades |
|--------------|---------|------------------|
| Direção | Definição do escopo e política de segurança da informação | Definir o escopo do SGSI, aprovar a política de segurança da informação e proporcionar os recursos necessários para a segurança da informação. |
| Tecnologia da Informação | Implementação e gestão de controles de segurança da informação | Implementar controles técnicos de segurança, como controle de acesso, criptografia, backup e monitoramento. Garantir a proteção dos sistemas e redes, aplicar atualizações e correções de segurança e apoiar a resposta a incidentes. |
| Recursos Humanos | Treinamento e conscientização em segurança da informação | Promover treinamentos e ações de conscientização sobre segurança da informação para os colaboradores, garantindo que todos compreendam suas responsabilidades e sigam as políticas de segurança. |
| Jurídico / Compliance | Conformidade legal e proteção de dados | Garantir que a organização esteja em conformidade com leis e regulamentos aplicáveis, elaborar e revisar políticas, contratos e termos de uso, além de apoiar a gestão de riscos legais. |
| Todos os departamentos | Cumprimento das políticas de segurança da informação | Seguir as políticas e procedimentos de segurança estabelecidos, proteger as informações sob sua responsabilidade e reportar incidentes ou comportamentos suspeitos. |
---

# 🔐 Identificar Medidas

| Medidas | Justificativa |
|--------|--------------|
| Avaliação de riscos de privacidade | A empresa deve conduzir uma avaliação de riscos de privacidade para identificar os riscos específicos relacionados aos dados pessoais que são processados. Essa avaliação ajudará a determinar as medidas apropriadas de proteção e controle de dados. |
| Mapeamento de dados pessoais | A empresa deve identificar e mapear quais dados pessoais são coletados, processados, armazenados e compartilhados. Isso permite maior controle sobre o ciclo de vida dos dados e facilita a implementação de medidas de proteção adequadas. |
| Definição de políticas de privacidade | A organização deve estabelecer políticas claras de privacidade, definindo como os dados pessoais serão tratados, protegidos e compartilhados. Essas políticas devem estar integradas ao SGSI e alinhadas com as normas e legislações aplicáveis. |
| Gestão de direitos dos titulares dos dados | A empresa deve implementar processos para garantir que os titulares possam exercer seus direitos, como acesso, correção e exclusão de seus dados. Isso garante transparência e conformidade com regulamentações de proteção de dados. |
| Treinamento e conscientização unificados | A organização deve promover treinamentos contínuos sobre segurança da informação e privacidade, garantindo que todos os colaboradores compreendam suas responsabilidades no tratamento de dados pessoais e reduzindo riscos de incidentes. |

---

# 📋 Plano de Ação

| Plano de Ação | Tarefas |
|--------------|--------|
| Estabelecimento de uma equipe de projeto | **1.** Designar uma equipe multidisciplinar composta por representantes de diferentes departamentos, incluindo Segurança da Informação, Tecnologia da Informação, Jurídico, Recursos Humanos e Compliance. <br><br> **2.** Nomear um líder de projeto responsável pela coordenação e execução do plano de ação. |
| Definição de políticas e procedimentos de segurança e privacidade | **1.** Elaborar e documentar políticas de segurança da informação e privacidade alinhadas à ISO/IEC 27001 e 27701. <br><br> **2.** Garantir a comunicação e disseminação dessas políticas para todos os colaboradores da organização. |
| Implementação de controles de segurança e privacidade | **1.** Implementar controles técnicos e organizacionais, como controle de acesso, criptografia e proteção de dados pessoais. <br><br> **2.** Integrar controles de privacidade ao SGSI existente, garantindo a proteção dos dados em todo o seu ciclo de vida. |
| Monitoramento e gestão de incidentes | **1.** Estabelecer processos para monitoramento contínuo dos sistemas e detecção de incidentes de segurança e privacidade. <br><br> **2.** Definir e implementar um plano de resposta a incidentes, incluindo comunicação e mitigação de impactos. |
| Revisão, auditoria e melhoria contínua do SGSI | **1.** Realizar auditorias internas periódicas para avaliar a eficácia dos controles implementados. <br><br> **2.** Revisar continuamente o SGSI com base nos resultados das auditorias, incidentes e mudanças no ambiente, promovendo melhorias constantes. |
---



# 🧠 Conclusão
O projeto demonstra a implementação de um SGSI alinhado às normas ISO/IEC 27001, 27002 e 27701, garantindo a proteção da informação e dos dados pessoais. A abordagem segue o modelo de melhoria contínua (PDCA), promovendo evolução constante dos processos de segurança.

---

# 🚀 Conceitos Aplicados
- ISO/IEC 27001  
- ISO/IEC 27002  
- ISO/IEC 27701  
- GRC (Governança, Riscos e Compliance)  
- LGPD  
