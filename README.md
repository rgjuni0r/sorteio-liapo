### README - Sorteio LIAPO

---

## Visão Geral

Bem-vindo ao repositório do **Sorteio LIAPO**. Este projeto foi desenvolvido para realizar sorteios de maneira eficiente, interativa e visualmente atraente. A aplicação utiliza tecnologias modernas como Bootstrap para estilização e responsividade, além de JavaScript para animar o processo de sorteio, garantindo uma experiência fluida e dinâmica.

## Estrutura do Projeto

O projeto é composto por um único arquivo HTML que integra todos os componentes necessários para executar o sorteio diretamente no navegador. Não há necessidade de configuração adicional ou dependências externas além do que já está embutido no código.

### Componentes Principais:

1. **Bootstrap**: Utilizado para garantir uma interface responsiva e moderna. A biblioteca facilita a organização dos elementos da página, mantendo uma estética limpa e organizada em diferentes dispositivos.
   
2. **Canvas Confetti**: Uma biblioteca leve para efeitos de confetes, adicionando um toque festivo ao final de cada sorteio.

3. **JavaScript**: Controla a lógica do sorteio, gerencia as animações e manipula a interface do usuário de maneira interativa.

4. **HTML/CSS**: Estrutura e estiliza o layout da página, com atenção aos detalhes para uma apresentação visual consistente e profissional.

## Funcionalidades

### 1. **Sorteio Interativo**
   - O usuário pode definir um intervalo de números e excluir números específicos do sorteio.
   - Durante o sorteio, uma bolinha animada gira com os números, simulando um processo de sorteio aleatório que começa rápido e desacelera gradualmente até que o número sorteado seja revelado.
   - Após o sorteio, o número vencedor é exibido, e um efeito de confete celebra o resultado.

### 2. **Elementos Responsivos e Dinâmicos**
   - A interface é completamente responsiva, ajustando-se a diferentes tamanhos de tela, desde dispositivos móveis até desktops.
   - Durante o sorteio, todos os elementos da interface, exceto a bolinha animada, são temporariamente ocultados para focar a atenção do usuário no processo de sorteio.

### 3. **Estética e Personalização**
   - Cores e estilos foram escolhidos para refletir a identidade visual da LIAPO, com uma predominância de tons roxos.
   - A interface inclui um footer personalizado com informações de direitos autorais e crédito ao desenvolvedor.

## Como Usar

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/sorteio-liapo.git
   cd sorteio-liapo
   ```

2. **Abra o Arquivo HTML**:
   - Navegue até o diretório onde o repositório foi clonado e abra o arquivo `sorteio-liapo.html` em seu navegador de preferência.

3. **Configuração do Sorteio**:
   - Preencha os campos de número mínimo, número máximo, e números excluídos (se houver).
   - Clique no botão "Sortear" para iniciar o processo.

4. **Visualizar o Resultado**:
   - Observe a bolinha sorteando os números. Após 10 segundos, o número vencedor será revelado com uma animação especial de confetes.

5. **Personalização**:
   - Caso deseje modificar o intervalo ou os números excluídos, basta ajustar os campos e realizar um novo sorteio.

## Estrutura do Código

### Cabeçalho HTML (`<head>`):
   - Inclui os links para o Bootstrap e a biblioteca Canvas Confetti.
   - Define o estilo padrão da página, como cores, alinhamento de texto e animações.

### Corpo da Página (`<body>`):
   - **Título e Imagem**: Exibe o título do sorteio e o logotipo da LIAPO.
   - **Formulário**: Contém os inputs para definir os parâmetros do sorteio.
   - **Animação**: A bolinha de sorteio centraliza a atenção do usuário durante o sorteio.
   - **Footer**: Contém os créditos e links de contato.

### Scripts:
   - Controlam a lógica de sorteio, incluindo a seleção aleatória de números e a animação da bolinha.
   - Gerencia a exibição dos confetes após o sorteio.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias ou correções.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.

## Contato

Para dúvidas ou sugestões, entre em contato através do [e-mail](mailto:suporte@abcensina.com.br) ou visite nosso [site](https://abcensina.com.br).

---

Este projeto foi desenvolvido com dedicação para oferecer uma solução de sorteio simples, porém eficaz e visualmente atrativa. Espero que você goste e que ele atenda às suas necessidades. 

Atenciosamente,

**Rogério Moreira Alves Júnior**  
*Desenvolvedor Full Stack | CEO da abc Ensina*
