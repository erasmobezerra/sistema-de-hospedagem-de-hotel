# 🏨 DIO - Sistema de Hospedagem de Hotel
Este desafio de projeto foi desenvolvido na trilha **Dados e Listas com .NET C#**, do Bootcamp **Deal Group AI Centric .NET**. 

## 📚 Contexto
Foi proposto um desafio para construir um sistema de hospedagem, que será usado para realizar uma reserva em um hotel. Há a classe Pessoa, que representa o hóspede, a classe Suíte, e a classe Reserva, que fará um relacionamento entre ambos. O programa deverá calcular corretamente os valores dos métodos da classe Reserva, que precisará trazer a quantidade de hóspedes e o valor da diária. O código foi dado pela metade, e meu objetivo foi dar continuidade obedecendo as regras descritas abaixo a fim de ter um programa utilizável. 

## 📏 Regras e validações
1. ❌ Não deve ser possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Se é uma suíte capaz de hospedar 2 pessoas, então ao passar 3 hóspedes deverá retornar uma exception.
2. 🔢 O método ObterQuantidadeHospedes da classe Reserva deverá retornar a quantidade total de hóspedes, enquanto que o método CalcularValorDiaria deverá retornar o valor da diária (Dias reservados x valor da diária).
3. 💸 Caso seja feita uma reserva igual ou maior que 10 dias, deverá ser concedido um desconto de 10% no valor da diária.

## 🗂️ Estrutura do Projeto

```
DesafioProjetoHospedagem/
├── Models/
│   └── Pessoa.cs
|   └── Reserva.cs
|   └── Suite.cs
├── Program.cs
└── README.md
```

![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## 🛠️ Tecnologias Utilizadas
<div>      
  <img alt="C#" src="https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white&style=for-the-badge" />
  <img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?logo=.net&logoColor=white&style=for-the-badge" />  
</div>  

## ⚙️ Funcionalidades Implementadas
### 🔧 Métodos Principais

| Método | Descrição |
|--------|-----------|
| **CadastrarHospedes()** | Verificar se a capacidade é maior ou igual ao número de hóspedes sendo recebido |
| **ObterQuantidadeHospedes()** | Retorna a quantidade de hóspedes (propriedade Hospedes) |
| **CalcularValorDiaria()** | Retorna o valor da diária |

## 📋 Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas:

- 🔹 **.NET 6.0** ou superior
- 🔹 **IDE**: Visual Studio 2022, VS Code ou similar

## 🚀 Como Executar
```bash
# 1. Clone o repositório
git clone https://github.com/erasmobezerra/sistema-de-hospedagem-de-hotel.git

# 2. Navegue até a pasta do projeto
cd .\sistema-de-hospedagem-de-hotel\

# 3. Execute o projeto
dotnet run
```

## 📬 Contato
<div align="left">

**Erasmo Bezerra**

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:erasmo.ads.tech@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erasmobezerra/)

</div>

---

🙏 Agradeço profundamente à **Digital Innovation One** por proporcionar este aprendizado gratuito e de qualidade. Um reconhecimento especial ao professor **[Leonardo Buta](https://www.linkedin.com/in/leonardo-buta/)** pela excelente didática e orientação durante todo o processo.

<div align="center">
  <p>⭐ Se este projeto foi útil para você, considere dar uma estrela!</p>
</div>
