# Configuração do Node.js e SASS

## Node.js

Este repositório fornece instruções para a compreensão e instalação do Node.js, bem como a definição e instalação do pacote SASS (Syntactically Awesome Stylesheets).

### Introdução ao Node.js

O Node.js é uma plataforma que possibilita a execução de código JavaScript no lado do servidor, sendo ideal para o desenvolvimento de aplicações escaláveis e de alta performance.

### Instalação do Node.js

1. Acesse o [site oficial do Node.js](https://nodejs.org/).
2. Faça o download da versão recomendada para o seu sistema operacional.
3. Execute o instalador e siga as instruções do assistente.
4. Após a instalação, abra o terminal e digite `node -v` para verificar a instalação.

## Compreensão e Configuração do SASS e SCSS

Este guia oferece instruções para compreender e diferenciar a sintaxe do SASS e SCSS, configurar o uso do SASS, compilar código SASS em código CSS e gerenciar dependências e pacotes.

### Sintaxe do SASS e SCSS

O SASS (Syntactically Awesome Stylesheets) e o SCSS são extensões do CSS que adicionam funcionalidades avançadas. Enquanto o SASS utiliza uma sintaxe mais concisa, o SCSS adota uma abordagem mais próxima do CSS padrão.

### Configuração do SASS

#### Instalação do Node.js

Certifique-se de ter o Node.js instalado no seu sistema. Siga as instruções no [site oficial do Node.js](https://nodejs.org/).

#### Instalação do SASS

1. Abra o terminal.
2. Digite `npm install -g sass` para instalar globalmente o pacote SASS.
3. Após a instalação, você pode criar arquivos SASS com a extensão `.scss` e compilá-los usando `sass input.scss output.css`.
4. Utilize o SASS para escrever estilos de forma eficiente e organizada em seus projetos.

### Compilação de Código SASS

1. **Criação de Arquivos:**
   - Utilize a extensão `.sass` para SASS ou `.scss` para SCSS ao criar seus arquivos.

2. **Compilação:**
   - Para SASS: `sass input.sass output.css`
   - Para SCSS: `sass input.scss output.css`

### Gerenciamento de Dependências

- Utilize o arquivo `package.json` para listar dependências e suas versões.
- Instale dependências usando o comando `npm install`.
- Gerencie pacotes com o NPM (Node Package Manager).

# Utilização de Variáveis, Encapsulamento e Compilação Automática no SASS

Este guia apresenta instruções sobre como criar e utilizar variáveis no SASS para armazenar valores, encapsular regras e seletores, e configurar a compilação automática do código SASS para CSS.

## Variáveis no SASS

As variáveis no SASS permitem armazenar valores que podem ser reutilizados em todo o código. Para criar e utilizar variáveis:

```scss
// Exemplo de variável
$cor-primaria: #3498db;

// Utilização da variável
elemento {
  color: $cor-primaria;
}
```

## Encapsulamento de Regras e Seletores

O SASS facilita o encapsulamento de regras e seletores para uma melhor organização do código. Utilize aninhamento para encapsular:

```scss
// Exemplo de encapsulamento
seletor-pai {
  propriedade: valor;

  seletor-filho {
    propriedade: valor;
  }
}
```

## Compilação Automática do Código SASS para CSS

Para configurar a compilação automática do código SASS para CSS, utilize a linha de comando ou ferramentas como Gulp ou Webpack. Exemplo usando a linha de comando:

1. Abra o terminal.
2. Navegue até o diretório do seu projeto.
3. Execute o comando:

   ```bash
   sass --watch arquivo-sass.scss:arquivo-css.css
   ```

   Isso monitorará alterações no arquivo SASS e automaticamente compilará para CSS.

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou correções, abrindo uma issue ou enviando um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).