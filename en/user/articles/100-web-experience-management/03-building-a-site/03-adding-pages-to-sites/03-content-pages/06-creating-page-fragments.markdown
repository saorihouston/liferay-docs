---
header-id: creating-page-fragments
---

# Creating Page Fragments

[TOC levels=1-4]

Fragments enable you to create rich content. With all of the included Fragments
and Collections, many projects can be completed using just what ships with
@product@. Sometimes, though, you must create your own Fragments. Fragments are
built using HTML, CSS, and JavaScript. For a deeper dive into creating a custom
Fragment, see [Developing Fragments](/docs/7-2/frameworks/-/knowledge_base/f/creating-fragments).

In this article, you'll learn about the Page Fragments interface.

## Creating and Managing Fragments

To navigate to the Page Fragments interface,

1.  Go to Site Administration. Make sure the Site where you want to work is 
    selected.

2.  Select *Site Builder* &rarr; *Page Fragments*

![Figure 1: Here is the Page Fragments page with no Fragments or Collections created.](../../../../../images/empty-fragments-page.png)

Fragments are organized in *Collections*. The main Page Fragments page shows
available Collections, provides the option to Import and Export, and enables you
to create Collections. You can also manage the organization and display of
Fragments and Collections you have created. To create a Fragment, you must first
create a Collection.

1.  Click *New* &rarr; *Collection* to add a Collection.

2.  Give the Collection a *Name* and *Description* and click *Save*.

Collections help you organize Fragments, and can be used to differentiate 
between different types of Fragments or Fragments used by different groups or 
departments. Next, create a Fragment inside the Collection you created.

1.  Click on the Collection you created.

2.  Click the *Add* icon (![New](../../../../../images/icon-add.png)) to create
    a Fragment.

3.  Choose either *Section* or *Component*.

3.  Give it a *Name* and click *Save*.

The Fragment development environment appears. Each pane in the editor has
a different function:

- The top left pane is for entering HTML.
- The top right pane is for entering CSS.
- The bottom left pane is for entering JavaScript.
- The bottom right pane provides a live preview as you work in the other panes.

![Figure 2: The Fragments editor provides an environment for creating all the parts of a Fragment.](../../../../../images/fragments-editor.png)

In addition to standard HTML, CSS, and JavaScript, developers can also embed
widgets and provide fields containing text and images that can be edited during
the final Content Page publication process. Fragment development is covered in
depth in 
[Developing Fragments](/docs/7-2/frameworks/-/knowledge_base/f/creating-fragments).

You can also include resources in your Fragment Collection that your Fragments
can reference. This is helpful when exporting/importing Fragments: their
resources are automatically included. If they're stored somewhere else
(e.g., Documents and Media), you must export/import them separately. Click the
*Resources* tab for your Collection and add resources (e.g., image, document,
etc.) there.

![Figure 3: The Resources tab can be selected from the Fragment Collection.](../../../../../images/fragment-resources-tab.png)

Once added, you can reference resources from your Fragment's code without
worrying about their availability. You can learn more about doing this in 
[Including Default Resources in Fragments](/docs/7-2/frameworks/-/knowledge_base/f/including-default-resources-in-fragments).

Next you'll learn how to import and export Page Fragments.
