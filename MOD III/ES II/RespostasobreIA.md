# Atividade Avaliativa – Engenharia de Software Orientado à IA  
**Nome:** Kayki Ivan, Kayky Rodrigues, Gleison Oliveira, Vinycius Huellyson e Fernando Sena
**Disciplina:** Engenharia de Software II  
**Professor:** Willyams Saraiva  

---

## 1. Qual a principal diferença entre o ciclo de vida tradicional e o de IA?

No ciclo tradicional de software, a gente escreve regras e o sistema só faz o que a gente manda. Já no de IA, a gente ensina a máquina a aprender com dados. Ou seja, em vez de regras fixas, o comportamento do sistema depende do que ele aprendeu nos dados.

---

## 2. Dois problemas que podem surgir se os dados forem ruins:

1. **IA com preconceito**: se os dados tiverem algum tipo de injustiça, tipo desigualdade, a IA vai repetir isso.  
2. **Resultados errados**: se os dados estiverem incompletos ou mal organizados, o sistema vai errar nas previsões ou recomendações.

---

## 3. Caso Amazon – Sistema de recomendação com IA

### a) Quais partes da engenharia de software estão envolvidas?

- Backend (para conectar tudo)
- Banco de dados e tratamento de dados
- Criação e treino do modelo de IA
- Interface (mostrar as recomendações pro usuário)
- Monitoramento pra garantir que o sistema funcione bem

---

### b) Quais são os desafios?

1. Ter que atualizar o modelo toda hora  
2. Lidar com um monte de dados ao mesmo tempo  
3. Fazer o sistema rodar rápido, mesmo com muita gente usando  
4. Cuidar do modelo pra não errar feio (como recomendar coisa nada a ver)

---

### c) Como a engenharia pode ajudar a resolver?

- Automatizando tudo com MLOps  
- Separando as partes do sistema (arquitetura por microsserviços)  
- Testando sempre pra evitar erros  
- Monitorando o sistema com métricas claras  
- Documentando tudo e usando controle de versão

---

## 4. Área escolhida: **Detecção e correção de bugs com IA**

### a) Que tipo de IA é usada aqui?

Geralmente é **IA supervisionada** que aprendeu com milhões de códigos e usa redes neurais ou LLMs (tipo o que o Copilot usa).  

---

### b) Ferramenta real que faz isso:

- **GitHub Copilot**  
- **Amazon CodeGuru**  
- **DeepCode**

---

### c) Como isso funciona e o que tem de bom/ruim?

A IA analisa o código e já sugere correções ou melhorias. Ajuda muito no dia a dia, principalmente em código repetitivo ou erros comuns.

**Vantagens**:
- Corrige mais rápido  
- Evita bugs antes mesmo de rodar  
- Economiza tempo

**Desvantagens**:
- Pode sugerir coisa errada  
- Nem sempre entende o que você quer fazer  
- Ainda precisa da gente pra revisar

---

### d) Demonstração (exemplo Copilot):

```python
def dividir(a, b):
    try:
        return a / b
    except ZeroDivisionError:
        return "Erro: divisão por zero"
```

O Copilot sugere esse `try/except` sozinho quando vê que pode ter divisão por zero. Isso ajuda muito no dia a dia.

---