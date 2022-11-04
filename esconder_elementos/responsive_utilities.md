VISIBLE | HIDDEN

Extra small devices
Phones (<768px) 
.visible-xs-*   | .hidden-xs	


Small devices
Tablets (≥768px)
.visible-sm-*	| .hidden-sm	

Medium devices
Desktops (≥992px)
.visible-md-*	| .hidden-md	

Large devices
Desktops (≥1200px)
.visible-lg-*	| .hidden-lg	

Group of classes	           |     CSS display
                               
.visible-*-block	           |     display: block;
.visible-*-inline	           |     display: inline;
.visible-*-inline-block        |     display: inline-block;

So, for extra small (xs) screens for example, the available 
.visible-*-* classes are: .visible-xs-block
                          .visible-xs-inline
                          .visible-xs-inline-block.

<section id="servicos" class="visible-xs-block visible-sm-block">
toda seção de conteudos se torna visivel apenas para xs e sm

<section id="servicos" class="hidden-xs">
não exibe mais o conteúdo para dispositivos menores