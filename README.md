# Idea issue ng-material

IntelliJ Idea shows this error:
```
Property matHeaderRowDef is not provided by any applicable directive on an embedded template
```
for `matHeaderRowDef` in a template. This is unexpected, because `material-module.ts` exports
`MatTableModule`.  
Moreover other structural directives work: e.g. `matHeaderCellDef` does
not show any error.

![IDEA screenshot](./idea-screenshot.png "IDEA screenshot")
