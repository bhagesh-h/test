# Welcome to Markdown Studio

This is your local-first markdown power tool.

## Features
- **GFM Support**: Tables, task lists, and more.
- **Math**: $E=mc^2$
- **Code**: Highlighting via Shiki/Prism.
- **AI**: Integration with Gemini.

Start by creating a new note in the sidebar.

```python
import os
os.getcwd()
```

```json
{
   "Key":"Value"
}
```

```mermaid
graph TD;
  A-->B;
  A-->C;
```

> [!warning] Proceed with Caution 
> Proceed with Caution 

> [!info] Proceed with Caution 
> Proceed with Caution 

```mermaid
gitGraph
       commit
       commit
       branch develop
       checkout develop
       commit
       commit
       checkout main
       merge develop
       commit
       commit
```

```mermaid
pie
    title Pie Chart
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 150 
```
```mermaid
stateDiagram
    [*] --> Still
    Still --> [*]

    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
```
```mermaid
classDiagram
      Animal <|-- Duck
      Animal <|-- Fish
      Animal <|-- Zebra
      Animal : +int age
      Animal : +String gender
      Animal: +isMammal()
      Animal: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Fish{
          -int sizeInFeet
          -canEat()
      }
      class Zebra{
          +bool is_wild
          +run()
      }
```
```mermaid
%% Example with selection of syntaxes
        gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid

        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d

        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d

        section Documentation
        Describe gantt syntax               :active, a1, after des1, 3d
        Add gantt diagram to demo page      :after a1  , 20h
        Add another diagram to demo page    :doc1, after a1  , 48h

        section Last section
        Describe gantt syntax               :after doc1, 3d
        Add gantt diagram to demo page      : 20h
        Add another diagram to demo page    : 48h
```
### AI Generated Summary
Markdown Studio is a local-first markdown editor featuring GFM support, LaTeX math, code highlighting, and Gemini AI integration. It supports advanced formatting, including diagrams and task lists, providing a professional environment for note management.

[Test Url](https://support.typora.io/Draw-Diagrams-With-Markdown/)

| Time | Temp 1 | Temp 2 |
|-------|--------|--------|
| 1     | 14.98  | 2      |
| 2     | 14.04  | 3      |
| 3     | 12.86  | 4      |
| 4     | 1.32   | 6      |

:dog:
:cat: