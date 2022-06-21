# 發個幹文為什麼那麼多觸及 tweet likes stats and quick plot
<!--
creation time: 23:53:54
first uploaded: 00:26:xx (https://gist.github.com/holishing/1b8a78d5a3f7d9d26b28df4329c5ccbb)
-->
[點我看結論](#discussion-and-conclution)
## Related Tweets
- 0: <https://twitter.com/_/status/1536375587673018370>
- 1: <https://twitter.com/_/status/1536773646949453824>
- 2: <https://twitter.com/_/status/1537076212182691840>
- 3: <https://twitter.com/_/status/1537382884218380289>
- 4: <https://twitter.com/_/status/1537777947322765313>
- 5: <https://twitter.com/_/status/1538123819834953733>
- 6: <https://twitter.com/_/status/1538477798813184001>
- 7: <https://twitter.com/_/status/1538893887892205568>

## Scripts
### Requirments
-  [GMT](https://github.com/GenericMappingTools/gmt), Generic Mapping Tools

### Last actual likes
```bash
gmt plot -W1 -Bxa1+l"Day" -Bya1000+l"Likes" -BWS stat.csv -png stat
```

### Last screenshotted likes expect last tweet
```bash
gmt plot -W1 -Bxa1+l"Day" -Bya1000+l"Likes" -BWS stat_screenshot_except_lasttime.csv -png stat_screenshot_except_lasttime
```

### Result Plot
### Last actual likes
![](https://i.imgur.com/iO9QI2r.png)


### Last screenshotted likes expect last tweet
![](https://i.imgur.com/MxznYMs.png)

### Discussion and Conclution
結果顯示，從第二次到第三次的截圖推文是觸及率提升的關鍵
