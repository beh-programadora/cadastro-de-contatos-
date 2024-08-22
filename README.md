# Gerenciador de Contatos Simples

Este é um gerenciador de contatos simples em Python. O programa permite adicionar, exibir e remover contatos da lista de contatos. Cada contato é composto por um nome, telefone e email.

## Funcionalidades

- Adicionar novos contatos com nome, telefone e email.
- Exibir todos os contatos cadastrados.
- Remover contatos da lista pelo nome.

## Requisitos

- Python 3.x

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2.Navegue até o diretório do projeto
cd nome-do-repositorio
3.Execute o script Python:
python gerenciador_de_contatos.py
Exemplo de Uso
# Adicionando contatos
adicionar_contato("Alice", "1234-5678", "alice@example.com")
adicionar_contato("Bob", "8765-4321", "bob@example.com")

# Exibindo contatos
print("Contatos cadastrados:")
exibir_contatos()

# Removendo um contato
remover_contato("Alice")

# Exibindo contatos após remoção
print("\nContatos após remoção:")
exibir_contatos()
Saída esperada:
Contatos cadastrados:
Nome: Alice, Telefone: 1234-5678, Email: alice@example.com
Nome: Bob, Telefone: 8765-4321, Email: bob@example.com

Contatos após remoção:
Nome: Bob, Telefone: 8765-4321, Email: bob@example.com
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Licença
Este projeto é licenciado sob a MIT License.
