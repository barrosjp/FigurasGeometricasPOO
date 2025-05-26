# 🎯 Figuras Geométricas com Programação Orientada a Objetos

Este projeto tem como objetivo demonstrar os principais conceitos da **Programação Orientada a Objetos (POO)** aplicados ao cálculo de **áreas** e **volumes** de **figuras geométricas planas e espaciais**. A estrutura modular permite fácil entendimento e reutilização de código, organizando os exemplos em diretórios específicos para **Abstração**, **Encapsulamento** e **Herança**.

---

## ⚙️ Conceitos de POO Aplicados

- 🧩 **Abstração**: foca no essencial, ocultando os detalhes de implementação.  
- 🔐 **Encapsulamento**: protege os dados por meio de atributos privados e métodos públicos.  
- 🧬 **Herança**: promove reutilização de código por meio de hierarquia de classes.

---

## 🗂 Estrutura do Projeto

O projeto está dividido em três módulos principais, representando cada conceito de POO:

---

### 📁 `figurasGeometricas - Abstração`

Demonstra como abstrair o comportamento comum das figuras geométricas, com interfaces ou classes abstratas.

**Pacotes:**
- `br.edu.principal` → Contém a classe principal com exemplos de uso.  
- `br.edu.figurasgeometricasplanas` → Figuras planas (Triângulo, Retângulo etc.).

**🔷 Diagrama UML:**  
![Diagrama Abstração](https://github.com/user-attachments/assets/680759c0-c425-4bc8-935a-736292f7537c)

---

### 📁 `figurasGeometricas - Encapsulamento`

Explora como proteger atributos usando modificadores de acesso e métodos `get` / `set`.

**Pacotes:**
- `br.edu.principal`  
- `br.edu.figurasgeometricasplanas`  
- `br.edu.figurasgeometricasespacias`

**🔷 Diagrama UML:**  
![Diagrama Encapsulamento](https://github.com/user-attachments/assets/97535320-bfa7-4d7c-af14-a0544285c153)

---

### 📁 `figurasGeometricas - Herança`

Mostra como classes especializadas podem herdar comportamentos de uma superclasse genérica.

**Pacotes:**
- `br.edu.principal`  
- `br.edu.figurasgeometricasplanas`  
- `br.edu.figurasgeometricasespacias`

**🔷 Diagrama UML:**  
![Diagrama Herança](https://github.com/user-attachments/assets/d94644c8-ee11-4d58-852b-f6f6184e3bed)

---

## 📐 Figuras Geométricas Implementadas

### ✳️ Figuras Planas
- Triângulo  
- Retângulo  
- Quadrado  
- Círculo  
- Trapézio  
- Paralelogramo  
- Losango  
- Pentágono  
- Hexágono

### 🔷 Figuras Espaciais
- Cubo  
- Prisma  
- Esfera  
- Pirâmide  
- Cone  
- Cilindro  
- Paralelepípedo  
- Tetraedro

---

## 🔧 Estrutura das Classes

Todas as figuras seguem a mesma estrutura:

- ✅ Atributos privados  
- ✅ Construtor com parâmetros  
- ✅ Métodos públicos:
  - `calcArea()`
  - `calcVolume()` *(apenas para figuras espaciais)*

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/figurasGeometricasPOO.git
