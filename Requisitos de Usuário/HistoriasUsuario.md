# 1. História de Usuário

A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas. 

<table>
    <thead>
        <tr style="background-color: purple; color: white" >
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">RF/RNF relacionado</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Story Points</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero poder decidir se quero apenas realizar um sorteio ou uma aposta sem barreiras ou atrasos, para assim, satisfazer minha vontade do momento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>Apresentar, de forma simples, as opções ao usuário para que ele possa tomar uma decisão.</li>
                <li>Destacar qual a modalidade escolhida [aposta ou sorteio].</li>
                <li>Após o uso, deve ser claro a modalidade que estava em uso, para que o usuário decida se continuará com a mesma opção.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 5 </td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero poder visualizar e editar minhas configurações de privacidade, para ter controle sobre quais informações o sistema pode armazenar e como elas são utilizadas.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>O usuário deve poder visualizar quais dados estão sendo armazenados.</li>
                <li>As mudanças devem ser aplicadas imediatamente após a confirmação do usuário.</li>
                <li>Caso o usuário tente sair da seção sem salvar as alterações, o sistema deve exibir uma mensagem de confirmação.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 34 </td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, quero ver uma animação fluida durante o giro da roleta, para que a experiência seja divertida e envolvente, aumentando meu interesse em continuar usando o site.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>A roleta deve girar com animação suave e responsiva em diferentes dispositivos.</li>
                <li>A duração do giro deve ser razoável (ex: entre 3 e 6 segundos).</li>
                <li>A animação deve finalizar com destaque visual para o prêmio ou resultado.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Média</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RNF03, RF03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 21 </td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário, quero escolher um número e uma cor, para que eu possa fazer uma aposta.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>O sistema deve permitir escolher um número e uma cor antes de girar a roleta.</li>
                <li>Após o giro da roleta, o sistema deve exibir de forma clara e imediata o número sorteado, a cor sorteada e o resultado da aposta (ganhou ou perdeu).</li>
                <li>Quando o usuário acerta o número e a cor, o sistema deve dobrar automaticamente o valor fictício apostado e atualizar o saldo na tela.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 3 </td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário, quero escolher qual o valor inicial fictício que desejo começar.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>O sistema deve permitir escolher o valor inicial e mostrá-lo de forma clara.</li>
                <li>O sistema deve permitir escolher qual o valor que vou usar em cada aposta.</li>
                <li>Após o resultado da roleta, o sistema deve atualizar o valor fictício com ganhos ou perdas.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF01, RF02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 8 </td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Como usuário, quero acessar facilmente as regras e instruções da roleta, para que eu entenda como funciona antes de apostar ou jogar.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">
              <ol>
                <li>Deve haver um botão ou link visível, como "Regras" ou "Ajuda".</li>
                <li>Ao clicar, deve abrir uma tela, modal ou pop-up com informações simples sobre: como funciona o giro da roleta, como fazer apostas e como são calculados os ganhos.</li>
                <li>O usuário deve conseguir fechar essa tela e voltar para o jogo sem perder seu progresso.</li>
              </ol>
            </td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Baixa</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"> 5 </td>
        </tr>
    </tbody>
</table>

<div style="text-align: center">
<p>Tabela 3: História de Usuário</p>
</div>
