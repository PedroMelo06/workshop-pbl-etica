# Relatório de Conformidade Ética e LGPD

**Disciplina / Contexto:** Metodologia Ativa - Aprendizagem Baseada em Problemas (PBL) 
**Instituição:** Universidade Católica de Brasília (UCB)  
**Professor:** Marco Machado  

---

## 1. Etapa 1: Diagnóstico e LGPD (25 min)

### Mapeamento de Dados (ONG de Apoio Comunitário)
* **Dados Comuns (3 itens):**
  1. **Nome Completo:** Identificação básica do beneficiário ou voluntário.
  2. **E-mail:** Canal de comunicação para avisos e atualizações.
  3. **Telefone/WhatsApp:** Contacto direto para coordenação de apoios.

* **Dados Sensíveis (2 itens - conforme LGPD):**
  1. **Dados de Saúde / Condição Médica:** Histórico de saúde ou restrições alimentares dos assistidos para direcionamento de ajuda.
  2. **Convicções Filosóficas / Organizações Sociais:** Dados sobre participação em entidades de amparo comunitário.

### Ficha de Minimização (DER)
Para atender ao princípio da minimização de dados, foram eliminados do Diagrama Entidade-Relacionamento (DER) campos desnecessários como *Estado Civil, Título de Eleitor e Renda Familiar Exata*, mantendo apenas o estritamente necessário para o suporte social[cite: 1].

### Regras RBAC (Role-Based Access Control)
Perfis de acesso definidos para a aplicação:
1. **Administrador:** Acesso total ao sistema, gestão de utilizadores e logs.
2. **Assistente Social:** Acesso a dados comuns e sensíveis necessários para o atendimento.
3. **Voluntário:** Acesso restrito apenas a dados comuns para marcação de presenças, sem ver dados sensíveis.

---

## 2. Etapa 2: TCLE & Imagem (35 min)

### Redação do TCLE
Termo redigido em linguagem simples e popular:
> **TERMO DE CONSENTIMENTO LIVRE E ESCLARECIDO**
> 
> Olá! Precisamos da sua autorização para guardar informações básicas (como nome e telefone) para organizar os nossos atendimentos e prestar o melhor auxílio possível.
> * **Segurança:** Os seus dados são confidenciais e nunca serão vendidos ou repassados a terceiros para fins comerciais.
> * **Seu direito:** Pode pedir para ver, alterar ou apagar os seus dados a qualquer momento.

### Protocolo de Imagem
* **Técnica de foto:** Foco em atividades coletivas e planos abertos, evitando exposição de rostos vulneráveis ou menores de idade.
* **Desfoque facial:** Aplicação obrigatória de desfoque (*blur*) na região facial antes de qualquer publicação ou armazenamento público de imagens.
