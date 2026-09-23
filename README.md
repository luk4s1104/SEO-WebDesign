# 🎲 Criador de Ficha de RPG - Laboratório de SEO e UI/UX

Este repositório contém o código-fonte de uma aplicação web conceitual para um **Criador de Ficha de RPG**. O projeto foi desenvolvido com objetivos puramente acadêmicos, servindo como uma **prova de conceito (PoC)** e **ambiente controlado** para o aprendizado prático de técnicas de otimização para motores de busca (**SEO**) e acessibilidade web.

> ⚠️ **Nota:** O código disponibilizado aqui é uma versão preliminar e simplificada (protótipo). Ele foi projetado especificamente para testar critérios de indexação, performance de renderização e semântica de tags, funcionando como a fundação estrutural para um sistema maior e mais robusto no futuro.

---

## 🎯 Objetivos do Projeto
*   **Estudo de SEO On-Page:** Validar o impacto da inclusão de meta tags críticas (`description`, `viewport`) e metadados de compartilhamento (protocolo `Open Graph`) na avaliação de algoritmos de busca.
*   **Auditoria via PageRank:** Utilizar a ferramenta *Google PageSpeed Insights* para diagnosticar gargalos técnicos e observar a evolução da nota da página (que subiu de 90 pontos para o nível ideal após a refatoração).
*   **Exploração de UI/UX:** Desenvolver uma interface imersiva no estilo *Dark Mode* voltada ao público de RPG de mesa, balanceando design com performance de carregamento rápido.

---

## 📂 Estrutura dos Arquivos

O projeto simula o fluxo básico de navegação de um usuário através de dois arquivos principais:

1.  **`index.html` (Página Inicial):** A porta de entrada do site. Utiliza uma abordagem de estilização baseada exclusivamente em **CSS Inline** para garantir que a renderização ocorra sem o bloqueio de arquivos externos. Conta com efeito de fundo escurecido (`opacity: 0.3`) e toda a configuração dos metadados estruturados de SEO.
2.  **`form.html` (Tela da Ficha):** O ambiente operacional onde a ficha é montada. Concentra sua folha de estilos em um bloco de **CSS Interno** (`<style>` no `<head>`), organizando as informações através de propriedades flexíveis (`display: flex`) e grades estruturadas (`display: grid`) para simular os slots de equipamentos do personagem.

---

## 🛠️ Tecnologias Utilizadas
*   **HTML:** Estruturação semântica da aplicação.
*   **CSS:** Estilização visual (abordagens interna e inline).
*   **Google PageSpeed Insights:** Ferramenta de análise técnica e auditoria de PageRank.

---

## 📈 Resultados Obtidos
Durante o ciclo de desenvolvimento, a ausência inicial de metadados limitou a pontuação de SEO da página em **90 pontos**. Com a aplicação das correções 
estruturais descritas, a página eliminou os apontamentos de erros dos robôs de busca, comprovando como pequenos ajustes no cabeçalho modificam a leitura e a relevância orgânica de um projeto na web.

🔗 **Acesse o projeto online:** [Clique aqui para visualizar o site](https://seo-web-design-six.vercel.app/)
