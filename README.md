# CV of Mounir Meknaci

## Aim of the website
I am currently studying web development with OPENCLASSROOMS (www.openclassrooms.com) and the online CV is one of the projects I have to complete for my diploma. This project is also a starting point for me to have some 'visibility' on the web.
My task is to integrate a template using HTML and CSS languages to create a webpage which is adaptable to all types of devices.

## Automated Rules used for the stylesheet
The extension used on vscode is stylelint.
https://stylelint.io/user-guide/rules/list
```json
{
    "stylelint.config": {
        "rules": {
            "selector-max-class": 3,
            "block-no-empty": true,
            "font-family-no-duplicate-names": true,
            "font-family-no-missing-generic-family-keyword": true,
            "color-no-invalid-hex": true,
            "string-no-newline": true,
            "unit-no-unknown": true,
            "property-no-unknown": true,
            "keyframe-declaration-no-important": true,
            "declaration-block-no-duplicate-properties": true,
            "selector-type-no-unknown": true,
            "selector-pseudo-element-no-unknown": true,
            "selector-pseudo-class-no-unknown": true,
            "media-feature-name-no-unknown": true,
            "comment-no-empty": true,
            "no-duplicate-selectors": true,
            "no-empty-source": true,
            "no-extra-semicolons": true,
            "no-invalid-double-slash-comments": true,
            "rule-empty-line-before":[
            "always",
            {
              "ignore": ["after-comment"]
            }
          ],
            "media-feature-colon-space-after": "always",
            "comment-empty-line-before": "always",
            "comment-whitespace-inside": "always",
            "indentation": 4,
            
        }
    }
}
```

## Organizing the CSS
The stylesheet is divided into three different categories : Base, Layout and the Custom Module.
#### Base (General styles)

body { ... }

container { ... }

h1, h2, h3, h4 { ... }

ul { ... }

#### Layout (structure: positionning, size and style)

. {
    padding,
    marging,
    flexbox,
    display
    ...
}

#### Custom Module (All about styling: text, pictures, icons...)
. {
    underline,
    color,
    border
    ...
}

## License
Public domain.