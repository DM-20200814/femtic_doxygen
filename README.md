# femtic_doxygen
online doc of femtic, generated by doxygen. 

there is an auto tool to generate doxygen-format comments.  
> vscode plugin:`doxygen documentation generator`.  
by modifying the .json file, you can have your own customized content.
```json
// The template for the file parameter in Doxygen.
    "doxdocgen.file.fileTemplate": "@file {name}",
    // Version number for the file.
    "doxdocgen.file.versionTag": "@version 0.1",
    // Set the e-mail address of the author.  Replaces {email}.
    "doxdocgen.generic.authorEmail": "you@domain.com",
    // Set the name of the author.  Replaces {author}.
    "doxdocgen.generic.authorName": "your name",
    // Set the style of the author tag and your name.  Can template {author} and {email}.
    "doxdocgen.generic.authorTag": "@author {author} ({email})",
    // If this is enabled a bool return value will be split into true and false return param.
    "doxdocgen.generic.boolReturnsTrueFalse": true,
    // The template of the brief Doxygen line that is generated. If empty it won't get generated at all.
    "doxdocgen.generic.briefTemplate": "@brief {text}",
    // The format to use for the date.
    "doxdocgen.generic.dateFormat": "YYYY-MM-DD",
    // The template for the date parameter in Doxygen.
    "doxdocgen.generic.dateTemplate": "@date {date}",
```
> Auto-complete doxygen commands  
![](https://github.com/cschlosser/doxdocgen/raw/HEAD/images/doxygen-auto-complete.gif)
