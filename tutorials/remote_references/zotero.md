# Setup Zotero with LaTeXing

LaTeXing offers a great support for the work together with Zotero. This
feature was introduced with LaTeXing version 0.8. The steps to setting up
Zotero are very simple and you just have to follow these steps systematically.

> To work with Mendeley and Zotero you need the package oauthlib & SSL
> available from the package control.

Activate the **zotero** option inside the LaTeXing.sublime-settings. At the
first moment LaTeXing tries to access some data from Zotero and you haven't
set up the access the authorisation process will be initiated.

## Obtain the Verification Code

For a successful communication between LaTeXing and Zotero a private key is
required. It is possible to generate and fill this code by hand but here we
are going to use the automatic way with LaTeXing.

![](images/zotero_setup_1.jpg)

At the bottom an input panel was created with a link, normally your standard
browser should automatically open this link and you don't have to copy the
link from there. The Zotero website will open and you need to follow the
instructions there.

![](images/zotero_setup_2.jpg)

Log in with your default Zotero login details.

![](images/zotero_setup_3.jpg)

Now you have to accept the key for LaTeXing, you can check the permissions in
here but it is also a read request required.

![](images/zotero_setup_4.jpg)

After accepting the permissions the verification will be displayed and you
just need to copy this code and go back to LaTeXing.

## Enter the Verification Code

With the verification code from Zotero.org you can finalize the authorisation
process. Just paste the code in the input box and press enter.

![](images/zotero_setup_5.jpg)

If the authorisation was successful a status message will confirm this, shown
on the next picture.

![](images/zotero_setup_6.jpg)

Now you are ready to use your Zotero database without leaving LaTeXing; like
it is saved on your local machine for citations or import multiple items to
your local bibliography file.

## Using your Zotero Database

![](images/zotero_setup_7.jpg)

Here the original database in Zotero.

![](images/zotero_setup_8.jpg)

> Just be award that you have to force LaTeXing to synchronise the data every
> time when you changes something and you wouldn't like to wait for the cache
> refresh. The synchronisation command will be a particle update and just the
> changed citations are updated.
