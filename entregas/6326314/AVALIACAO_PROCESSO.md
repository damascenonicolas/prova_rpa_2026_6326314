# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/6326314/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** A

1. **Nome do processo e descrição resumida:**
   Organização Diária de Comprovantes em PDF. O processo consiste em ler arquivos PDF de comprovantes recebidos, extrair a data e o número do documento a partir do nome original do arquivo e renomeá-los seguindo um padrão rigoroso e fixo de nomenclatura antes de movê-los para a pasta de arquivamento definitiva.

2. **Volume / frequência estimados:**
   Frequência diária, com um volume estimado de 150 a 200 comprovantes em PDF processados ao final de cada dia útil.

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Sim. Os arquivos de entrada são do mesmo tipo (PDF) e trazem as informações necessárias (data e número do documento) dispostas de forma padronizada diretamente em seus nomes de arquivo, permitindo a extração dos dados sem ambiguidade.

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Sim. O processo segue uma regra de negócio totalmente fixa, baseada em lógica booleana e caminhos definidos (se o arquivo contiver o padrão, renomeia; se não, move para exceção). Não há espaço para julgamento subjetivo, interpretação ou tomada de decisão humana.

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras claras, dados estruturados e repetibilidade)
   Sim, o processo é altamente elegível a RPA. Ele atende perfeitamente aos três pilares da automação: possui dados de entrada estruturados e previsíveis (arquivos PDF com nomes padronizados), baseia-se em regras 100% claras e determinísticas (regra de nomenclatura fixa sem subjetividade) e apresenta alta repetibilidade, sendo executado manualmente de forma idêntica todos os dias.
