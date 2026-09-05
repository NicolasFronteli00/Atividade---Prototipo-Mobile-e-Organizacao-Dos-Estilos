# Atividade---Prototipo-Mobile-e-Organizacao-Dos-Estilos

Integrantes 

-Ariel Wilmer Condori Mamani
-Enzo Castanheira
-Laura Victoria De Azevedo Rodrigues 
-Nicolas Fronteli Freitas 


Sobre o Projeto

Este projeto é uma adaptação para uma interface mobile de uma aplicação já existente.
Foram fornecidas 14 telas e seu fluxo de navegação, e a partir delas foi feita uma análise para identificar os elementos como possíveis componentes reutilizáveis, considerando suas estruturas e variações. Em seguida foram desenvolvidas 14 wireframes mobile de baixa fidelidade utilizando o padrão BEM para organização dos estilos CSS.


Telas 

-Tela 01 - Página Inicial
-Tela 02 - Categoria Techno
-Tela 03 - Destaques 
-Tela 04 - Assinar Newsletter
-Tela 05 - Administração de Categorias 
-Tela 06 - Criação de Postagem
-Tela 07 - Escolhas do Editor
-Tela 08 - Gerenciamento de Usuários 
-Tela 09 - Fila de Revisão 
-Tela 10 - Fila de Comentários 
-Tela 11 - Resultados de Busca
-Tela 12 - Login
-Tela 13 - Criar Conta 
-Tela 14 - Gerenciar Perfil


Componentes Identificados e Variações

Componente | Onde aparece | Variações |

Header | Todas as telas públicas | única (logo + ações + menu) |
Button | Todas as telas | `--primary`, `--secondary`, `--outline`, `--disabled`, `--small`, `--block` |
Card | Home, Categoria, Destaques, Busca | padrão, `--compact` (categorias), `--highlight` (destaque), `--horizontal` |
Form | Login, Cadastro, Newsletter, Criar Post, Perfil | campos de texto, textarea, checkbox |
List | Categoria, Destaques, Busca, todas as telas admin, Perfil | `--with-image` (busca e perfil) |
Admin menu | Todas as telas administrativas (05–10) | única |
Stats | Todas as telas administrativas (05–10) | única |
Tag | Home (categorias), Categoria (filtros) | `--active` |
Profile avatar | Perfil | única |
Footer | Todas as telas | única |


Organização dos Arquivos

|-- wireframes/

    | -- Tela_01.png
    | -- Tela_02.png
    | -- Tela_03.png
    | -- Tela_04.png
    | -- ...
    | -- Tela_14.png

|-- css/

    |-- admin.css
    |-- base.css
    |-- button.css
    |-- card.css
    |-- footer.css
    |-- form.css
    |-- list.css
    |-- navigation.css
    |-- profile.css
    |-- tag.css
    |-- variables.css











    
 







