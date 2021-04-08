# japan-postal-code-api

### &nbsp; forked from [ZCloud-Firstserver/japan-postal-code](https://github.com/ZCloud-Firstserver/japan-postal-code)
#### &nbsp;&emsp; forked from [meltedice/japan-postal-code](https://github.com/meltedice/japan-postal-code)
##### &nbsp;&emsp;&emsp; forked from [mzp/japan-postal-code](https://github.com/mzp/japan-postal-code)
###### &nbsp;&emsp;&emsp;&emsp; forked from [ajaxzip3/ajaxzip3.github.io](https://github.com/ajaxzip3/ajaxzip3.github.io)

and

[https://github.com/madefor/postal-code-api](https://github.com/madefor/postal-code-api)
[https://github.com/madefor/postal-code-api/tree/gh-pages](https://github.com/madefor/postal-code-api/tree/gh-pages)
[]()
[]()

## How to update postalcode data

[https://www.post.japanpost.jp/zipcode/dl/roman-zip.html](https://www.post.japanpost.jp/zipcode/dl/roman-zip.html)
```
wget https://www.post.japanpost.jp/zipcode/dl/roman/ken_all_rome.zip
unzip ken_all_rome.zip
nkf -Sw KEN_ALL_ROME.CSV > KEN_ALL_ROME.UTF8.CSV
python ./makejsonpdata-from-csv.py KEN_ALL_ROME.UTF8.CSV
```

