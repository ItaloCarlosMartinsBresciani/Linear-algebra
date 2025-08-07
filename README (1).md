##  Trabalho Final - Álgebra Linear e Aplicações

###  Tema: Problema de Procrustes Ortogonal

### 👥 Integrantes

* [@anapbatista](https://github.com/anapbatista) – Ana Paula de Abreu Batista 
* [@ItaloCarlosMartinsBresciani](https://github.com/ItaloCarlosMartinsBresciani) – Italo Carlos Martins Bresciani 
* [@LuizCorrei4](https://github.com/LuizCorrei4) – Luiz Gabriel Correia dos Santos 

---

### 🧩 Resumo da Proposta

Neste trabalho, exploramos o **Problema de Procrustes Ortogonal**, que busca encontrar a melhor matriz de rotação para alinhar dois conjuntos de pontos no espaço, minimizando a diferença entre eles.

Essa abordagem tem aplicações importantes, especialmente em **visão computacional**, como no **alinhamento de formas** (ex: rostos) e no reconhecimento de padrões em imagens.

---

### 🛠️ Implementação e Abordagem

A implementação prática consistiu nos seguintes passos:

1. **Importação de pontos faciais** de duas imagens distintas.
2. **Centralização dos pontos** em relação à origem.
3. Aplicação da **Decomposição em Valores Singulares (SVD)** para obter a **matriz de rotação ideal**.
4. **Transformação e alinhamento dos pontos**, verificando a sobreposição.
5. **Visualização gráfica** para validar a eficácia da rotação.

---

### 👁️ Sobre as Imagens

Para representar rostos humanos de forma ética e segura, utilizamos imagens da **influencer virtual Aitana López**, uma **IA hiper-realista**. Isso evita problemas de privacidade e permite o estudo em contextos reais com dados sintéticos.

---

### 📓 Detalhamento Matemático

A explicação completa dos conceitos matemáticos, incluindo a dedução da matriz de rotação via SVD, está disponível no **notebook** que acompanha este repositório.

---

### 📚 Referências

* Simon Ensemble (2018). *Orthogonal Procrustes Problem*.
* Wikipedia. *(Orthogonal Procrustes Problem)*.
* Hossain, T. (2021). *Understanding the Orthogonal Procrustes Problem*.

---
