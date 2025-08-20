---
title: Creating and Updating Mujeres
nav: Mujeres
---
________

#How to create and maintain Mujeres records

Mujueres records are creating using Markdown files in the Mujeres template.

To add a new mujeres bio the site:

-Download the mujeres_bio_template from the _templates_ folder.

-Open the file with your text editor.

-Rename the file to the Last and First name of your subject and save it.

-Fill out the header information: (Note that anything in _italics_ is just to explain and should not be included in your final example). *Bold* indicates a required field. 

*objectid: alicia-escalante* _(first-last)_
*title: Alicia Escalante* _(Title as Shown on Page)_
born: _(optional bio detail)_
education: _(optional bio detail)_
bio_detail: _(optional bio detail)_
*quote: Don’t ever underestimate the power of a woman.* _(Quote - strongly suggested.)_ *description: Alicia Escalante was born in El Paso Texas, in 1933 to what she describes as a traditional family. She was the second oldest of seven children, and she shared an intense bond with her mother. She'd go on to be an organizer and movemement leader, creating the East LA Welfare Rights Organization* _(2-3 sentence description)_

*image_large*: https://raw.githubusercontent.com/marcosvdotcom/chicanapormiraza/refs/heads/main/web_graphics/chicanadiasporic.png
*image_small*: https://cpmrark.reclaim.hosting/mujeres/small/aliciaescalante_sm.jpg
*image_thumb*: https://cpmrark.reclaim.hosting/mujeres/thumbs/aliciaescalante_th.jpg

For now, we will just put the same image URL in all the same spots. 

_Need to upload an image? [Click here](How to upload an image)_

-Add your biography body information where indicated. This should be written in markdown.

_*Explore CB includes: CB allows you to easily add in archival records stored on the site, these are called "includes"*_

Includes examples: 
<img src="tbd"></i>


## Existing records edit
To edit an existing Mujeres record, find the markdown file in the _bios folder.
Click the pencil icon in the upper right to edit the file. 
Edit and save.
You may need to hard refresh to see the updates pull throuh on the demo site.

## Connecting records

If the person described has archival records, you can add related fileds using the following. If you don't hve related records, just delte these from the mujeres template/starter.

<code start>

## Browse related records
<br>

{% include feature/image.html objectid="cb209;cb206;cb208" %}
[Click here for more.](http://127.0.0.1:4000/chicanapormiraza/browse.html#alicia%20escalante)

</code>

Once oyu rae ready, move your file to the _bios folder
You can go there and upload a file by clicking in the right corner upload files.
Once uploaded, refresh teh site and you shoudl see your new bio on mujeres.
