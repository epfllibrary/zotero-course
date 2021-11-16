## From Zotero to the word processor

Zotero integrates very well with Microsoft Word and LibreOffice Writer.
There are several ways to add references from a Zotero library in a word processor.

First, both Zotero and the word processor have to be open. Then, to be able to use the interactive features, you need to have a Zotero button in your word processor. Can you see it? If not, in Zotero, open the Preferences panel and go to *Cite > Word Processors* and click on the "reinstall [name of the word processor] Add-in" button.

## Zotero and LaTeX

It's also possible to use Zotero with LaTeX. 

### With Overleaf

To connect Overleaf with your Zotero library go to "settings" and look for "link to Zotero". Your overleaf account is now linked to your Zotero library.
In your paper, create a new file uploaded from Zotero with the .bib extension. This file contains your entire Zotero library in bibtex format. For each reference, the first line is the key you have to use for citing.

Example: \cite{jawahar_viena_2019}

#### Overleaf and group libraries

A great feature of both Zotero and Overleaf is the ability to work collaboratively. However, synchronising Zotero group librairies with Overlead requires some extra steps.
You will need to:
1. Make your Zotero group library public (Public: Closed Membership / Group Library: Anyone can view, only members can edit)

2. Find the unique number of your Zotero group library by opening the group via Zotero.org

[add image]

3. Add a .bib file from an external URL with the following URL: https://api.zotero.org/groups/[unique group id]/items/top?format=bibtex&style=numeric&limit=100

### With TexMaker or another LaTeX editor.
Export your references from Zotero in a bibtex file. The file will not be up to date in case if you add, modify or remove references in Zotero. Use the keys in the same way as previously for citing. For advanced use of LaTeX within Zotero, [BetterBibTex](https://retorque.re/zotero-better-bibtex/), an independently developped plug-in can be useful
