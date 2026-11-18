# 📡 Digital Signal Processing (DSP) & Numerical Simulations in Python

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Notebooks-Google%20Colab-F9AB00.svg?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![Libraries](https://img.shields.io/badge/Stack-NumPy%20%7C%20SciPy%20%7C%20Matplotlib-007ACC.svg)](https://scipy.org/)
[![Field](https://img.shields.io/badge/Engineering-Signal%20Processing-success.svg)](#módulos-e-cadernos-interativos)

Ambiente interativo de simulações computacionais, análise espectral e design de filtros digitais para **Processamento Digital de Sinais (PDS / DSP)** implementado em **Python**.

O projeto contempla implementações práticas, visualização de respostas em frequência, estabilidade no plano complexo e aplicações reais em sistemas de telecomunicações.

---

## 🔬 Tópicos de Engenharia Abordados

* **Análise no Domínio da Frequência e Plano-Z**: Estudo de polos, zeros, região de convergência (ROC) e transformada rápida de Fourier (FFT/DFT).
* **Projeto de Filtros Digitais (FIR & IIR)**: Métodos de janelamento, transformações bilineares e síntese de filtros passa-baixas, passa-altas e passa-faixa.
* **Sistemas de Telecomunicações**: Modulação, filtragem seletiva, atenuação de ruído e processamento de canais de transmissão.
* **Computação Científica**: Vetorização e processamento matricial com **NumPy** e processamento de sinais com **SciPy (`scipy.signal`)**.

---

## 🚀 Módulos e Cadernos Interativos

Cada módulo inclui formulação teórica, simulações algorítmicas, gráficos de resposta e código executável via **Google Colab**:

| Módulo | Descrição Técnica | Notebook Interativo |
| :--- | :--- | :---: |
| **01. Transformada-Z** | Análise de estabilidade, mapeamento de polos/zeros no plano-z e resposta em frequência de sistemas LTI. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vL9B_r4GTMFMq0ZXfw7DRk8SCKTKF5Ks?usp=sharing) |
| **02. Transformada Discreta de Fourier (DFT)** | Análise espectral de sinais discretos, resolução de frequência, vazamento espectral (*leakage*) e algoritmos de FFT. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gZrlkqDhpk4H7tRCYAC23geHyonY6rBt?usp=sharing) |
| **03. Estruturas de Filtros no Tempo** | Implementação de estruturas em tempo discreto (Forma Direta I/II, Cascata e Paralela) e análise de resposta impulsiva. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vB8zM2lPNYJc9yxw3zrdM-4KyounNWCe?usp=sharing) |
| **04. Síntese de Filtros FIR** | Projeto de filtros de fase linear (*Finite Impulse Response*) via técnicas de janelamento (Hamming, Hanning, Blackman). | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qkXPIzKGQGVRGva2Ou46U_pS9K9Llz-P?usp=sharing) |
| **05. Síntese de Filtros IIR** | Projeto de filtros recursivos (*Infinite Impulse Response*) utilizando aproximações Butterworth, Chebyshev e transformação bilinear. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BbmFBzS5CHD3_K5Guj54iBccvwlPmgXn?usp=sharing) |
| **06. Aplicações em Comunicações** | Simulações aplicadas a telecomunicações: modulação digital, filtragem de canal e demodulação de sinais. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OnSmqYAXDFUpYSSjmMHnJhaulnIkco1G?usp=sharing) |

---

## 🛠️ Stack Tecnológica

* **Linguagem**: Python 3.x
* **Bibliotecas Científicas**:
  * `NumPy`: Computação numérica e operações matriciais eficientes.
  * `SciPy` (`scipy.signal`): Síntese de filtros, transformadas e convolução.
  * `Matplotlib`: Visualizações espectrais, diagramas de Bode e diagramas de polos e zeros.
* **Ambiente de Execução**: Jupyter / Google Colaboratory (Cloud GPU/CPU).

---

## 💻 Como Executar Localmente

Caso prefira rodar os cadernos na sua máquina local em vez do Google Colab:

```bash
# 1. Clone o repositório
git clone https://github.com/caiodantass/dsp-python-lab.git
cd dsp-python-lab

# 2. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# 3. Instale as dependências científicas
pip install numpy scipy matplotlib jupyterlab

# 4. Inicie o Jupyter Lab
jupyter lab
```

---

## 👨‍💻 Autor

**Caio Dantas**  
* Engenheiro de Software / Desenvolvedor  
* GitHub: [@caiodantass](https://github.com/caiodantass)  
* LinkedIn: [linkedin.com/in/caiodantass](https://www.linkedin.com/in/caio-l%C3%ADvio/)
