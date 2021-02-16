# disclaimer 
 am new in CSS so you may face a couple of bugs and also  I got inspiration from other themes
# How to install
[Copy this] - Dracula theme
    - ``` #document {
    background-color: #282a36;
}
#document .document-title {
    color: #ffffff;

}
body {
    background-color: #282a36;
    height: 100%;
    margin: 0;
    font-size: 15px;
    caret-color: #55CDC4;
	color:white;
}
.hierarchy-editor-toolbar-container--opened #hierarchy-editor-toolbar {
  border-color: #ff5555;
  border-top: solid #282a36;
  background-color: #282a36;
  border-width: thin;
  white-space: nowrap;
  display: flex;
  align-items: center;
  height: 100%;
  padding-left: 15px;
  padding-right: 15px;
}
#hierarchy-editor-toolbar-container #hierarchy-editor__add-to-portal .rich-text-editor {
  border: 1px solid ;
  border-radius: 5px;
  padding: 5px;
  margin: 5px 5px 4px;
  background-color: #282a36;
  color:white;
  font-size: 15px;
}
.rem-text {
    margin-left: -5px;
    padding-left: 20px;
    min-height: 16.67px;
    color:white;
    font-size: 18px;
}
.concept_rem_type, .question_rem_type {
  font-weight: 700;
  color:#f5f1f1;
}
.search-results {
    font-weight: 400;
    color: #000;
    background-color: #fff;
    border-radius: 10px;
    border: none;
    min-width: 300px;
    padding-bottom: 0;
    font-size: 16px;
    position: relative;
    bottom: -2px;
    animation: fadein-zoom .05s;
    overflow: hidden;
	background-color: #282a36;
	
    color:white;
}
.rich-text-editor__selected-text-menu .rich-text-editor__selected-text-menu__doc-options {
    display: flex;
    padding: 0 4px;
    align-items: center;
	background-color: #282a36;
	
    color:white;
}
.rich-text-editor__selected-text-menu .rich-text-editor__selected-text-menu__search {
    border-color: #c8c8c8;
    border-top: solid #c8c8c8;
    border-width: thin;
	background-color: #282a36;
	
    color:white;
}
.search-results #search-results__list {
    z-index: 8;
    max-width: 50rem;
    overflow-y: auto;
    max-height: calc(100vh - 80px);
	background-color: #282a36;
	
    color:white;
}
.rich-text-editor__selected-text-menu .search-results #search-results__list {

	background-color: #282a36;
	
    color:white;
}
.selectedResult {
    	background-color: #282a36;
		color:rgb(241, 241, 243);
}
/* sidebar */

#ho mepage #content #document-sidebar, #main #content #document-sidebar{
    border-width: thin;
    color:rgb(241, 241, 243);
    overflow: hidden;
    background-color: #44475a;
    z-index: 7;
    max-width: 240px;
    min-width: 240px;
    display: flex;
    flex-direction: column;
}


/* up seetings  */ 
#document .document__top-bar .document__options-menu .ui.right.pointing.dropdown>.menu {
    /* box-shadow: 0 0 0 1px rgba(0,15,40,.05), 0 3px 6px rgba(0,15,40,.1), 0 9px 24px rgba(0,15,40,.2); */
    border-radius: 10px;
    width: 17rem;
    background-color: #44475a;
    color: white;

} 

/* portl */
#hierarchy-editor .TreeNode {
    border-color: #e5e5e5;
    border-width: 2px;
    transition-timing-function: linear;
    position: relative;
    background-color: transparent;
    padding-left: 25px;
    padding-top: 0px;
    padding-bottom: 0px;
    margin-top: 0px;
    margin-bottom: 0px;
}
#hierarchy-editor .TreeNode--dark-indent-line {
    border-color: #bcbcbc!important;
    border-width: 2px;
    background-color: transparent;
}
.hierarchy-editor--ltr .TreeNode {
    margin-left: 2.5px;
    padding-left: 20px;
    border-left-style: solid;
}
#hierarchy-editor .portal-rem {
    border-style: none none;
    border-top-style: none;
    border-right-style: none;
    border-bottom-style: none;
    border-left-style: none;
    border-width: 0px;
    margin-top: 10px;
    margin-left: -7px;
    margin-right: -7px;
    padding-top: 0px;
    height: 100%;
}
#show-embedded-search-button {
	background-color: #44475a;
    padding-left: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 12px;
    margin-top: 10px;
    margin-bottom: 10px;
    border: 0px none rgb(0,0,0);
    border-bottom: 0px solid #000;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
    margin-right: 6px;
    margin-left: -6px;
    color: #82868B;
    font-weight: 400;
}
.embeddedSearch {
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border: 0px solid #d3d4d8;
    border-top-color: rgba(183,183,187,0);
    border-top-style: solid;
    border-top-width: 0px;
    border-right-color: rgba(183,183,187,0);
    border-right-style: solid;
    border-right-width: 0px;
    border-bottom-color: rgba(183,183,187,0);
    border-bottom-style: solid;
    border-bottom-width: 0px;
    border-left-color: rgba(183,183,187,0);
    border-left-style: solid;
    border-left-width: 0px;
    border-image-source: initial;
    border-image-slice: initial;
    border-image-width: initial;
    border-image-outset: initial;
    border-image-repeat: initial;
    text-decoration: none;
    text-decoration-line: none;
    text-decoration-thickness: initial;
    text-decoration-style: initial;
    text-decoration-color: initial;
    padding-top: 5px;
    padding-right: 5px;
    padding-bottom: 6px;
    padding-left: 10px;
    margin-bottom: 5px;
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 0px;
    background-color: #FDFDFE;
}
#hierarchy-editor .portal-rem--embedded-search {
    border-color: none;
    background-color: #44475a;
    margin-right: 6px;
    padding-top: 0px;
    margin-top: 14px;
    margin-left: -6px;
    padding-bottom: 14px;
    margin-bottom: 20px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .rem-container__top-level-spacer {
    margin-top: 10px;
    width: 100%;
    display: block;
}
#search-results__controls #search-results__control .search-results__control__keyboard-shortcut, .quote {
    margin-right: 0px;
    margin-left: 0px;
    background-color: #44475a;
    border-radius: 30px;
    padding: 1px;
    padding-left: 6px;
    padding-right: 6px;
}
i.icon.search:before {
    content: "\f002";
    zoom: 125%;
    padding-top: 6px;
    padding-left: 2px;
    color: #44475a;
}
i.icon.refresh:before {
    content: "\f021";
    zoom: 120%;
    color: #44475a;
    padding-right: 5px;
}
#embedded-search-refresh-button {
    float: right;
    padding-top: 6px;
    padding-right: 15px;
    padding-bottom: 10px;
    padding-left: 5px;
}
#no-search-results {
    color: #44475a;
    text-align: center;
    margin-top: 20px;
    margin-bottom: 5px
}
#hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0,0);
    border-width: 0px;
    position: relative;
    top: 0px;
    padding-top: 0px;
    margin-top: -25px;
}
#hierarchy-editor .search-portal-tree-node {
    border-bottom-width: 0px;
    border-top-width: 0px;
    border-left: 0px solid rgb(0,0,0,0);
    border-bottom-color: rgb(0,0,0,0);
    border-right: 0px solid rgb(0,0,0,0);
    border-top-color: rgb(0,0,0,0);
    margin-left: -6px;
    margin-right: 6px;
    padding-left: 15px;
    padding-right: 9px;
    padding-bottom: 12px;
    margin-bottom: 7px;
    margin-top: -30px;
    background-color: #44475a;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
.rem-indented-indicator {
    color: rgb(0,0,0,0);
    top: -1.8px;
    position: fixed;
}
#hierarchy-editor .isSearchResult {
    background-color: transparent;
    margin-top: 0px;
    margin-bottom: -0px;
    border: 0px solid rgb(0,0,0);
    border-radius: 0px;
    margin-right: 0px;
    margin-left: 0px;
    padding-left: 0px;
}
#hierarchy-editor .rem-container__top-level-spacer .rem-container__top-level-spacer__inner {
    border-color: rgb(0,0,0,0);
    border-top: solid rgb(0,0,0,0);
    border-width: 5px;
    bottom: 0px;
    position: relative;
}
#hierarchy-editor .portal-rem .portal-rem-top, #hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0);
    border-width: 0px;
    position: relative;
    top: -4px;
    padding-top: 13px;
}
#hierarchy-editor .portal-tree-node {
    border-left: 0px solid rgba(183,183,187,0);
    border-bottom-color: rgba(183,183,187,0);
    border-right: 0px solid rgba(183,183,187,0);
    border-bottom: 8px solid #44475a;
    border-top: 4px solid #44475a;
    margin-left: -6px;
    margin-right: 6px;
    margin-top: -16px;
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 9px;
    padding-top: 6px;
    padding-bottom: 0px;
    background-color:#44475a ;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .hierarchy-editor__after-portal .addItemAfterPortal {
    height: 25px;
    width: 100%;
    padding-left: 8px;
    margin-top: -8px;
    margin-bottom: -4px;
}
#hierarchy-editor .hierarchy-editor__after-portal {
    border-bottom-style: solid;
    border-width: 0px;
    border-top-width: 0px;
    border-right-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 0px;
    padding-top: 0px;
    padding-bottom: 0px;
    margin-left: -6px;
    margin-right: 7px;
}
#hierarchy-editor .rem-container--not-included-in-document-scope {
    color: #44475a;
    padding-left: 15px!important;
    padding-bottom: 2px;
    padding-top: 1px;
}
/* hilights */
  
.rem-text.rem-header--1,
.rem-text.rem-header--2,
.rem-text.rem-header--3 {
  margin-top: 3px;
  border-radius: 30px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  background-color:#44475a ;
  
  }
  
  
   
/*red*/
.highlight-color--red, .pdf-viewer__highlight-container--red .AreaHighlight, .pdf-viewer__highlight-container--red .Highlight__part {
  
  background-color: #ff5555;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/*orange*/
.highlight-color--orange, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--orange .AreaHighlight, .pdf-viewer__highlight-container--orange .Highlight__part, .PdfHighlighter .textLayer ::selection {
  background-color: #ffb86c;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/*yellow*/
.highlight-color--yellow, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--yellow .AreaHighlight, .pdf-viewer__highlight-container--yellow .Highlight__part, .PdfHighlighter .textLayer ::selection {
  background-color: #f1fa8c;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/*green*/
.highlight-color--green, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--green .AreaHighlight, .pdf-viewer__highlight-container--green .Highlight__part, .PdfHighlighter .textLayer ::selection {
  background-color: #50fa7b;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/*blue*/
.highlight-color--blue, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--blue .AreaHighlight, .pdf-viewer__highlight-container--blue .Highlight__part, .PdfHighlighter .textLayer ::selection {
  background-color: #8be9fd;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/*purple*/
.highlight-color--purple, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--purple .AreaHighlight, .pdf-viewer__highlight-container--purple .Highlight__part, .PdfHighlighter .textLayer ::selection {
  background-color: #ff79c6;
  border-radius: 35px;
  border-left-style: solid;
  border-right-style: solid;
  border-color: rgba(0, 0, 0,0.0);
  border-width: 6px;
  color:black ;
}
/* seetings*/
.settings-page .settings-page__sidebar {
    min-width: 195px;
    max-height: 100%;
    display: flex;
    flex-direction: column;
    border-color: #44475a;
    border-right: solid #44475a;
    border-width: 1;
    background-color: #44475a;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link {
    border-color: #44475a;
    color: rgb(248, 248, 249, .6);
    font-size: 17px;
    padding: 10px 10px 10px 20px;
    border-bottom: solid #44475a;
    border-width: 0;
    display: flex;
    align-items: center;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__title {
    color: rgb(248, 248, 249, .6);
    font-weight: 700;
    font-size: 24px;
    margin: 20px;
}
.settings-page label {
    font-size: 14px!important;
    color: #535666;
}
.settings-page .settings-page__content .settings-page__content-inner {
    padding: 30px;
    color: #535666;
}
.settings-page__option {
    margin-top: 10px;
    padding-bottom: 10px;
    display: flex;
    border-width: 1px;
}
.settings-page .settings-page__sub-header {
    border-width: 1px;
    color: #535666;
    font-size: 18px;
    margin: 40px 0 10px;
    padding-bottom: 5px;
    font-weight: 700;
}
.settings-page__option .settings-page__text .settings-page__text__subtext {
    color: #44475a;
    margin-top: 5px;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link:hover {
    background-color: rgb(73,83,88,0.4);
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link--active {
    font-weight: 700;
    background-color: #44475a;
    border-left-style: solid;
    border-left-width: 3px;
    border-left-color: #41668C;
    }
.settings-page__option .settings-page__input .settings-page__input-box {
    padding-right: 1rem;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 5px;
    border-style: none;
    border-radius: 4px;
    background-color: #E8F0FC;
}
/*KB*/
#KnowledgeBasePage {
    padding-top: 20px;
    padding-left: 15px;
    padding-right: 15px;
    height: 100%;
    background-color:#282a36;
}
#DocumentTable .ReactVirtualized__Grid {
    background-color: #44475a;
    border-radius: 0 0 15px 15px;
    box-shadow: 0 0 0 1px rgba(111,166,255,.05), 0 1px 3px rgba(51,82,134,.05), 0 3px 10px rgba(118,142,184,.2);
    border-top: none;
}
#DocumentTable .ReactVirtualized__Table__headerRow {
    text-transform: none;
    font-size: 17px;
    padding: 20px 0 10px;
    background-color: #fff;
    padding-right: 0!important;
    border-radius: 15px 15px 0 0;
    box-shadow: 0 0 0 1px rgba(111,166,255,.05), 0 1px 3px rgba(51,82,134,.05), 0 3px 10px rgba(118,142,184,.2);
    border-bottom: none;
    background-color: #44475a;
}
/* popups */
.rem-reference__popup {
    width: 275px;
    font-size: 14px;
    background-color: #282a36;
    border: thing solid #c8c8c8;
    border-radius: 3px;
}
.rem-reference__popup .rem-reference__popup__preview {
    background-color: #282a36;
    color: white;
    font-size: 16px;
    border-color: #c8c8c8;
    border-bottom: solid #c8c8c8;
    border-width: thin;
    margin-bottom: 5px;
    padding: 8px 11px;
    font-weight: 700;
    

}
.ui.popup {
    font-size: 14px;
    background-color:#282a36;
    border: thin solid #c8c8c8;
    border-radius: 3px;
	color: white;
}
.toolbar-button {
    color: white;
}
.rem-reference-link {
    color: #ff5555;
    font-weight: 500;
}
.bold {
    font-weight: 700;
    color:#50fa7b ;
}
#document-hover-preview {
    background-color:#282a36;
    color: white;
    box-shadow: 0 0 0 1px rgba(15, 15, 15, .05),
    0 3px 6px rgba(15, 15, 15, .1),
    0 9px 24px rgba(15, 15, 15, .2);
    border: none;
    border-radius: 3px;
    margin: 10px;
    padding: 15px 20px!important;
        }
#document-hover-preview #document-hover-preview__popup
    {
        padding-left: 5px;
    }
#SearchPopup .EditorContainer {
   background-color:#282a36;
   color: white;
}
#hierarchy-editor .HierarchyEditorChildrenList .children-list-content,
.hierarchy-editor__hidden-children {
    background-color:#282a36;
    color: white;
    border-radius: 3px;
    box-shadow: 
        rgba(15, 15, 15, 0.2) 0px 0px 0px 1px,
        rgba(15, 15, 15, 0.4) 0px 0px 6px,
        rgba(15, 15, 15, 0.6) 0px 0px 24px;
}
#hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top {
    border-color: #282a36;;
    z-index: 1;
    margin-left: -12px;
    margin-right: -10px;
    padding-right: 1px;
    pointer-events: auto;
    background-color:#282a36;
    color: white;
}
.cloze {
    background-color: rgba(210,225,248,0);
    color: #ff79c6;
    border-bottom: 3px solid #ff79c6;
    padding-bottom: 2px;
    font-weight: 600;
    font-style: italic;
    color:ff79c6 ;
}
.flash {
    background-color:transparent!important;
    box-shadow: none;
    border: none;
}
/*qouee*/
.spacedRepetition .spacedRepetitionContent {
    background-color:#44475a;
    overflow-y: auto;
    overflow-x: hidden;
    font-size: 16px!important;
    flex-grow: 1;
    -webkit-text-size-adjust: none;
    -moz-text-size-adjust: none;
}
.Queue .queue__title {
    justify-content: center;
    position: relative;
    text-align: center;
    height: 32px;
    padding: 4px;
    background-color: #44475a;;
    color: white;
}
.queue__buttons {
    background-color: #44475a;;
    color: white;
}
.spacedRepetition .spaced-repetition__reveal{
    background-color: #44475a;;

}
.concept_rem_type, .question_rem_type {
    font-weight: 700;
    color: white;;
}
.Queue {
    background-color: #44475a;
    color: white;
    border-radius: 4px;
    box-shadow: 
        rgba(15, 15, 15, 0.1) 0px 0px 0px 1px,
        rgba(15, 15, 15, 0.2) 0px 0px 6px,
        rgba(15, 15, 15, 0.5) 0px 0px 24px;
}
.spacedRepetition .fill-in-the-blank {
    color: #ff79c6;
}
.rem-bullet__document{

    background-color: transparent;
}
.spacedRepetition .spaced-repetition__prompt .indented-rem .rem-bullet__document {
    background-color: transparent;;
    display: inline-block;
    padding: 6px;
    border-radius: 5px;
}
.Queue .queue__title .queue__sizeButton {
    border: none;
    outline: none;
    background-color: transparent;
    color: white;
    border-radius: 10px;
    display: flex;
}
.Queue .queue__badge {
    padding: 5px 9px;
    margin: 5px;
    border-style: none;
    border-radius: 10px;
    display: inline-block;
    background-color: transparent;
    color: white;
    text-align: center;
    font-weight: 450;
    font-size: 14px;
}
#SearchPopup #rich-text-editor__icon .icon {
    background-color: transparent;
    margin-top: 16px;
    padding-left: 10px;
    padding-right: 10x;
}
i.icon.search:before {
    content: "\f002";
    zoom: 125%;
    padding-top: 6px;
    padding-left: 2px;
    color: white;
    background-color: transparent;
}
#SearchPopup {
    color: #000;
    width: min(calc(100vw - 200px),700px);
    display: flex;
    flex-direction: column;
    max-height: calc(100vh - 140px);
	background-color: #282a36;

}
.react-contextmenu{
    color: white;
   	background-color:#282a36;
   	font-size:15px;
}
.react-contextmenu--visible #menu-divider {
    border: none;
}
.ui.dropdown .menu>.item {
    border-radius: 10px;
    color: white;

}
.ui.dropdown .menu>.item:hover {
    background-color: #6272a4;
}

#document-sidebar__link   {
    padding: 8px 10px 8px 15px;
    margin: 2.5px 0;
    font-weight: 700;
   	color:white;
    font-size: 15px;
}
#document-parents .parent-link {
    color: white;
}
.react-contextmenu--visible .hierarchy-editor__rem-menu {
        color: white;
    }
    .react-contextmenu--visible .hierarchy-editor__rem-menu:hover {
        background-color: #6272a4;
    }
    .ui.dropdown .menu {
        color: white;
        background-color:#44475a
    
    
      }  
      #DocumentationList .document-list-item--opened, #documentList .document-list-item--opened {
        font-weight: 700;
        background-color: transparent;
        border-width: 4px;
        border-left-color: #3b7cc8;
    }
    #homepage #content #document-sidebar #DocumentationList .documentListHeader:hover,
    #homepage #content #document-sidebar #DocumentationList .document-list-item:hover,
    #homepage #content #document-sidebar #documentList .documentListHeader:hover,
    #homepage #content #document-sidebar #documentList .document-list-item:hover,
    #main #content #document-sidebar #DocumentationList .documentListHeader:hover,
    #main #content #document-sidebar #DocumentationList .document-list-item:hover,
    #main #content #document-sidebar #documentList .documentListHeader:hover,
    #main #content #document-sidebar #documentList .document-list-item:hover {
        background: #6272a4;
    }
    
    #homepage #content #document-sidebar #DocumentationList .document-list-item--opened,
    #homepage #content #document-sidebar #documentList .document-list-item--opened,
    #main #content #document-sidebar #DocumentationList .document-list-item--opened,
    #main #content #document-sidebar #documentList .document-list-item--opened {
        background: #6272a4;
    }
    #document-sidebar__hiden-link__container:hover {
        background-color:#6272a4;
    }

    #document-sidebar__hiden-link__container {
        background-color: #6272a4;
    }
    .embeddedSearch {
        color: black;
        background-color: #FDFDFE;
    }
  .document-sidebar-item__right-click-menu{
    color: white;
    background-color:#44475a


  }
  .document-sidebar-item__right-click-menu:hover{
    background-color: #6272a4;


  }
  #SearchPopup #PinnedResults .PinnedResult {
    padding: 5px;
    margin: 5px;
    border-radius: 7px;
    color: white;
}
.RichTextViewer undefined{
color: white;
}
#quote {
    background-color: #6272a4;
    border: .7px solid #c8c8c8;
    border-radius: 4px;
    padding-right: 2px;
    padding-left: 2px;
    margin-right: 2px;
    margin-left: 2px;
}
#SearchPopup {
color: white;


}
.rem-reference__popup .rem-reference__popup__item {
    color: white;
    
}
.rem-reference__popup .rem-reference__popup__item:hover {
    background-color: #6272a4;
    
}
.spacedRepetition .spaced-repetition__prompt .spaced-repetition__prompt__breadcrumbs {
    color: white;
    margin-left: 16px;
    margin-bottom: 5px;
}
#hierarchy-editor__ctrl-f{
    background-color: #44475a;
    border-color: #44475a;


}  
  ```
- 
