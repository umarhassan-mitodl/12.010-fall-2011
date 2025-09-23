---
content_type: page
description: This section provides instructions on using course resources with different
  types of computers.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Related Resources
uid: ddefc53c-5c9a-5e34-4407-32ac2e36985b
---
## PC Instructions

If you are familiar with installing software on your PC and know lots about the Windows system you can try to install g77 from the link below. You should read the {{% resource_link "d7caf9eb-556c-4ee0-8cde-4106b26a670f" "instructions" %}} first to see if you understand the instructions.

Below is a link to Fortran (g77) for PC:

({{% resource_link "0384a61f-093c-4bd7-a09f-f6f60dd385b1" "http://www.neng.usu.edu/cee/faculty/gurro/Classes/Classes_Fall2002/Fortran77/Fortran77Course.html" %}})

Below are alternative instructions (these require about the same amount of knowledge as the instructions above).

Alternative is to add cygwin to your PC (linux running on PC). Download cygwin from {{% resource_link "92cac8de-8ec8-456c-8301-cb04dbb3a769" "http://www.redhat.com/services/custom/cygwin/" %}}

Use cygwin\_setup to get gcc, g77 and nedit.

Also needed is

{{% resource_link "7099626e-d7da-45c7-bd4f-75c0724975ab" "http://ist.mit.edu/xwin32" %}}

which is the Windows X-window system. (Needed for nedit)

When using X-windows from cygwin you need to add at the terminal prompt

setenv DISPLAY: 0.0

(this allows programs such as nedit and xterm to open windows).

{{% resource_link "3c0045ae-df01-4156-a2de-75b39e566810" "Installing Fortran" %}} gives instructions for installing gfortran on a PC.

## Intel Mac Instructions

Nedit can be downloaded from   
{{% resource_link "10392596-4384-4017-8449-dd5b7b358a06" "http://sourceforge.net/projects/nedit/files/nedit-executable/5.5/nedit-5.5-MacOSX.tar.gz/download" %}}

gfortran downloaded from {{% resource_link "0c1f8be7-b49b-4bd1-a914-7ced0d2bd123" "http://hpc.sourceforge.net" %}} (see links with gfortran in name).

{{% resource_link "27f91b44-ee5c-4813-b7ff-17d6c51b2892" "Fink commander" %}} is a great utility to install to get lots of linux packages for the Mac.

{{% resource_link "76b92d93-2896-4d4b-aaec-125f8194999c" "O'Reilly series of books on programming" %}}

{{% resource_link "c410aa54-68f9-4d5e-af4d-238b24f29946" "Fortran Resources and Fortran Compilers for Windows and Linux" %}}