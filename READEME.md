# Anotações realizadas durante a criação o projeto

- Mobile first
    - criar primeiro o modelo para o mobile e depois para a web desktop.

- Na responsividade se utiliza unidades de medidas flexíveis
    - REM = Root EM
        - Este unidade de medida equivale a 
          1rem = 16px
        
        ```bash
        Exemplo, para utilizar esta unidade de medida em seu projeto:  
          font-size: 62.5%; = 10px
        ```
        
    - Media Queries = @media
        - Limita o escopo das folhas de estilo usando media features, tal como largura, altura e cor;
        Media queries, adicionadas no CSS3, deixam a apresentação do conteúdo adaptado a uma gama especifica de dispositivos não precisando mudar o conteúdo em si;
        
        ```bash
        Exemplo:
          @media (min-width/max-width: 40em) {
            body {
              background-color: black;
            }
          }
        /* O "em" indica a unidade de medida da página Web. */
        ```
        
- > = indica que é para pegar a primeira tag div dentro da tag main.
    
    ```bash
    Exemplo:
    main > div {
    
    }
    ```
    
- + = Pega toda tag li anterior a tag ul e li.
    ```bash
    ul li + li {

    }
    ```