# VGrid.less
The best grid system ever made in LESS

## Settings
First you set the with of your columns, the number of columns and the padding between.

```
/*  1. - Width Variables
————————————————————————————————————————————— */
@sm-screen: (720px  + @padding-width*2);
@md-screen: (940px  + @padding-width*2);
@lg-screen: (1140px + @padding-width*2);
@xl-screen: (@lg-screen * 20);



/* 2. - Columns settings
————————————————————————————————————————————— */
@cols-per-row: 12;    // Columns per row
@padding-width: 30px; // Padding between columns
```

## Classes
- You can made columns using mixins or using classes like `grid-$` where `$` can be 1 to `@cols-per-row`.
- You can made columns for specific with using mixins or classes like `grid-xs-$`, `grid-sm-$`, `grid-md-$` or `grid-lg-$`.
- You can offset columns using mixins or classes like `offset-xs-$`, `offset-sm-$`, `offset-md-$` or `offset-lg-$`.
- And more thinks in code.

## Follow me and improve this
Send me a message [@victoor](http://twitter.com/victor) and if you can improve this just make a pull request.

Thanks,
