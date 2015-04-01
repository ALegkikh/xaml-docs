---
title: Navigation
page_title: Navigation
description: Navigation
slug: wizard-navigation
tags: wizard, navigation
published: True
position: 0
---

# Navigation

__RadWizard__ provides out of the box a basic sequential page navigation, which allows you to navigate through the pages linearly. With the help of __RadWizard's__ events you can follow the state of the control at run time and implement custom pages sequence and page processing validation if necessary.

## Linear Navigation 

__RadWizard’s__ navigation is enabled by default and it allows you navigating through the pages in linear order. By default, pages will be visited in the order that they are defined in its __WizardPages__ collection.	

## Conditional Navigation ##

__RadWizard__ provides the following events, which enable the implementation of conditional (not linear) navigation. 
* SelectionChanging
* SelectionChanged
* Previous
* Next
* Finish 
* Help 
* Cancel

>For the full list of events refer to the [Events]({%slug wizard-events%}) article.



