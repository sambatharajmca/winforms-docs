---
title: Structure
page_title: Structure | UI for WinForms Documentation
description: RadDesktopAlert component displays a small pop-up window on the screen to notify the user that a specific event has occurred in the application. 
slug: winforms/desktopalert/structure
tags: desktopalert, structure
published: True
position: 1
---

# Structure

>caption Fig.1 RadDesktopAlert's structure

![desktopalert-structure 001](images/desktopalert-structure001.png)

This article describes the inner structure and organization of the elements which build the __RadDesktopAlert__ control.

1. __RadDesktopAlertElement__: represents the main element of a __RadDesktopAlert__ <br>
	1\.1\. __AlertWindowCaptionElement__: represents the caption of a __RadDesktopAlert__. It contains a caption grip which is used to move the alert window, close button and options drop-down button.<br>
		 1\.1\.1\. __AlertWindowCaptionGrip__: represents the part of a __RadDesktopAlert__ that can be used to move the component on the screen.<br>
		 1\.1\.2\. __AlertWindowTextAndSystemButtonsElement__: represents the part of a __RadDesktopAlert__ that contains the text and the system buttons.<br>
	1\.2\. __AlertWindowContentElement__: represents the content of a __RadDesktopAlert__ component.The content usually is built of an image and HTML enabled text. <br>
	1\.3\. __AlertWindowButtonsPanel__: represents the element which holds the buttons that can be added in a __RadDesktopAlert__ window.<br>