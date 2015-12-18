Tool for using with Lego Digital Designer 4.3.5 wich can find parts quick and copy this direct to LDD.

#summary One-sentence summary of this page.

# Introduction #

I like to work with Lego Digital Designer but finding of parts is very limited. Because of this i wrote myself a little tool wich make working with LDD  better. Because the tool is better working than expected i want to share the beta version already with you all. If anyone found a bug or a feature request, let me know.


# Details #
**LDD Part Finder features**

  * Index of all (available) parts of LDD 4.3.5
  * Fast search on partnumber, design id or description keyword, wildcards or regular expression (PCRE, use :your RegularExpression in front of a search)
  * Show the partnumber and a preview image of the found LDD design part
  * Show the itemnos and a preview image of the itemnos variations in official LDD colors
  * Copy the item description or design id/itemnos to clipboard option
  * Copy the item description or design id/itemnos **DIRECT** to the stringfield of LDD option
  * Main window Stay on front of all other windows option
  * Bring LDD to front after a clipboard or **DIRECT** copy option
  * Minimize and Maximize button to make the main window small or default. This is handy when used with stay on top and working in LDD.
  * Auto minimize after clipboard or LDD Direct copy.
  * All options (including selected font) can be saved in the .ini file and will be loaded by program start.
  * Option to choose another font for easy reading at your own comfort.
  * Low memory usage and working on WinXP/Win7 x86/x64 (minimal required screen size = 800x600)
  * Contains **14.490 LDD** itemnos and **13.877 NON LDD** itemnos (but official Lego numbers)
  * Easy LDD Yes/No column to show if your selected itemnos/Lego part/variation is known and supported in LDD
> > Key in your itemnumber from an Official Lego building instruction inventory and pronto, with ONLY ONE mouseclick it's into LDD, the end of searching is near!


# Begin of a FAQ #

for LDD Direct to function following LDD state/theme is required :

  * if you want to copy a designID direct to LDD, the LDD program should be in LDD Extended mode/theme.

  * if you want to copy a itemnos (official colored part with number) the LDD program should be in LDD mode/theme.

You can change the LDD mode/theme at all time in the LDD View menu - New themes.

Supported Wildcards
  * `*`   Match everything
  * `?`   Match exactly one character.
  * `#`   Match a digit.
  * `@`   Match an alphabetic character
  * `$`   Match a digit or an alphabetic character
  * `#+`  Match multiple digits.
  * `@+`  Match multiple alphabetic characters
  * `$+`  Match multiple digits or alphabetic characters

Wildcards can be used multiple times in a search

# HISTORY #
1.0.0
- normal release, end of beta, current release contains 28.367 itemnos, but still more to come.
- more bugfixing, i guess all bugs are history (i hope)
- better About menu window including a direct link to the one of the best CROSS PLATFORM programming languages in the world, www.purebasic.com
- menu option to the LDD PF main download site

new feature
- extended\_images\_lib.bin, this library contains 12.455 official Lego images with or without decorations. This library is optional and you can download this separately. Place it in the same folder as LDD PF and the program will automatically use it when you click a itemnos. Downside is that not all parts are available as extended image, if so then the standard image will be used.

1.1.0 beta
  * much bugfixing, correct itemnos now beter than ever, but stil some things to do (duplicate design id's, missing itemnos...)
  * all assemblies of LDD (multi part parts) are now converted too, so a lot of figure upper and lower parts are available with their itemnos, LDD and offical parts
  * image\_lib, parts.lib are updated so you NEED the complete archive to download.

# New Feature #
To get a hold on itemnos which are supported by LDD and not supported/known OFFICIAL Lego parts i made a new collumn LDD with yes/no. This will show you if your selected colour/itemnos is supported by LDD and you can direct copy it to the LDD stringfield.



**1.0.9 beta**
bugfix: wrong parts where showed due to a bug in the itemnos to design id routine. way more itemnos are now correctly showed!
new feature:
- when you input an official itemnos the picture and correct color is now automatically displayed and selected.
- column headers adjusted for better auto sizing


**1.0.8 beta**
- 9 itemnos where lost in the automatic conversion of 1.0.7, this is fixed now
itemnos fixed = 4119500,4125253,4256320,4264362,4282742,4288245,4288961,4520636,4550171


**1.0.7 beta**
- images lib updated to contents of 835.4
images for new design id 10113,2493,90395,90396,90540,90542,95322,95323,95324,96204,98065,98067,98068,98069,98071,98086,98165,99242,99254,99464


**1.0.6. beta**

- updated to LDD brickset 835.4
- added more than 12.500 (!) NON LDD, but official LEGO itemnos wich has an alias to a LDD design id. So with an official Lego building instruction booklet/pdf it should be possible to find (almost) every itemnr/nos mentiod in LDD PF.
- cosmetic corrections


**1.0.5. beta**
- speeded up the splash screen as requested by legolijntje of eurobricks.com
- moved the font selection menu option to prefs


**1.0.4 beta**

New features:
Minimize and Maximize by button

> Make the main window small or default size. This is handy when you use stay on front and need the display area in LDD but still want to go back fast to LDD Part Finder.

Auto Minimize
> If checked this will auto minimize the main window after a LDD\_Direct or clipboard copy

Menu Prefs
> Save Options - This will save all checkmarked or uncheckmarked options to the .ini Also the current font will be saved. The font selection option will NOT save by default anymore.
> Default opions - This revert back to the default options, all options uncheckmarked and the default font.

**1.0.3 beta**

Supported Wildcards
Wildcards can be used multiple times in a search

Examples
Br**- finds Brick and all other words beginnning with Br
Br?ck** - finds any part wich begin with Brick,Brock etc.
**Brick\*x2** - Will find all parts containing brick and x2
43##**- Finds all parts wich itemnos or designid starts with 43 and two digits**brick\*2x#**- Finds all parts containing brick and 2x3 2x2 2x1**

- !! regular expression switch has been changed from @ to : !!

- windows alert sound after you press enter has been removed
- some cosmetic corrections