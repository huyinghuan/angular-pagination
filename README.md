# angular-pagination
angular pager for semantic-ui

## how to use

copy this file to your project.
and declaration it in your `app.module.ts`

In page

```
<pagination [pageCount]="pageCount" [pageCurrent]="params.page" (onGoto)="gotoPage($event)"></pagination>
```

tell pagination how many page count total and  the number of current page index, and listener `onGoto` event. 
