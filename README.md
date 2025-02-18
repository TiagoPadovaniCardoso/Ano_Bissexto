# Aprendizados com o Script em Batch

Este script em Batch foi uma ótima oportunidade para aprender e praticar conceitos importantes de programação, lógica e manipulação de arquivos. Abaixo, destaco os principais pontos que pude absorver:

---

## 📂 **Manipulação de Diretórios**
- Aprendi a criar diretórios dinamicamente usando o comando `mkdir`.
- Utilizei a estrutura `if not exist` para verificar se um diretório já existe antes de criá-lo, evitando erros.
- Naveguei entre diretórios usando `cd` para organizar pastas e subpastas.

---

## 📅 **Lógica de Anos Bissextos**
- Implementei uma lógica para determinar se um ano é bissexto:
  - Um ano é bissexto se for divisível por 4.
  - Exceto se for divisível por 100, a menos que também seja divisível por 400.
- Usei variáveis (`set /a`) para calcular os restos das divisões e determinar o número de dias em fevereiro.

---

## 🔢 **Controle de Fluxo**
- Utilizei condicionais (`if`) para tomar decisões com base em valores de entrada.
- Aprendi a usar `exit /b` para interromper a execução do script caso o mês seja inválido.
- Implementei um loop (`for /l`) para criar pastas correspondentes aos dias do mês.

---

## 📝 **Interação com o Usuário**
- Exibi mensagens claras no console usando `echo` para informar o usuário sobre:
  - Se o ano é bissexto ou não.
  - O número de dias no mês selecionado.
  - O próximo ano bissexto, caso aplicável.

---

## 🛠️ **Boas Práticas**
- Organizei o código em blocos lógicos para facilitar a leitura e manutenção.
- Utilizei comentários (ou mensagens de `echo`) para explicar o que cada parte do código faz.
- Aprendi a importância de validar entradas (como o mês) para evitar erros inesperados.

---

## 💡 **Reflexão**
Esse script me mostrou como a programação em Batch pode ser poderosa para automação de tarefas simples, como criar pastas e organizar arquivos. Além disso, reforçou conceitos importantes de lógica de programação, como condicionais, loops e manipulação de variáveis. Foi um ótimo exercício para praticar pensamento estruturado e resolução de problemas!

---

## 🚀 **Próximos Passos**
- Melhorar o script para aceitar entradas mais flexíveis (como nomes de meses em vez de números).
- Adicionar tratamento de erros para entradas inválidas.
- Explorar outras funcionalidades do Batch, como manipulação de arquivos e integração com outros programas.

---

**Conclusão:** Esse projeto foi uma experiência enriquecedora, e estou animado para aplicar esses conhecimentos em outros desafios! 🎉
