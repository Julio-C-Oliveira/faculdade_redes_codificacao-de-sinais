# faculdade_redes_codificacao-de-sinais

Simulador de algoritmos de **codificação de linha e modulação em banda base** na camada física de redes de computadores, desenvolvido no âmbito da disciplina de Redes de Computadores no curso de Ciência da Computação na Universidade Federal do Pará (UFPA).

---

## 🚀 Padrões de Codificação Implementados

1. **4B3T (4 Binary 3 Ternary):**
   - Converte blocos de 4 bits binários em símbolos ternários de 3 níveis (-1, 0, +1), reduzindo a taxa de modulação e o uso de largura de banda no canal.
2. **AMI (Alternate Mark Inversion):**
   - Codificação bipolar com três níveis de tensão: o bit 0 é ausência de sinal (0V) e o bit 1 alterna sucessivamente entre polaridades positiva (+V) e negativa (-V), eliminando a componente DC (*Direct Current*).
3. **Manchester Diferencial:**
   - Modulação bifásica auto-sincronizada. A presença ou ausência de transição no início do período de bit indica o valor lógico (0 ou 1), mantendo transição central mandatória para sincronização de clock.

---

## 🛠️ Tecnologias

- **Python 3.9+**
- **Matplotlib:** Geração das formas de onda e transições de pulso digitais.
- **NumPy:** Vetorização e manipulação de arrays binários.

---

## 📦 Como Executar

```bash
# 1. Clonar repositório
git clone https://github.com/Julio-C-Oliveira/faculdade_redes_codificacao-de-sinais.git
cd faculdade_redes_codificacao-de-sinais

# 2. Criar ambiente virtual e instalar dependências
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

# 3. Executar o simulador
python3 main.py
```

---

## 📄 Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.
