# ToolBoox application

Main project: [https://github.com/gaborauth/toolsboox-android](https://github.com/gaborauth/toolsboox-android)

## Community templates

In the `Tools for Boox` application there is a list of templates that are free and open to anyone to use.

### I have a template to share!

Do you have a template to share? Great! :)

In order to prevent the uploading and sharing of templates with commercial licenses, we ask you to choose a [Creative Commons](https://creativecommons.org/) licence with link about your template.

You can add yourself as contributor, this helps if there is a dispute about the template, either because someone thinks it's their creation, or because you see it elsewhere as commercial template.

Guidelines about the supported formats.

a. PNG, preferably transparent,

b. the template must be 1404 x 1872, at the moment this is the only supported size,

c. the thumbnail should be 351 x 468 (shrink to 1/4 the template),

d. the name contains only lowercase letters, numbers and '-', like 'grey-lines-32',

e. the description preferably a short sentence or a shorter brief,

f. single category, like 'grids' or 'lines'

g. the filename should be the `name` + `.png`

Example of the file names:
- black-grey-lines-16-t.png
- black-grey-lines-16.json
- black-grey-lines-16.png

Example of the JSON content:
```
{
  "version":1,
  "data":{
    "contributor":{
      "email":"gabor.auth@toolsboox.com",
      "name":"Gábor AUTH"
    },
    "copyright":"https://creativecommons.org/licenses/by/4.0/",
    "name":"grey-lines-32",
    "description":"Grey lines (x32)",
    "category":"lines",
    "filename":"grey-lines-32.png"
  }
}
```

4, Send a pull request about the template, I will check the files and the JSON.
