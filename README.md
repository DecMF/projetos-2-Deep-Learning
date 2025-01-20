#  Projetos de Deep Learning - IA353

## 📋 Descrição Geral
Este repositório contém projetos desenvolvidos na disciplina **IA353 - Redes Neurais** (pós-graduação FEEC/Unicamp), sob orientação do professor **Fernando José Von Zuben**. Os projetos abordam diversas técnicas de aprendizado profundo, aplicadas a problemas clássicos e modernos, como o problema do caixeiro viajante, predição de séries temporais, geração de imagens e aprendizado por reforço.

##  Estrutura do Repositório
- 📂 `notebooks`: Notebooks Jupyter com os códigos de implementação.
- 📂 `data`: Arquivos de dados utilizados nos projetos.
- 📂 `images`: Gráficos e resultados gerados pelos notebooks.
- 📂 `docs`: Documentação adicional.

---

##  Projetos

### **PC06 - Redes Neurais de Hopfield (TSP)**
- Objetivo: Resolver o problema do caixeiro viajante (TSP) utilizando redes neurais de Hopfield.
- Destaques:
  - Exploração de instâncias pequenas (até 10 cidades) devido à sensibilidade aos hiperparâmetros.
  - Limitações em atender as condições de contorno do problema.
- **Notebook**: [PC06_HN_TSP.ipynb](notebooks/PC06_HN_TSP.ipynb)

---

### **PC07 - Mapas Auto-Organizáveis (SOM) para TSP**
- Objetivo: Resolver o TSP utilizando mapas auto-organizáveis (SOM).
- Destaques:
  - Instâncias maiores que no PC06.
  - Exploração do "anel elástico" para aderir às coordenadas das cidades.
- **Notebook**: [PC07_SOM_TSP_atualizado.ipynb](notebooks/PC07_SOM_TSP_atualizado.ipynb)

---

### **PC08 - Predição de Séries Temporais (RNNs, LSTM e MLP)**
- Objetivo: Comparar diferentes abordagens para a predição de séries temporais.
- Séries analisadas:
  - Sunspot (bem comportada, facilita a predição linear).
  - Unemployment rate (impactada por eventos anômalos, como a pandemia de COVID-19).
- **Notebook**: [PC08_RNNs_MLP_LP_TS_SUNSPOT.ipynb](notebooks/PC08_RNNs_MLP_LP_TS_SUNSPOT.ipynb)

---

### **PC09 - Autoencoders para MNIST**
- Objetivo: Explorar manifolds 2D da base MNIST usando autoencoders.
- Abordagens:
  - Autoencoders densos (com camadas densas para codificação e decodificação).
  - Autoencoders convolucionais (com downsampling e upsampling).
- **Notebook**: [PC09_P1_AE_MNIST.ipynb](notebooks/PC09_P1_AE_MNIST.ipynb)

---

### **PC10 - Generative Adversarial Networks (GANs)**
- Objetivo: Treinar GANs para gerar dígitos da base MNIST.
- Destaques:
  - Resultados intermediários salvos a cada 1.000 épocas.
  - Extensão para gerar imagens da base CIFAR-10.
- **Notebook**: [PC10_P1_GAN_MNIST.ipynb](notebooks/PC10_P1_GAN_MNIST.ipynb)

---

### **PC11 - Processamento de Linguagem Natural (LSTM)**
- Objetivo: Implementar um modelo Encoder-Decoder baseado em LSTM para mapear uma sequência de entrada em uma sequência de saída (seq2seq).
- Destaques:
  - Aplicação em uma tarefa similar a tradução de frases.
  - Baseado no conceito de predição algébrica.
- **Notebook**: [PC11_PLN_LSTM.ipynb](notebooks/PC11_PLN_LSTM.ipynb)

---

### **PC12 - Aprendizado por Reforço (Deep Q-Learning)**
- Objetivo: Resolver labirintos utilizando aprendizado por reforço com Deep Q-Learning.
- Destaques:
  - Treinamento até convergência em labirintos 5x5.
  - Análise das políticas aprendidas.
- **Notebook**: [PC12_RL_Maze.ipynb](notebooks/PC12_RL_Maze.ipynb)

---

##  Resultados
Exemplos de resultados gerados nos notebooks:
- Gráficos de evolução de perdas e acurácias para GANs e outras redes.
- Visualizações de manifolds em autoencoders.

---

##  Participação
Este projeto foi desenvolvido em parceria com **Beatriz Akiria de Assis Quaresma.**.
