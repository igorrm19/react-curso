# React + TypeScript + Vite

`Uso do CSS, styled-components para o desenvolvimento codigos css para componentes.

instalação com npm, ``` npm install styled-components```

um exemplo do meu codigo


``` import styled from "styled-components";
    export const BackGroundImage = styled.img`
     left: 0;
     top:0;
     position: relative; 
 `;```

Dessa forma podemos ultilizar estilizações css em outras partes do codigo
Por exemplo usando uma estilização que muda a cor de um titulo para vermelho podemos fazer

``` function App() {


  return (
    <>
     <Titulo>
       <LoginScreen />
     </Titulo>
    </> 
  ) ```

No qual o componente titulo tem a estilização de cor vermelha e o componente <LoginScreen /> é um h1 escrito hello word

export const Titulo = styled.h1`
  color: white;
`; 



Documentação do  styled components:
https://styled-components.com/docs/basics#motivation
