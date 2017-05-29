# MonokaiAndroid
Monokai Theme for Android Studio 1.5+

Fork of https://github.com/benmarten/MonokaiAndroidStudio with the following changes:

- changed reference link (ctrl-click link) color from ugly default blue to magenta
- right margin (vertical bar) color changed to reddish gray to be more visible
- selected background color: changed to have more contrast and be better visible
- unmatched brace background color changed to match UnknownSymbol background colo
- bigger default font size

![Screenshot](https://raw.githubusercontent.com/benmarten/Monokai_Android/master/screenshot.png "Screenshot")

## Installation

1. Download the `Monokai_Android.jar` or clone this repository.
2. In Android Studio choose `File > Import Settings ...`

## Updating the JAR from source files

1. Clone this repo, `cd` to `src`
2. Zip all the files inside and rename the file from `whatever.zip` to `Monokai_Android.jar`
3. Move the zip up to the git root

## Monokai Theme Colors

### OSX (RGB)

#### Editor Interface
- Background: #272822
- Selection Background: #49483E
- Caret: #F8F8F0
- Invisibles: #49483E
- Invalid Highlight: Background #F92672, Font: #F8F8F0

#### Code
- Text: #F8F8F2
- Comment: #75715E
- Quoted String: #E6DB74
- Number, Constant: #AE81FF
- Keyword, Tag, Annotation: #F92672
- Class Name: #A6E22E, underline
- Inherited Class: #A6E22E, italic underline
- Function Name, Attribute Name: #A6E22E
- Function Argument: #FD971F
- Library Function, Library Constant: #66D9EF
- Storage Type, Library Class, Library Type: #66D9EF, italic

### Windows (sRGB) see: https://github.com/jibsen/tmcolorconv

#### Editor Interface
- Background: #34352D
- Selection Background: #5B5A4F
- Caret: #F9F9F3
- Invalid Highlight: Background #FD4485, Font: #F9F9F3

#### Code
- Text: #F9F9F5
- Comment: #888471
- Quoted String: #EBE086
- Number, Constant: #BD99FF
- Keyword, Tag, Annotation: #FD4485
- Class Name: #B3E43B, underline
- Inherited Class: #B3E43B, italic underline
- Function Name, Attribute Name: #B3E43B
- Function Argument: #FFA727
- Library Function, Library Constant: #75E0F2
- Storage Type, Library Class, Library Type: #75E0F2, italic

## License
MIT
