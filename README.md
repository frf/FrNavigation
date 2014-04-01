FrNavigation
=======

** O que é FrNavigation ? **

FrNavigation é um módulo para navegação baseado em Zend Framework 2

** O que exatamente faz FrNavigation ? **

FrNavigation foi criado com fins educacionais para demonstrar como navegação pode ser feito. Ele é totalmente funcional.

Instalação
============

Instalação via composer é suportado, apenas certifique-se que você definiu `"minimum-stability": "dev"`
em seu arquivo `composer.json` e depois disso  `php composer.phar require frf/fr-navigation:dev-master`

Vá para a sua configuração do aplicativo em `./config/application.config.php` e adicione 'FrNavigation' .
Um exemplo de configuração de aplicativo poderia parecer com o seguinte :

'módulos' => array (
    'Application' ,
    `'FrNavigation'`
)

Configuração de navegação
=============


Usando o Linux copie: ` cp vendor/frf/fr-navigation/config/navigation.global.php.dist config/autoload/navigation.global.php`.

Mostrar navegação
=============
Adicione esta em algum lugar em seu layout `/módulo/Aplication/view/layout/layout.phtml` . :

`<?php echo $ this->navigation('navegação')->menu(); ?>`
