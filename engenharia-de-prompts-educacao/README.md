# 🧠 Engenharia de Prompts Aplicada: IA como Assistente Educacional

**Documento completo disponível no arquivo:** [`portifolio1.pdf`](engenharia-de-prompts-educacao/portifolio1.pdf)

## 🎯 Resumo do Projeto
Este projeto explora a aplicação de Inteligência Artificial para o planejamento de aulas de tecnologia, com foco em alunos do 6º ano do Ensino Fundamental com defasagem em letramento digital. 

O objetivo técnico central é demonstrar como a **Engenharia de Prompts** afeta diretamente a qualidade e a utilidade da resposta gerada por um Modelo de Linguagem (LLM), transformando uma ferramenta genérica em uma assistente altamente especializada.

## 🛠️ O Problema e o Contexto
* **Público-alvo:** Crianças de 10 a 11 anos da região do Jardim Roberto (Osasco - SP).
* **Desafio:** Ensinar lógica de programação (estruturas condicionais e laços no Scratch) para um público com lacunas significativas no manuseio de computadores.
* **Necessidade Sistêmica:** O roteiro gerado pela IA precisava ser lúdico, utilizar analogias do cotidiano e da cultura pop infantil, e evitar abstrações técnicas complexas que pudessem bloquear os alunos.

## 🚀 Metodologia: A Evolução do Prompt
Para validar que modelos de IA baseados em previsões estatísticas dependem intrinsecamente da especificidade da entrada, a modelagem foi dividida em três estágios de complexidade:

### ❌ Prompt A (Genérico)
> *"Crie uma aula de programação em Scratch sobre comandos condicionais e laços."*

**Problema:** Gera uma saída padronizada, ignorando o nível de letramento e a realidade sociocultural dos usuários finais.

### ⚠️ Prompt B (Contextualizado)
> Adição de dados demográficos (região, faixa etária) e exigência de engajamento utilizando exemplos concretos para o perfil de alunos com necessidades educacionais especiais.

### ✅ Prompt C (Contextualizado + Critérios e Limites Estritos)
O prompt definitivo foi desenhado como uma instrução de sistema complexa, forçando a IA a respeitar regras de negócio claras:
1. **Diferenciação:** Exigência de instruções de apoio detalhadas e visuais focadas no manuseio básico do computador.
2. **Localização:** Tradução da lógica para referências da vivência local e cultura pop atual.
3. **Limites Técnicos (Restrições):** Uso restrito e obrigatório da nomenclatura oficial do Scratch (ex: "se... então", "repita"). **Proibição absoluta** de introdução de algoritmos complexos, pseudocódigo ou linguagens baseadas em texto.

## 💡 Conclusão
Ao fornecer um contexto rico, estruturar objetivos de diferenciação e aplicar restrições técnicas rigorosas de vocabulário, o Prompt C elimina o risco de alucinações ou respostas genéricas. Este modelo comprova que o controle estrito de parâmetros transforma o LLM em uma ferramenta de precisão para a resolução de problemas reais.
