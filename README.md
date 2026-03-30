# Projeto – Limiarização de Imagens

## Autores
Fabricio da Costa Fernandes (RA: 11202321635)
Felipe de Lima Major (RA: 11202230321)
Lilian Gimenez Teixeira (RA: 11202332321)

## Descrição do Projeto
Este repositório contém o relatório e os códigos desenvolvidos para o estudo de **limiarização de imagens** utilizando Python, OpenCV e Jupyter Notebook.

O objetivo do trabalho é explorar técnicas de segmentação de imagens por limiarização, analisando tanto métodos **manuais** quanto métodos **automáticos**, como o método de **Otsu**, além de realizar experimentos com imagens estáticas e captura em tempo real utilizando webcam.

O relatório foi desenvolvido em formato **Jupyter Notebook (.ipynb)** para permitir a reprodução dos experimentos e a visualização dos resultados diretamente no documento.

---

# Estrutura do Repositório
│
├── relatorio.ipynb
├── README.md
│
├── imagens/
│ ├── teste-para-projeto-I.jpg
│ ├── teste-para-projeto-II.jpg
│
├── codigo/
│ ├── limiarizacao_imagens.py
│ ├── limiarizacao_webcam.py
│
└── resultados/
├── saida.avi


Cada relatório e seus arquivos associados devem estar organizados em uma pasta própria.

---

# Estrutura do Relatório (Notebook)

O relatório segue a estrutura solicitada na disciplina.

## 1. Título do Relatório
Nome do experimento ou laboratório.

## 2. Nome Completo dos Autores
Lista com os integrantes da equipe.

## 3. Data de Realização dos Experimentos
Data em que os testes foram realizados.

## 4. Data de Publicação do Relatório
Data de entrega/publicação no repositório.

---

# Introdução

Nesta seção é apresentada uma breve explicação sobre **limiarização de imagens**, técnica utilizada em processamento de imagens para segmentar regiões de interesse.  

A limiarização consiste em transformar uma imagem em escala de cinza em uma **imagem binária**, separando pixels em duas classes (objeto e fundo) com base em um valor de limiar \(T\).

Também são discutidas as diferenças entre:

- limiarização **manual**
- limiarização **automática**
- método de **Otsu**

---

# Procedimentos Experimentais

Os experimentos realizados incluem:

1. Conversão de imagens para **escala de cinza**
2. Análise do **histograma**
3. Aplicação de **limiarização manual**
4. Aplicação de **limiarização automática (Otsu)**
5. Comparação entre os resultados
6. Implementação de limiarização em **tempo real utilizando webcam**

O código foi desenvolvido em **Python** utilizando as bibliotecas:

- OpenCV
- NumPy
- Matplotlib

Os experimentos podem ser reproduzidos executando as células do notebook.

---

# Análise e Discussão

Nesta parte são discutidos:

- os efeitos da escolha de diferentes valores de limiar
- comparação entre limiarização manual e automática
- análise do histograma das imagens
- artefatos observados nas segmentações
- resultados obtidos no processamento em tempo real com webcam

Também são discutidas situações em que cada método apresenta melhor desempenho.

---

# Conclusões

A limiarização mostrou-se uma técnica simples e eficiente para segmentação de imagens em muitos casos.

Os resultados indicam que:

- a limiarização manual pode funcionar bem quando o histograma é conhecido
- o método de Otsu é útil quando se deseja um processo automático
- variações de iluminação podem impactar os resultados

O experimento com webcam permitiu observar esses efeitos em tempo real.

---

# Referências

- Gonzalez, R. C., Woods, R. E. – **Digital Image Processing**
- Documentação do OpenCV  
  https://opencv.org/
- Material da disciplina

---

# Como Executar o Projeto

1. Clonar o repositório

```bash
git clone <link-do-repositorio>
```
2. Instalar dependências
```
pip install opencv-python numpy matplotlib
```
3. Abrir o notebook
```
jupyter notebook
```
4. Executar o arquivo
```
relatorio.ipynb
```
