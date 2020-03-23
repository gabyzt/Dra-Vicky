<html lang="es"><head>
<title>Dra vicky</title>
 <link rel="stylesheet" type="text/css" href="index file/segundostl.css">
<link rel="stylesheet" type="text/css" href="https://github.com/gabyzt/Dra-Vicky/blob/master/index%20file/photoswipe.css">
<link rel="stylesheet" type="text/css" href="P%C3%A1gina%20App%20Archivos/default-skin.css">
</head>

 
 
 
 
  <div class="loading-welcome active welcome-screen" ng-style="{'background-color': view.code.welcome_extra.background || view.welcome_extra.background}" style="background-color: rgb(255, 255, 255); display: none;">
    <div class="progress">
        <div class="loading-bar indeterminate" ng-style="{'background-color': view.code.color1 || view.color1}" style="background-color: rgb(56, 11, 131);"></div>
    </div>
    <div class="helper"></div>
    
    <img id="welcomeImg" imageonload="" ng-src="https://github.com/gabyzt/Dra-Estrella/blob/master/index%20file/6181944_1.png" ng-style="{
            'max-width': view.code.welcome_extra.zoom *2 || view.welcome_extra.zoom *2 + 'px',
            'max-height': view.code.welcome_extra.zoom *2 || view.welcome_extra.zoom *2 + 'px',
            'animation-iteration-count' :  view.showPreview == 'infinite' ? 'infinite' : '',
            'animation-direction' :  view.showPreview == 'infinite' ? 'alternate' : ''
            }" src="https://github.com/gabyzt/Dra-Estrella/blob/master/index%20file/6181944_1.png" style="max-width: 100px; max-height: 100px; display: inline;">
</div>
    


















<div class="sh-background" ng-style="getBackgroundStyles()" style="height: 500px; background-color: rgb(56, 11, 131); color: rgb(255, 255, 255);"></div>

    <div class="sh-container" id="rootElement"><!-- rootElement is important for sync data -->
        <div ng-hide="hasAnyContentToDisplay()" class="ng-hide">
            <div class="vcard-row text-center mt-20">
                <h4>       </h4>
            </div>
           
        </div>
       
      
            
      




<div ng-show="hasAnyContentToDisplay()">
   
            <div class="sh-page">

    <div class="sh-page__title ng-binding" ng-show="view.code.title" ng-class="{'sh-page__title--more-space': !view.code.description &amp;&amp; !view.code.button.label}">Dra. Estrella Morales Palma</div>

    <div class="sh-page__description" ng-show="view.code.description &amp;&amp; view.code.description.length &lt;= 200"><!--
        --><span class="sh-page__description-text ng-binding">Cirujano Dentista</span>
    </div>



<div class="sh-background" ng-style="getBackgroundStyles()" style="height: 500px; background-color: rgb(56, 11, 131); color: rgb(255, 255, 255);"> </div>




<center>
<!-- ngIf: !useGridView() --><div ng-if="!useGridView()" class="ng-scope">
        <!-- ngRepeat: image in view.code.images track by $index --><sh-gallery-image ng-repeat="image in view.code.images track by $index" class="ng-scope"><div class="sh-image" ng-click="openGallery(image)" ng-style="getImageContainerStyle(image)" style="padding-bottom: 128.106%;"><img class="sh-image__image" ng-src="https://raw.githubusercontent.com/gabyzt/Dra-Estrella/master/index%20file/estr1f.jpg" ng-class="{'sh-image__image--loaded': image}" src="https://raw.githubusercontent.com/gabyzt/Dra-Estrella/master/index%20file/estr1f.jpg"></div></sh-gallery-image>

    
            
       
    </div>
</center>
