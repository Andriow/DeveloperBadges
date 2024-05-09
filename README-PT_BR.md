# Developer Badges
Um sistema de reconhecimento baseado em badges do git para que os usuários possam expor suas conquistas, e ao mesmo tempo que seja de forma auditável através de uma forma pública no GIT de reconhecimentos. 

# Lista de badges e suas explicações:
Nome | Exemplo | Descrição
:---:|:-------:|:--------:
MVP | ![Static Badge](https://img.shields.io/badge/MVP-2023--12--31-blue) | Most Valuable Player - Melhor desenvolvedor do time no período.

# Como reconhecer outras pessoas
Para isso você deverá fazer um fork do presente repositório e alterar o arquivo badges.md adicionando lá os reconhecimentos que você realizar, será através desse arquivo que a comunidade poderá auditar o reconhecimento. 

No arquivo badge.md você poderá separar os reconhecimentos da forma que fique mais confortável para sua manutenção e facilitando a sua gestão. 

As badges deverão obrigatoriamente seguir o padrão do [shields.io](https://shields.io/badges/static-badge), utilizando o padrão de static-badges, utilizando como label o nome da badge junto com a data em que essa badge foi concedida no formato YYYY-MM-DD. como no exemplo a baixo:

![Static Badge](https://img.shields.io/badge/Example-2023--12--31-blue)

Além de conter a badge, o arquivo badges.md também deverá conter instruções para uso da badge da seguinte maneira, sempre lembrando de alterar o link da imagem para o seu fork, para que fique possível de auditar o envio do reconhecimento.

### Formato:
'BADGE' to 'github da pessoa que recebeu o reconhecimento'
````
Bloco de código para que a pessoa possa utilizar a badge em markdown e em HTML
````

### Exemplo: 
![Static Badge](https://img.shields.io/badge/Example-2023--12--31-blue) to [Andriow](https://github.com/Andriow) 
````
[![Static Badge](https://img.shields.io/badge/Example-2023--12--31-blue)](https://github.com/Andriow/DeveloperBadges/badges.md)

<a href='https://github.com/Andriow/DeveloperBadges/badges.md'><img alt="Static Badge" src="https://img.shields.io/badge/Example-2023--12--31-blue"></a>
````
# Como utilizar as badges
A badge recebida pode ser utilizada em qualquer local que aceite código markdown ou HTML, uma sugestão é de utilizar no seu portfolio ou página de perfil no github, mas também podem ser utilizadas em assinaturas em projetos do github ou outras ferramentas.

Para utilização basta copiar o código da badge da página badges.md da pessoa que concedeu a badge para você e utilizar no local em que preferir, lembrando sempre de adicionar o link de auditoria, para que todos saibam que foi um reconhecimento legítimo.

### Exemplo: 
[![Static Badge](https://img.shields.io/badge/Example-2023--12--31-blue)](https://github.com/Andriow/DeveloperBadges/badges.md)