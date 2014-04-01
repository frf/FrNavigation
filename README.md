FrNavigation
=======

** O que é FrNavigation ? **

FrNavigation é um módulo para navegação baseado em Zend Framework 2

** O que exatamente faz FrNavigation ? **

FrNavigation foi criado com fins educacionais para demonstrar como navegação pode ser feito. Ele é totalmente funcional.

instalação
============

Instalação via composer é suportado, apenas certifique-se que você definiu `` ` " para a estabilidade mínima ":" dev " ```
em seu `` ` composer.json ``` arquivo e depois disso prazo `` ` php composer.phar exigem coolcsn / CSN- navegação : dev -master ```

Vá para a sua configuração do aplicativo em `` ` . / Config / application.config.php ``` e adicione ' FrNavigation ' .
Um exemplo de configuração de aplicativo poderia parecer com o seguinte :

`` `
'módulos' => array (
    'Application' ,
    'FrNavigation'
)
`` `

configuração de navegação
=============

Copiar ` . / Vendor / frnavigation / FrNavigation / config / navigation.global.php.dist ` para
   ` . / config / autoload / navigation.global.php ` e editar.

Mostrar navegação
=============
Adicione esta em algum lugar em seu layout `/ módulo / Aplicação / view / layout / layout.phtml ` . :

`` `
<?php echo $ this->navegação('navegação')->menu(); ?>
`` `
