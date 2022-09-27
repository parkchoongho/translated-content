---
title: ARIA techniques
slug: Web/Accessibility/ARIA/ARIA_Techniques
tags:
  - ARIA
  - Acessibilidade
  - Precisa de Tradução
  - Referencia
  - TopicStub
  - Visão Geral
translation_of: Web/Accessibility/ARIA/ARIA_Techniques
---
O ARIA define as semânticas que podem ser aplicadas aos elementos, e são divididas em **funções** (definindo um tipo de elemento da interface do usuário) e **estados** e **propriedades** que são suportados por uma função. Os autores devem atribuir uma função ARIA e os estados e propriedades apropriados a um elemento durante seu ciclo de vida, a menos que o elemento já possua semântica ARIA apropriada (através do uso de um elemento HTML apropriado). A adição de semântica ARIA apenas expõe informações extras para a API de acessibilidade de um navegador e não afeta o DOM de uma página.

## Funções

### Funções de widget

- [button](/pt-BR/docs/Web/Accessibility/ARIA/Roles/button_role "Using the button role")
- [checkbox](/pt-BR/docs/Web/Accessibility/ARIA/Roles/checkbox_role "Using the checkbox role")
- [gridcell](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Gridcell_Role)
- [link](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_link_role "Using the Link role")
- menuitem
- menuitemcheckbox
- menuitemradio
- option
- [progressbar](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_progressbar_role "en/ARIA/ARIA_Techniques/Using_the_progressbar_role")
- [radio](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_radio_role "en/ARIA/ARIA_Techniques/Using_the_radio_role")
- scrollbar
- searchbox
- separator (when focusable)
- [slider](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_slider_role "en/ARIA/ARIA_Techniques/Using_the_slider_role")
- spinbutton
- [switch](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Switch_role)
- [tab](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tab_Role)
- [tabpanel](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tabpanel_Role)
- [textbox](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_textbox_role "en/ARIA/ARIA_Techniques/Using_the_textbox_role")
- [treeitem](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Treeitem_Role)

### Funções compostas

As técnicas abaixo descrevem cada função composta, bem como suas funções filho obrigatórias e opcionais.

- combobox
- [grid](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Grid_Role) (incluindo as funções [row](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Row_Role), [gridcell](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Gridcell_Role), rowheader, columnheader)
- [listbox](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_listbox_role "en/ARIA/ARIA_Techniques/Using_the_listbox_role") (incluindo a função option)
- menu
- menubar
- [radiogroup (veja a função radio)](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_radio_role "en/ARIA/ARIA_Techniques/Using_the_radio_role")
- [tablist](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tablist_Role) (incluindo as funções [tab](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tab_Role) and [tabpanel](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tabpanel_Role))
- [tree](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tree_Role)
- treegrid

### Funções da estrutura de documento

- [application](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Application_Role)
- [article](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Article_Role "en/Accessibility/ARIA/ARIA_Techniques/Using_the_article_role")
- [cell](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Cell_Role)
- columnheader
- definition
- directory
- [document](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Document_Role)
- feed
- [figure](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Figure_Role)
- [group](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_group_role "en/ARIA/ARIA_Techniques/Using_the_group_role")
- [heading](/pt-BR/docs/Web/Accessibility/ARIA/Roles/heading_role)
- [img](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Role_Img)
- [list](/pt-BR/docs/Web/Accessibility/ARIA/Roles/List_role)
- [listitem](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Listitem_role)
- math
- none
- note
- [presentation](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_presentation_role "en/ARIA/ARIA_Techniques/Using_the_presentation_role")
- [row](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Row_Role)
- [rowgroup](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Rowgroup_Role)
- rowheader
- separator
- [table](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Table_Role)
- term
- [textbox](/pt-BR/docs/Web/Accessibility/ARIA/Roles/textbox_role)
- [toolbar](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_toolbar_role "en/ARIA/ARIA_Techniques/Using_the_toolbar_role")
- [tooltip](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Tooltip_Role)

### Funções de ponto de referência

- [banner](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_banner_role "en/ARIA/ARIA_Techniques/Using_the_banner_role")
- [complementary](/pt-BR/docs/Web/Accessibility/ARIA/ARIA_Techniques/Complementary_role)
- [contentinfo](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Contentinfo_role)
- [form](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Form_Role)
- [main](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Main_role)
- [navigation](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Navigation_Role)
- [region](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Region_role)
- [search](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Search_role)

### Funções de regiões ativa

- [alert](/pt-BR/docs/Web/Accessibility/ARIA/Roles/Alert_Role)
- [log](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_log_role "Using the Log role")
- marquee
- [status](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_status_role "Using the link role")
- [timer](/pt-BR/docs/Web/Accessibility/ARIA/Roles/ARIA_timer_role)

### Funções de janela

- [alertdialog](/pt-BR/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_alertdialog_role)
- [dialog](/pt-BR/docs/Web/Accessibility/ARIA/Roles/dialog_role)

## Estados e propriedades

### Atributos de widget

- aria-autocomplete
- aria-checked
- aria-current
- aria-disabled
- aria-errormessage
- aria-expanded
- aria-haspopup
- aria-hidden
- [aria-invalid](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-invalid_attribute "Using the aria-invalid attribute")
- [aria-label](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-label_attribute "Using the aria-labelledby attribute")
- aria-level
- aria-modal
- aria-multiline
- aria-multiselectable
- [aria-orientation](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-orientation_attribute "en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-orientation_attribute")
- aria-placeholder
- aria-pressed
- aria-readonly
- [aria-required](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-required_attribute "Using the aria-required property")
- aria-selected
- aria-sort
- [aria-valuemax](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuemax_attribute "Using the aria-required attribute")
- [aria-valuemin](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuemin_attribute "en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuemin_attribute")
- [aria-valuenow](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuenow_attribute "en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuenow_attribute")
- [aria-valuetext](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuetext_attribute "en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-valuetext_attribute")

### Atributos da região ativa

- aria-live
- [aria-relevant](/pt-BR/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-relevant_attribute "en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-relevant_attribute")
- aria-atomic
- aria-busy

### Atributos de drag & drop

- aria-dropeffect
- aria-dragged

### Atributos de relacionamento

- [aria-activedescendant](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-activedescendant_attribute "Role")
- aria-colcount
- aria-colindex
- aria-colspan
- aria-controls
- [aria-describedby](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-describedby_attribute "Using the aria-labelledby attribute")
- [aria-details](/pt-BR/docs/Web/Accessibility/ARIA/Annotations#Associating_annotated_elements_with_their_details)
- aria-errormessage
- aria-flowto
- [aria-labelledby](/en/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute "en/ARIA/ARIA_Techniques/Using_the_aria-labelledby_attribute")
- aria-owns
- aria-posinset
- aria-rowcount
- aria-rowindex
- aria-rowspan
- aria-setsize

### Propriedades específicas do MicrosoftEdge

- [x-ms-aria-flowfrom](/pt-BR/docs/Web/API/x-ms-aria-flowfrom) {{Non-standard_Inline}}