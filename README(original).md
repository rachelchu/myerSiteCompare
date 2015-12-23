#erSiteCompare
=============

According to https://github.com/everright/erSiteCompare

Rachel changed history log:

* Fix bug in result page


* Support keyword filtering:param:ignoreParam
```
--ignoreParam=/news/
```

* Support sub link 
```
myerSiteCompare.py  http://www.site1.com/br  http://www.site2.com/br  --template=c:\test\erSiteCompare-template.zip  --ignoreParam=/send-to-friend/
```

* Add time stamp to result file automatically
Remove param: --output


* Add readjson()
If the result is not generated only, can use param:method and --output
```
myerSiteCompare.py  http://www.site1.com/products  http://www.site2.com/products  --template=c:\test\erSiteCompare-template.zip  --output=C:\test\result40 --m=result
```

* Add Windows Security for firefox
If there are Windows Security, can use param: security1 and security2
```
myerSiteCompare.py  http://www.site1.com/products  http://www.site2.com/products  --template=c:\test\erSiteCompare-template.zip --security1=username:password --security2=username:password
```
