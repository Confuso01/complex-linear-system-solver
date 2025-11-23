# 🔢 Resolvedor de Sistemas Lineares com Números Complexos

Um resolvedor interativo e visual de sistemas lineares que suporta números complexos em formatos retangular e fasorial, com representações gráficas em tempo real.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

##  Características

-  **Suporte completo a números complexos**
  - Formato retangular: `a+bj` (ex: `3+4j`, `2-5j`)
  - Formato fasorial: `M∠θ` (ex: `5∠30`, `10<45`)
  
-  **Matrizes de 2×2 até 6×6**
  - Resolução usando eliminação gaussiana com pivotamento parcial
  - Cálculo automático do determinante
  
-  **Resolução passo a passo**
  - Visualização detalhada do processo de eliminação
  - Substituição retroativa explicada
  
-  **Diagramas visuais**
  - Diagrama Fasorial
  - Diagrama Vetorial
  - Diagrama Poligonal
  
-  **Interface moderna**
  - Modo claro e escuro
  - Design responsivo
  - Animações suaves
  
-  **Duas formas de entrada**
  - Entrada por matriz (A × x = b)
  - Entrada por sistema de equações

##  Como Usar

### 1. Acesso Rápido
Basta abrir o arquivo `index.html` em qualquer navegador moderno. Não requer instalação!

### 2. Entrada de Dados

#### Formato Retangular (a + bj):
```
3+4j   →  3 + 4i
2-5j   →  2 - 5i
-1+3j  →  -1 + 3i
5      →  5 + 0i (número real)
2j     →  0 + 2i (imaginário puro)
```

#### Formato Fasorial (M∠θ):
```
5∠30    →  magnitude 5, ângulo 30°
10<45   →  magnitude 10, ângulo 45°
2ang60  →  magnitude 2, ângulo 60°
```

### 3. Exemplo Prático

**Sistema de equações:**
```
(2+3j)x₁ + (1-j)x₂ = 5+2j
(1+j)x₁ + (3+2j)x₂ = 4-3j
```

**Como inserir:**
1. Selecione matriz 2×2
2. Preencha a matriz A:
   - a₁₁ = `2+3j`
   - a₁₂ = `1-j`
   - a₂₁ = `1+j`
   - a₂₂ = `3+2j`
3. Preencha o vetor b:
   - b₁ = `5+2j`
   - b₂ = `4-3j`
4. Clique em "Resolver Sistema"

## 📋 Funcionalidades Detalhadas

### Configurações Disponíveis

| Opção | Descrição |
|-------|-----------|
| **Tamanho da matriz** | 2×2, 3×3, 4×4, 5×5 ou 6×6 |
| **Casas decimais** | 0 a 40 casas decimais |
| **Passo a passo** | Mostra o processo de resolução detalhado |
| **Diagramas visuais** | Três tipos de representações gráficas |
| **Tipo de entrada** | Matriz ou sistema de equações |
| **Tema** | Modo claro ou escuro |

### Resultados Fornecidos

-  Solução em formato retangular
-  Solução em formato fasorial
-  Determinante da matriz (retangular e fasorial)
-  Verificação da solução (A × x = b)
-  Processo passo a passo (opcional)
-  Representações visuais (opcionais)

##  Aplicações

Este resolvedor é ideal para:
- 📚 Estudantes de engenharia elétrica
- ⚡ Análise de circuitos em regime permanente senoidal
- 🔬 Cursos de álgebra linear
- 📊 Sistemas de controle
- 🎯 Processamento de sinais

##  Tecnologias

- **HTML5** - Estrutura
- **CSS3** - Estilização e animações
- **JavaScript Vanilla** - Lógica e cálculos
- **Canvas API** - Diagramas visuais

## 🛠️ Instalação

Não requer instalação! Mas se quiser clonar:

```bash
git clone https://github.com/seu-usuario/complex-linear-system-solver.git
cd complex-linear-system-solver
```

Abra `index.html` no seu navegador preferido.

## ⚠️ Observações Importantes

- Use **'j'** para a unidade imaginária (não 'i')
- **Não use espaços** nos números complexos
- Ângulos fasoriais devem estar em **graus** (não radianos)
- O sistema deve ter **solução única** (determinante ≠ 0)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📝 Exemplos de Uso

### Exemplo 1: Sistema 2×2 Simples
```
Matriz A:
  2    1
  1    2

Vetor b:
  3
  3

Solução:
  x₁ = 1
  x₂ = 1
```

### Exemplo 2: Sistema com Números Complexos
```
Matriz A:
  1+j     2
  -j      1+2j

Vetor b:
  3+j
  2-j

Clique em "Resolver Sistema" para ver a solução!
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor: Moisés

Desenvolvido com ❤️ para facilitar o aprendizado de sistemas lineares complexos.

## 🌟 Agradecimentos

- A todos que contribuem para o aprendizado de engenharia
- Comunidade open source
- Estudantes e professores que utilizam esta ferramenta

---

** Se este projeto foi útil, considere dar uma estrela!**

** Encontrou um bug? Abra uma issue!**

** Tem uma sugestão? Contribua com o projeto!**
