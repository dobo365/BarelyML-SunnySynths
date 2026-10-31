# BarelyML - Sunny Synths markdown

Markup display for JUCE - Barely a Markup Language

BarelyML - Sunny Synths markdown is an extension of the BarelyML library made by Friz Menzer in 2023. It is providing a more complete handling of the initialy supported markdown tags but has also enhanced it with new ones. Only the Markdown part has been enhanced and tested.

Copy the BarelyML - Sunny Synths.cpp and .h files to your Juce project.
Test with the TESTME.md file.

### Latest version: 0.8 
Date: June 15th 2026
Author:  Dominique Bontemps - Sunny Synths

- Corrected the usage of table background colours 
- Adapted to be closer to the Github Wiki layout
- Added support for double tilde tag to indicate a strikethrough text
- Handle right/center/left alignment in tables columns
- Links are not in bold; they get a pointing hand cursor when hovered
- Tables are rendered as in Github Wiki (even rows have a very light background, grid in light grey, header in bold) 
- Supports inline code using single back tick tag and code blocks using triple back tick tags
- Code text is displayed in courier new font on a grey rectangle background
- Ability to copy code block by pressing an icon
- Added horizontal rule drawing using standard markdown "---" tag
- Blockquote marking using standard markdown "> " tag
- Adapted Admonition block tagging as "!!! TYPE" and "!!!"
- Possible Admonition block types are: HINT, INFO, CAUTION, WARNING, OTHER, MISC 
- Completely rewritten Admonition blocks rendering that also covers blockquote
- Modified H1 heading rendering to be more in line with GitHub's H1 rendering (with a line drawn below the text)

Licensed under the MIT license, in the hope it will be useful to as many people as possible.
