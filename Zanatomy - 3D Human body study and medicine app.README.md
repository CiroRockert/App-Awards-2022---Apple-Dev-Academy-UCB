# App-Awards-2022---Apple-Dev-Academy-UCB
Como primeiro professor da SEEDF a levar 40 alunos em 2019 para Apple Developer Academy e em 2022 com mais 30 estudantes e um app na Googleplay e App Store. 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
    <title></title>

    
    
    <script src="lib/ionic/js/ionic.bundle.js"></script>

    <!-- cordova script (this will be a 404 during development) -->
    <script src="cordova.js"></script>

    <!-- IF using Sass (run gulp sass first), then uncomment below and remove the CSS includes above
    <link href="css/ionic.app.css" rel="stylesheet">
    -->

    <link href="css/ionic.app.css" rel="stylesheet">

    <style type="text/css">
      .platform-ios .manual-ios-statusbar-padding{
        padding-top:20px;
      }
      .manual-remove-top-padding{
        padding-top:0px; 
      }
      .manual-remove-top-padding .scroll{
        padding-top:0px !important;
      }
      ion-list.manual-list-fullwidth div.list, .list.card.manual-card-fullwidth {
        margin-left:-10px;
        margin-right:-10px;
      }
      ion-list.manual-list-fullwidth div.list > .item, .list.card.manual-card-fullwidth > .item {
        border-radius:0px;
        border-left:0px;
        border-right: 0px;
      }
      .show-list-numbers-and-dots ul{
        list-style-type: disc;
        padding-left:40px;
      }
      .show-list-numbers-and-dots ol{
        list-style-type: decimal;
        padding-left:40px;
      }
    </style>

    <script src="js/app.js"></script>
    <script src="js/controllers.js"></script>
    <script src="js/routes.js"></script>
    
    <script src="js/directives.js"></script>
    <script src="js/services.js"></script>

    <!-- Only required for Tab projects w/ pages in multiple tabs 
    <script src="lib/ionicuirouter/ionicUIRouter.js"></script>
    -->

  </head>
  <body ng-app="app" animation="slide-left-right-ios7">
  <div>
  <ion-side-menus enable-menu-with-back-views="false" data-componentid="side-menu21">
    <ion-side-menu-content>
      <ion-nav-bar class="bar-light">
        <ion-nav-back-button></ion-nav-back-button>
        <ion-nav-buttons side="left">
          <button class="button button-icon button-clear ion-navicon" menu-toggle="left"></button>
        </ion-nav-buttons>
      </ion-nav-bar>
      <ion-nav-view></ion-nav-view>
    </ion-side-menu-content>
    <ion-side-menu side="left" id="side-menu21" style="background-color:#003333;">
      <ion-header-bar class="bar-light">
        <div class="title">Menu</div>
      </ion-header-bar>
      <ion-content ng-controller="menuCtrl" padding="false" class="side-menu-left has-header ">
        <div data-componentid="image1">
          <img src="img/ZzcJfL2CR7u3PX4sPKLo_pessoaid.jpg" style="display: block; width: 34%; height: auto; margin-left: auto; margin-right: auto;">
        </div>
        <h5 id="menu-heading1" style="color:#000000;text-align:center;" data-componentid="heading1">Manuela Alc??ntara</h5>
        <ion-list id="menu-list1" data-componentid="list1">
          <ion-item class="item-icon-left item-icon-right dark" id="menu-list-item4" data-componentid="list-item4">
            <i class="icon ion-ios-person"></i>Editar Perfil
            <i class="icon ion-edit icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item1" data-componentid="list-item1">
            <i class="icon ion-ios-gear"></i>Configura????o</ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="menu-list-item6" ui-sref="tabsController.conteDoVestibular()" menu-close="" data-componentid="list-item6">
            <i class="icon ion-ios-bookmarks"></i>Conte??dos
            <span class="item-note">PAS/ENEM/USP</span>
            <i class="icon ion-connection-bars icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="menu-list-item8" ui-sref="tabsController.simulados()" menu-close="" data-componentid="list-item8">
            <i class="icon ion-ios-book"></i>Simulados
            <span class="item-note">PAS/UnB/ENEM/USP</span>
            <i class="icon ion-university icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item7" data-componentid="list-item7">
            <i class="icon ion-trophy"></i>Pontua????o
            <span class="item-note">89/100</span>
          </ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item3" href-inappbrowser="https://www.msdmanuals.com/pt-br/casa/dist%C3%BArbios-%C3%B3sseos,-articulares-e-musculares/biologia-do-sistema-musculoesquel%C3%A9tico/m%C3%BAsculos" data-componentid="list-item3">
            <i class="icon ion-ios-body"></i>Corpo 3D</ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item5" data-componentid="list-item5">
            <i class="icon ion-ios-moon"></i>Modo Noturno </ion-item>
          <ion-item class="item-icon-left dark" id="menu-list-item2" ui-sref="page()" menu-close="" data-componentid="list-item2">
            <i class="icon ion-log-out"></i>Sair</ion-item>
        </ion-list>
      </ion-content>
    </ion-side-menu>
  </ion-side-menus>
</div>
  </body>
</html>
