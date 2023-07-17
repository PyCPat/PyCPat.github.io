# Python code change patterns

On this page, you will find code change patterns that were extracted from open source Python repositories. Each pattern consists of several instances of similar code changes. Following links contain the code change pattenrs extracted using various staturgies.

* [Link1](https://github.com/PyCPat/PyCPat.github.io/tree/master/INIT) provides an extensive collection of code change patterns found in the `__init__` functions of classes that inherit from the parent class "nn.Module." These patterns are presented in various formats as below.

    * In [HTML Format](https://pycpat.github.io/INIT/HTML/HTML/2/directory.html) format, the link leads to a comprehensive resource for accessing all the patterns in HTML format. It first directs you to the main page, which is a table summarizing the patterns. The table includes columns such as "ID" for the pattern ID, "Pattern size" indicating the number of repeated nodes, and "Details" which provides a direct link to all the instances of each pattern. Within each instance link, you will find a graphical representation of the repeated graph present in the pattern instances. Additionally, there is further information about each change instance, as well as a highlighted code snippet for reference. This allows for a clear visualization and understanding of the code change patterns in the init functions of classes inheriting from "nn.Module".

    * In "[JSON]([https://github.com/PyCPat/PyCPat.github.io/tree/master/JSON](https://github.com/PyCPat/PyCPat.github.io/tree/master/INIT/JSON))" format, the directory includes pattern information in `JSON` format, while the
    * The "[FRAGMENTS](https://github.com/PyCPat/PyCPat.github.io/tree/master/FRAGMENTS)" directory contains code changes associated with each pattern in HTML format. To access code changes in the "[FRAGMENTS](https://github.com/PyCPat/PyCPat.github.io/tree/master/FRAGMENTS)" folder, you can use the Pattern "ID" and "FRAGMENT_ID" fields. The folders in "[FRAGMENTS](https://github.com/PyCPat/PyCPat.github.io/tree/master/FRAGMENTS)" are named according to the "PATTERN_ID," while the code change files are named after the "FRAGMENT_ID."

`Note: In both the Json and HTML formats, certain fields are prefixed with either "M" or "N". Fields prefixed with "M" are relevant to the code before the change, while those prefixed with "N" are relevant to the code after the change.
      

The JSON file contains information of the pattern as Jsons. Here is some information about the contents of the JSON file:

```json
{
"PATH" : "To find the HTML illustration of the pattern, you can add the prefix https://pycpat.github.io/HTML/ to this filed"  
"NODES" : "Information about the pattern's repeated nodes"
    {
      "BEFORE_CHANGE" : "Nodes belonged to the code before to the change."
      "AFTER_CHANGE" : "Nodes belonged to the code after to the change."
    }
"NUMBER_OF_REPEATED_NODES": "The number of repeated nodes in the pattern's code change instances"
"Fragments" : "Information of code changes instances"
    {
      "FRAGMENT_ID" : "A unique ID is used to identify the fragment. You can use this ID to links to the code change in the "FRAGMENT" folder."
      "PROJECT_NAME" : "The project to which the change pertains"
      "COMMIT_NAME" : "Commit hex"
      "TIME" : "The git commit time"
      "AUTHOR_NAME" : "Author of the commit"
      "M FILE_NAME" : "The file of the before code in which the change is made"
      "M CLASS_NAME" : "The class of the before code change in which the change is made"
      "N FILE_NAME" : "The file of the after code in which the change is made"
      "N CLASS_NAME" : "The class of the after in which the change is made"
      "AUTHOR_NAME" : "Author email address"
      "COMMITTER_EMAIL" : "Commiter email address"
      "NODE_INFO" : "The information of the repeated nodes of the fragment"
      {
          "END_CHARACTER": "End character position of the AST nodes",
          "START_LINE_NUMBER": "Line number of the node",
          "AST_CLASS":"AST node name",
           "LENGTH": "Character length of the node",
          "START_CHARACTER":"Start character of AST node",
          "END_LINE_NUMBER": "End line number of of the node"
      }
    }
 "ID": "Pattern ID",
 "PATTERN_SIZE": "Number of code changes instances of the pattern"

}

