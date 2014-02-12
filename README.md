CodeRushPluginTemplates
=======================

This repository contains CodeRush templates useful to those looking to code their own CodeRush plugins.

Each template is made up of 2 files:

The .xml file is the template itself. This is the file you should download and imoport into CodeRush. It contains everything the template needs to function. ie Name, Definition and Context. The file also specifes where the template will install. In the case of these plugin templates, they will install to Custom\Plugin\[Template] 

The .txt file contains the human-readble version of the template definition. Although the .xml file is only xml, it is a serialized form of the template structure and as such can be tricky to read and get a proper understanding of what the template actually does. The .txt file is an easy way to see the template's dedinition withiout having to wade through all that xml.
  
Current Templates include:

 - NewAction
