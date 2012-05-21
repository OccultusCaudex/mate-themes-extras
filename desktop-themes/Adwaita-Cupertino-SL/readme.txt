Author: Rafa Cobreros rafacobreros@gmail.com
Licencia: GPL
Original theme in: http://gnome-look.org/content/show.php/Adwaita+Cupertino?content=147061

Customization tips:
NOTE:
	- should close and open session after the changes

------------------------------
* 1.- Select style for TABS *
------------------------------
Edit (gedit) the file ../Adwaita Cupertino SL/gtk-3.0/gtk.css

Go to the line where it says
@import url("tabs.css");

and modify it according to the option you want

1.- "tabs.css" (tabs default theme)

2.- "tabs-classics.css" (more traditional style tabs)

The line should look like one of the following two
(Be careful to leave only ONE of the two)

@import url("tabs.css");
or
@import url("tabs-classic.css");

---------------------------------
* 2.- Select style for nautilus *
---------------------------------
Edit (gedit) the file ../Adwaita Cupertino SL/gtk-3.0/gtk.css

go to the last line of the file, there are three options for nautilus:

	1.- "gnome-applications-gray.css"  		(nautilus sidebar and toolbar gray )
	2.- "gnome-applications-light.css" 		(nautilus sidebar and toolbar light leopard style)
	3.- "gnome-applications-gray-light.css" (nautilus sidebar gray and toolbar light)
	
edit (please carefully) the corresponding line "@import" according to the style of nautilus you want,
to make it ONE of the three (not both)

@import url("gnome-applications-gray.css");

or 

@import url("gnome-applications-light.css");

or

@import url("gnome-applications-gray-light.css");

-----------------------------------------
* 3.- Select style for titlebar buttons *
-----------------------------------------
If you prefer the buttons glassy style for titlebar (apple style):

Copy the contents of the file "buttons_glassy_SL.tar.gz" in folder .. /Adwaita Cupertino SL/metacity-1/

To restore the previous:

Copy the contents of the file "buttons_normal.tar.gz" in folder .. /Adwaita Cupertino SL/metacity-1/

----------------------------
* 4.- Fix synaptic buttons *
----------------------------
Note: I have not set by default because sacrifices appearance/quality of the radio-buttons in gtk2.

Edit (gedit) file:
/Adwaita Cupertino SL/gtk-2.0/gtkrc

Find the line (near end, about line 710):
widget_class "*<GtkRadioButton>*"		style: "radiobutton"

and replaced by:
widget_class "*<GtkRadioButton>*"		style: "checkradio"

--------------------------------
* 5.- Fix GIMP toolbar-buttons *
--------------------------------
Note: I have not set by default because sacrifices appearance/quality of the check-buttons in gtk2.

Edit (gedit) file:
/Adwaita Cupertino SL/gtk-2.0/gtkrc

Find the line (near end, about line 710):
widget_class "*<GtkCheckButton>*"				style: "checkbutton"

and replaced by:
widget_class "*<GtkCheckButton>*"				style: "checkradio"


