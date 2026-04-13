# Redesign de IHC: Google Acadêmico 🎓

Este projeto apresenta uma análise detalhada e uma proposta de intervenção para o Google Acadêmico (Google Scholar), focada em modernização visual, usabilidade e acessibilidade. O estudo foi desenvolvido como parte da disciplina de Interação Humano-Computador no curso de Sistemas de Informação.

---

## Contexto e Problema
O Google Acadêmico é uma ferramenta essencial para a pesquisa científica, permitindo o acesso a artigos, teses e livros. No entanto, a análise da situação atual revelou lacunas significativas:
* **Interface Defasada:** O design visual está inconsistente em relação à identidade moderna do ecossistema Google (Material Design).
* **Ambiguidade Funcional:** Seções como "Minha biblioteca" são facilmente confundidas com outros serviços, como o Google Livros.
* **Barreiras de Acessibilidade:** O sistema é limitado para pessoas com deficiência, carecendo de recursos como pesquisa por voz e suporte robusto para leitores de tela.

---

## Metodologias Utilizadas
A análise foi fundamentada em frameworks clássicos de IHC para garantir o rigor técnico:
* **Análise PACT:** Detalhamento de Pessoas, Atividades, Contextos e Tecnologias envolvidos no uso da plataforma.
* **Triangulação de Dados:** Combinação de técnicas quantitativas e qualitativas, incluindo questionários, entrevistas semiestruturadas e grupos de foco.
* **Modelo CMN-GOMS:** Modelação de metas e operações para analisar a eficiência da interação em cenários específicos.
* **Engenharia Semiótica:** Avaliação da clareza da metamensagem do design e consistência dos ícones.

---

## Proposta de Intervenção
As soluções propostas visam reduzir a carga cognitiva e promover a inclusão digital:
1. **Atualização Visual:** Implementação do Material Design com foco em hierarquia visual e layout responsivo.
2. **Reestruturação de Menus:** Renomeação da "Minha biblioteca" para **"Artigos salvos"** e reorganização lógica das funcionalidades.
3. **Acessibilidade Universal:** Inclusão de suporte à pesquisa por voz, leitura de texto em voz alta e ajustes de contraste/fonte.
4. **Orientação ao Usuário:** Inserção de *tooltips* explicativos e tutoriais interativos para novos usuários.

---

## Personas e Cenários
O projeto utilizou personas para guiar as decisões de design:
* **Júlia Gonçalves (Estudante):** Representa o público jovem, focado em agilidade e dispositivos móveis, que sofre com a ambiguidade das bibliotecas do Google.
* **Maria Antônia (Pesquisadora):** Representa o público com menos familiaridade tecnológica, que enfrenta dificuldades na descoberta de recursos secundários, como a adição manual de artigos.

---

## Protótipos e Interface Proposta

Nesta secção, apresentamos as principais soluções visuais desenvolvidas para resolver os problemas de usabilidade e acessibilidade identificados na análise.

### 1. Redesign da Página de Resultados (Material Design)
<img src="https://github.com/user-attachments/assets/c89b8778-b47e-4420-9b95-430ffaf52bc5" width="80%" />

<img src="https://github.com/user-attachments/assets/bfb8f9a3-8f74-4d6b-be94-b6c208d5868d" width="80%" />

* **Melhoria:** Aplicação de hierarquia visual clara e tipografia moderna, alinhada ao ecossistema Google.
* **Acessibilidade:** Inclusão de botões destacados para pesquisa por voz e leitura de texto.

### 2. Redução de Ambiguidade Funcional
<img src="https://github.com/user-attachments/assets/eb26e2df-661c-4761-bdac-49d79b97b3af" width="80%" />

* **Mudança:** A seção "Minha biblioteca" foi renomeada para **"Artigos salvos"** para evitar confusão com o Google Livros e alinhar o sistema ao modelo mental do utilizador.

### 3. Storyboards: Cenário Atual vs. Proposta
Aqui ilustramos a jornada da utilizadora Júlia, demonstrando como a nova interface elimina erros de navegação.

| Cenário Atual (Problema) | Intervenção Proposta (Solução) |
| :--- | :--- |
| <img width="1600" height="1280" alt="image" src="https://github.com/user-attachments/assets/83aa2ea0-903f-4958-8217-5a1645525d4d" /> | <img width="1600" height="1280" alt="image" src="https://github.com/user-attachments/assets/727e537c-00e5-493f-8759-c4b5566d1c08" /> |
|Erro de descoberta e frustração ao tentar acessar a artigos salvos. | Fluxo linear e intuitivo, garantindo o sucesso da tarefa. |

---

## Estrutura do Repositório
* `/docs`: Relatório completo em PDF contendo a análise PACT, levantamento de requisitos e modelagem GOMS.
* `/assets`: Imagens dos storyboards, perfis de usuários e protótipos de interface.

---

## Grupo
* Matheus Hoffmann 
* Livia Novais 
* Adrielle Moreira 
* Sérgio Melo 
* Stephanie Soares

---
> **Nota Final:** Este estudo evidenciou que, embora funcional, a modernização do Google Acadêmico é uma oportunidade crítica para reforçar seu papel no apoio à pesquisa científica através da inclusão e do conforto cognitivo.
