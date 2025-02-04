# Formatação de Texto em Markdown no GitHub

## 1. Títulos
Use `#` para criar títulos de diferentes níveis:

```markdown
# Título Nível 1
## Título Nível 2
### Título Nível 3
#### Título Nível 4
##### Título Nível 5
###### Título Nível 6
```
# Título Nível 1
## Título Nível 2
### Título Nível 3
#### Título Nível 4
##### Título Nível 5
###### Título Nível 6

## 2. Ênfase

- **Negrito:** `**texto**` ou `__texto__` → **texto**
- *Itálico:* `*texto*` ou `_texto_` → *texto*
- ~~Tachado:~~ `~~texto~~` → ~~texto~~

## 3. Listas

### Lista não ordenada
```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
```
Resultado:
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2

### Lista ordenada
```markdown
1. Primeiro item
2. Segundo item
   1. Subitem 2.1
   2. Subitem 2.2
```
Resultado:
1. Primeiro item
2. Segundo item
   1. Subitem 2.1
   2. Subitem 2.2

## 4. Citações
```markdown
> Este é um bloco de citação.
> Pode conter várias linhas.
```
Resultado:
> Este é um bloco de citação.
> Pode conter várias linhas.

## 5. Código

### Código inline
Use crase (`) para código inline:  
```markdown
Aqui está um exemplo de `código inline`.
```
Resultado: Aqui está um exemplo de `código inline`.

### Bloco de código

Cerque o código com três crases (```) e especifique a linguagem (opcional):
```markdown
```python
print("Olá, mundo!")
```
```
Resultado:
```python
print("Olá, mundo!")
```

## 6. Links

```markdown
[Texto do link](https://www.exemplo.com)
```
Resultado: [Texto do link](https://www.exemplo.com)

## 7. Imagens

```markdown
![Texto alternativo](OIP.jpg)
```
Resultado:  
![Texto alternativo](caminho da imagem)

<!-- ![Texto alternativo](image2.gif) -->

## 8. Tabelas
```markdown
| Cabeçalho 1 | Cabeçalho 2 |
|------------|------------|
| Dado 1     | Dado 2     |
| Dado 3     | Dado 4     |
```
Resultado:
| Cabeçalho 1 | Cabeçalho 2 |
|------------|------------|
| Dado 1     | Dado 2     |
| Dado 3     | Dado 4     |

## 9. Linha Horizontal
Use três traços `---` ou três asteriscos `***` para criar uma linha horizontal.
```markdown
---
```
Resultado:
---
ou
***

## 10. Tarefas (Checkbox)
```markdown
- [x] Tarefa concluída
- [ ] Tarefa pendente
```
Resultado:
- [x] Tarefa concluída
- [ ] Tarefa pendente
