Grading Snippets

Setup

1. In VS Code - open Command Palette search bar under View.
2. In Command Palette type "snippet" then select "Preferences: Configure User snippets" followed by "markdown.json" The file that pops up should start with "Place your snippets for markdown here."
3. There is an example in the commented out section to follow:

```
    // "Print to console": {
    //  "prefix": "log",
    //  "body": [
    //      "console.log('$1');",
    //      "$2"
    //  ],
    //  "description": "Log output to console"
    // }
```

- "Print to console" is the name of the snippet
- prefix is the keyword you will type to generate the snippet
- body is the snippet itself
- description is just for your reference

**_Turn on tab completion_**

- Open File > Preferences > Settings. Search for "editor.tabCompletion" and turn on. When you type in a prefix and hit tab the snippet will autofill.

**_Some tricks about body:_**

| For one line |                                   |
| ------------ | --------------------------------- |
| code         | "body": "This is great woohoooo!" |
| output       | This is great wooohoooo!          |

| Several lines - no space |                                                                 |
| ------------------------ | --------------------------------------------------------------- |
| code                     | "body": ["Good work!", "Here is what you need to do to pass:"], |
| output                   | Good work! <br> Here is what you need to do to pass:            |  |

| Several lines - with space |                                                  |
| -------------------------- | ------------------------------------------------ |
| code                       | "body": ["Good work!", "", "Again great work."], |
| output                     | Good work! <br> <br> Again great work            |

Here is more on what snippets can offer. Placeholders under Snippet Syntax might be useful: https://code.visualstudio.com/docs/editor/userdefinedsnippets
