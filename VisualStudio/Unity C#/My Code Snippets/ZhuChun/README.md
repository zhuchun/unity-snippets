Author: Zhu Chun

Support: Raise issues.

Hi, this is my most common used Unity snippet for Visual Studio, feel free to check it out.

**Format:**
Filename
-----------------------------------
**Shortcut**

*Description*

`Example`

Brackets.snippet
------------------------------------
**serializeField**

`[SerializeField] GameObject go;`


**contextMenu**

`[ContextMenu("MenuName")]`

Code.snippet
------------------------------------

**notImplementedFunction**

*Create a function with a TODO comment and NotImplementedException.*

**foo**

*Create a dummy function.*

**singleton**

*Create a singleton and Awake() for this class, useful for global "Manager" class in games.*

**getComponent**

*GetComponent and assign a variable.*

**log**
**warning**
**error**

*Print in console with class name so that's easier to see.*

**logF**
**warningF**
**errorF**

*Print in console with class name and format, feel free to use placeholders like {0},{1} etc..*

**dlg**

*Create an event with a delegate use simmilar name*

```
public delegate void HappensDlg(); //"Happens" is the default name
public event HappensDlg OnHappens;
```