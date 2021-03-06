---
header-id: designing-web-content-with-templates
---

# Designing Web Content with Templates

[TOC levels=1-4]

Developers create templates to display the elements of the structure in the
markup they want. In essence, templates are scripts that tell @product@ how to 
display content in the structure. Changes to the structure require corresponding
changes to the template, because new or deleted fields produce errors on the
page. A structure cannot be displayed without a template, and a template cannot
exist without a structure.

@product@ only supports creating web content templates in FreeMarker (FTL) by
default. FreeMarker is the preferred, recommended language, and what you'll use
in the next example.
