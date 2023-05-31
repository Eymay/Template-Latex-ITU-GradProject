# Istanbul Technical University - LaTeX Thesis Template 

This is a fork of [ITU Graduate Thesis Template](https://github.com/ondes/Template-Latex-ITU-Thesis/tree/master) modified for Electronics and Communication Eng. department in ITU. The aim is to fully substitute the Word templates given. Most parts are fixed but if you observe any difference from the template, please open an issue.

The template is a work of many people and it is a community work at this moment. If you have used the template and made something better, do contribute it back so others can benefit. Pull requests are welcome.

To have an idea about how to modify the template in the first place, please check the commits I made. Most are atomic and descriptive enough that it can be informative alone to simply trace the changes.

## Options
In `thesis.tex` file you can change the options for your needs:
```
\documentclass[onluarkali,ingilizce,lisans,bez,elektrikelektronik]{thesis_itu}
```
Though they are not tested thoroughly:
- Check out `tekyonlu` instead of `onluarkali`
- or `turkce` instead of `ingilizce`
- or `karton` instead of `bez` 


## File Structure
The root file is `thesis.tex` and the main class file is `thesis_itu.cls`. Rest of the .tex files are imported by the .cls file which is the backbone of the template.

You can add you references to `thesis_bib.bib` file. The citation formatting is done by `thesis_itubib.bst` file and there shouldn't be any need to modify it.


