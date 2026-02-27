# 🚀 WhatsApp Sales Analyst - Spec-Driven Project

Este repositório contém uma Skill de IA especializada em análise de conversas de WhatsApp, com foco em aumentar a conversão de usuários para o plano **PRIME**.

## 🧠 Metodologia: SDD (Spec-Driven Development)

Este projeto não é baseado apenas em "prompts soltos". Ele utiliza a metodologia **SDD**, onde a inteligência é guiada por especificações técnicas rigorosas.

- **Specify (O Verbo):** O ato de definir as regras de negócio e os contratos de dados antes de criar a IA.
- **Spec (O Substantivo):** Os arquivos de especificação contidos na pasta `/specs` que servem como a "única fonte da verdade".
- **Prompt:** A instrução técnica que traduz as Specs para a linguagem da IA.

## 📂 Estrutura do Repositório

Organização baseada em padrões de engenharia de software:

- `/specs`: Contém as regras de classificação (Quente, Morno, Frio) e o esquema de saída JSON.
- `/prompts`: Armazena os prompts estruturados que utilizam as specs.
- `/skills`: Repositório de competências modulares (ex: análise de humor, recuperação de carrinho).
- `/docs`: Documentação adicional e SDD (Software Design Document).

## 🛠️ Como Utilizar (Via Bash)

### 1. Clonar o Repositório
```bash
git clone [https://github.com/SEU_USUARIO/whatsapp-analyst-prime.git](https://github.com/SEU_USUARIO/whatsapp-analyst-prime.git)
cd whatsapp-analyst-prime

2. Fluxo de Trabalho (Git Flow)
Sempre crie uma branch para novas implementações ou melhorias nas specs:

Bash
git checkout -b feature/nome-da-melhoria
# Faça suas alterações
git add .
git commit -m "feat: descrição da mudança na spec"
git push origin feature/nome-da-melhoria

📊 Objetivo da Skill
O agente analisa o log da conversa e identifica:

Status do Lead: Classificação automática baseada em gatilhos de compra.

Insights de Venda: Sugestão de gatilhos mentais (Escassez, Urgência).

Otimização de Fluxo: Identificação de onde a conversa "esfriou".

Desenvolvido com foco em escalabilidade e precisão técnica.


---

### 💡 Por que este conteúdo é importante?

1.  **A Seção Metodologia:** Explica a diferença entre **Specify** e **Spec** que você aprendeu. Isso mostra que você tem base teórica.
2.  **A Estrutura de Pastas:** Ajuda a manter o projeto **robusto**. Se você criar uma nova skill amanhã, já sabe onde colocar.
3.  **O Guia de Bash:** Ensina como usar branches. Se você quiser testar uma regra nova sem estragar a versão que já funciona, você usa o comando de `checkout -b` que está ali.

### 🏁 Próximo Passo Sugerido

Agora que o seu README está pronto:
1. Salve o arquivo no VS Code.
2. No terminal, use os comandos que aprendemos:
   * `git add README.md`
   * `git commit -m "docs: finaliza readme com metodologia SDD"`
   * `git push origin main` (ou a branch que você estiver usando).

**Gostaria que eu te ajudasse a criar agora o arquivo `specs/output-schema.json` para definir exatamente como a IA deve "cuspir" os dados?** Isso é o que torna a sua ferramenta integrável com outros sistemas.