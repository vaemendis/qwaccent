![](https://raw.githubusercontent.com/vaemendis/qwaccent/master/images/qwaccent-logo.png)

# What is it ?
**QWaccent** is a QWERTY keyboard layout with additional shortcuts to easily write in French.

It is derived from the UK Extended layout. The only modifications affect the input of diacritics.  
So any UK keyboard can be used as-is, without stickers or specifically printed keys.

![](https://raw.githubusercontent.com/vaemendis/qwaccent/master/images/qwaccent-layout.png)

# Download and installation

[**Download QWaccent**](https://github.com/vaemendis/qwaccent/releases/download/v1.0/qwaccent-1.0.zip)

QWaccent is currently available for **Windows only**.  
Contributions to provide MacOS and Linux versions are welcome !

## How to install

- Download and unzip the QWaccent package.
- Run the `setup.exe` file
- Restart your computer so that the new layout appears in the language bar and select it:

![](https://raw.githubusercontent.com/vaemendis/qwaccent/master/images/language-bar.png)

# QWaccent layout choices

QWaccent layout has been designed for developers (or more generally people who favor QWERTY keyboards) who also need to write in French.

## Why QWERTY ?

Developers often prefer QWERTY layouts because they are:

- the most common layout around the world, so most software design their keyboard shortcuts with QWERTY in mind
- easier for writing code, compared to AZERTY: direct access to dot, contiguous brackets and parentheses, direct access to numbers (no need to use the shift key or the num pad)...

## Philosophy

QWaccent layout aims to minimize the use of dead keys when writing French diacritics (é,à,û,ï...).   
It also tries to be as easy to use as possible, by sometimes choosing **efficiency over consistency**: the most often used diacritics are placed on their corresponding letter key.  

For instance (note the different accents):  
- `AltGr` + `e` = `é`
- `AltGr` + `a` = `à`
- `AltGr` + `u` = `û`

Other diacritics are placed on adjacent letters.

Consistency is preserved for dead keys though. If you forget a shortcut, you can still write your diacritic using them, as there are easy to remember (they are the same as the default UK Extended layout).

For instance:
- `AltGr` + `` ´ `` , `e` = `é`
- `AltGr` + `` ` `` , `a` = `à`
- `AltGr` + `` ^ `` , `u` = `û`

## Differences with UK Extended layout

- The  backtick key (`` ` ``) is not a dead key anymore (use AltGr + backtick to use it as a dead key). As a consequence, the broken bar (`¦`) is not accessible anymore.
- Diacritics on letters W and Y (ẃ,ŷ...) cannot be written anymore (as these letter are used for other purposes and do not exist in French anyway).

# Credits

Layout picture designed with [keyboard-layout-editor](http://www.keyboard-layout-editor.com/).  
Layout generated using [Microsoft Keyboard Layout Creator 1.4 ](https://www.microsoft.com/en-us/download/details.aspx?id=22339).  
Thanks to the [qwerty-fr](http://marin.jb.free.fr/qwerty-fr/) layout for the inspiration.  
Logo from [freepik.com](http://freepik.com).
