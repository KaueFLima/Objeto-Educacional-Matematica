# Objeto Educacional: Analisador de Inequações do 2º Grau

Este projeto consiste em um **Objeto Educacional** desenvolvido como atividade avaliativa para a disciplina de **Matemática** do curso de **Bacharelado em Inteligência Artificial**. 

O objetivo principal é fornecer uma ferramenta visual, interativa e didática para auxiliar alunos do Ensino Fundamental II e Ensino Médio na compreensão e determinação do **conjunto solução de uma inequação do segundo grau**.

**Professor Orientador:** Me. João Eichenberger Neto  

---

## Objetivos Pedagógicos

A transição do estudo de equações para inequações costuma ser um desafio para estudantes do ensino básico. Este software foi projetado para mitigar essa dificuldade através de:
* **Visualização Geométrica:** Conectar a álgebra abstrata à geometria da parábola, mostrando claramente o significado dos sinais de maior ($>$), menor ($<$), maior ou igual ($\ge$) e menor ou igual ($\le$).
* **Feedback Imediato:** Permitir que o estudante altere os coeficientes e veja instantaneamente a mudança nas raízes e na região sombreada do gráfico.
* **Estímulo à Autonomia:** Um espaço de customização de cores que torna a ferramenta mais amigável, interativa e atraente para o público jovem.

---

## Funcionalidades

* **Cálculo Automatizado de Raízes:** Identificação rápida do discriminante ($\Delta$) e das raízes reais por meio da Fórmula de Bhaskara.
* **Plotagem Dinâmica:** Gráfico interativo que destaca visualmente (via sombreamento) a área que atende à restrição da inequação.
* **Exibição do Conjunto Solução:** Apresentação do conjunto formal da resposta de forma matemática (ex: $S = \{x \in \mathbb{R} \mid x_1 < x < x_2\}$, $S = \mathbb{R}$ ou $S = \emptyset$).
* **Explicação em Linguagem Natural:** Tradução do resultado matemático para uma breve explicação em texto corrido, facilitando a leitura de alunos iniciantes.
* **Personalização Visual:** Menus suspensos para alterar as cores da linha da função e da área sombreada da solução.

---

## Tecnologias Utilizadas

O sistema foi desenvolvido inteiramente em **Python**, utilizando as seguintes bibliotecas:
* **[CustomTkinter](https://github.com/TomSchimansky/CustomTkinter):** Para a criação de uma interface gráfica (GUI) moderna, responsiva e com suporte a modo escuro/claro nativo.
* **[Matplotlib](https://matplotlib.org/):** Responsável pela geração, renderização e plotagem dinâmica dos gráficos matemáticos.
* **[NumPy](https://numpy.org/):** Utilizado para a manipulação eficiente dos vetores numéricos que geram a curva da parábola.

---

## Como Executar o Projeto

### Pré-requisitos
Certifique-se de ter o Python 3.x instalado em sua máquina.

### 1. Clonar o Repositório

```bash
git clone [https://github.com/brendolalves/Objeto-Educacional-Matematica.git](https://github.com/brendolalves/Objeto-Educacional-Matematica.git)
cd Objeto-Educacional-Matematica
````


**2\. Criar e Ativar Ambiente Virtual**

```bash
# No Windows:
python -m venv venv
.\venv\Scripts\activate

# No Linux/MacOS:
python3 -m venv venv
source venv/bin/activate
````

**3\. Instalar as Dependências**

```bash
 pip install customtkinter matplotlib numpy 
````
**4\. Executar o Aplicativo**

```bash
python main.py
````
**Licença**

Este projeto é de caráter estritamente acadêmico e educacional, distribuído sob a licença MIT. Sinta-se livre para clonar, estudar e sugerir melhorias\!
