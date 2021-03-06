# About

The [History.csv](https://github.com/eXpandFramework/eXpand/blob/master/ReleaseNotesHistory/History.csv) contains references to issues, commits, labels that affected each [Release](releases.expandframeowrk.com). For a quick search you can open the [History.csv](https://github.com/eXpandFramework/eXpand/blob/master/ReleaseNotesHistory/History.csv) and type what you want in the header of the autogenerated grid.

![image](https://user-images.githubusercontent.com/159464/57982225-f817f900-7a4a-11e9-99f8-23f0afa49880.png)

For complex queries you can download the file and use the language/tools of your choice to query further.

However you can spare your time and do complex queries with the [XpandPosh](http://xpandposh.expandframework.com) module and the [Get-XpandReleaseChange](https://github.com/eXpandFramework/XpandPosh/wiki/Get-XpandReleaseChange) Cmdlet.

Let's say for example we want to see what changed for the `ExcelImporter` and `ModelDifference` labels between `18.1.4.2` and `19.1.201.0` releases and we we want to display the results in a browser so we  can navigate with hyperlinks which are not supported in the console.

```ps1
Get-XpandReleaseChange ExcelImporter,Modeldifference 18.1.4.2 19.1.201.0 -ShowInBrowser
```

Note that the [Get-XpandReleaseChange](https://github.com/eXpandFramework/XpandPosh/wiki/Get-XpandReleaseChange) offers `autocompletion` so you do not have to discover the parameter values.


![image](https://user-images.githubusercontent.com/159464/57982266-aae85700-7a4b-11e9-9785-99697a496ff4.png)
