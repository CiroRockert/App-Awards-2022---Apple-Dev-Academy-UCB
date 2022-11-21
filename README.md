# App-Awards-2022---Apple-Dev-Academy-UCB
Como primeiro professor da SEEDF a levar 40 alunos em 2019 para Apple Developer Academy e em 2022 com mais 30 estudantes e um app na Googleplay e App Store. 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
    <title></title>

    <link rel="stylesheet" href="fonts/montserrat/css/fonts.css">
    
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

    
    <script src="lib/ionicuirouter/ionicUIRouter.js"></script>
    

  </head>
  <body ng-app="app" animation="slide-left-right-ios7">
  <div>
  <ion-side-menus enable-menu-with-back-views="true" data-componentid="side-menu21">
    <ion-side-menu-content>
      <ion-nav-bar class="bar-light">
        <ion-nav-back-button></ion-nav-back-button>
        <ion-nav-buttons side="left">
          <button class="button button-icon button-clear ion-navicon" menu-toggle="left"></button>
        </ion-nav-buttons>
      </ion-nav-bar>
      <ion-nav-view></ion-nav-view>
    </ion-side-menu-content>
    <ion-side-menu side="left" id="side-menu21" style="background-color:#FFFFFF;">
      <ion-content ng-controller="perfilCtrl" padding="false" style="top:0px !important;" class="side-menu-left ">
        <ion-list id="perfil-list9" data-componentid="list9">
          <ion-item class="item-avatar dark" id="perfil-list-item134" ui-sref="perfil2()" menu-close="" data-componentid="list-item134">
            <img src="img/EdqMZAmqQMyioldXOEHl_805c9224-7dd1-46b2-b97d-75e5483c51fa.jpeg">
            <h2dark>Ciro Rockert
              <p>Professor de artes</p>
            </h2dark>
          </ion-item>
          <ion-toggle toggle-class="toggle-dark" ng-checked="true" id="perfil-toggle10" data-componentid="toggle10">Ativar GPS</ion-toggle>
          <ion-item class="item-icon-left dark" id="perfil-list-item110" ui-sref="tabsControllerTabelaDCones.carteira_tab1()" menu-close="" data-componentid="list-item110">
            <i class="icon ion-card"></i>Carteira
            <span class="item-note">Saldo: R$50,00</span>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item94" ui-sref="tabsControllerTabelaDCones.notificaEs()" menu-close="" data-componentid="list-item94">
            <i class="icon ion-ios-bell"></i>Notificações
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item174" ui-sref="tabsControllerTabelaDCones.mensagens_tab4()" menu-close="" data-componentid="list-item174">
            <i class="icon ion-android-chat"></i>Converça
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item120" ui-sref="tabsControllerTabelaDCones.notificaEs()" menu-close="" data-componentid="list-item120">
            <i class="icon ion-ios-location"></i>Acompanhar
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item107" ui-sref="tabsControllerTabelaDCones.favoritos_tab3()" menu-close="" data-componentid="list-item107">
            <i class="icon ion-android-favorite"></i>Salvos
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item173" data-componentid="list-item173">
            <i class="icon ion-information-circled"></i>Informação
            <span class="item-note">V.0.0.1</span>
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left item-icon-right dark" id="perfil-list-item115" ui-sref="configuraEs()" menu-close="" data-componentid="list-item115">
            <i class="icon ion-ios-settings-strong"></i>Configurações
            <i class="icon ion-android-arrow-dropright icon-accessory"></i>
          </ion-item>
          <ion-item class="item-icon-left dark" id="perfil-list-item137" ui-sref="primeiraTela()" menu-close="" data-componentid="list-item137">
            <i class="icon ion-log-out"></i>Sair</ion-item>
        </ion-list>
      </ion-content>
    </ion-side-menu>
  </ion-side-menus>
</div>
  </body>
</html>
