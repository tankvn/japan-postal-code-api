# japan-postal-code-api

### &nbsp; forked from [ZCloud-Firstserver/japan-postal-code](https://github.com/ZCloud-Firstserver/japan-postal-code)
#### &nbsp;&emsp; forked from [meltedice/japan-postal-code](https://github.com/meltedice/japan-postal-code)
##### &nbsp;&emsp;  forked from [mzp/japan-postal-code](https://github.com/mzp/japan-postal-code)
###### &nbsp;&emsp;   forked from [ajaxzip3/ajaxzip3.github.io](https://github.com/ajaxzip3/ajaxzip3.github.io)



## How to update postalcode data
```
wget https://www.post.japanpost.jp/zipcode/dl/roman/ken_all_rome.zip
unzip ken_all_rome.zip
nkf -Sw KEN_ALL_ROME.CSV > KEN_ALL_ROME.UTF8.CSV
python ./makejsonpdata-from-csv.py KEN_ALL_ROME.UTF8.CSV
```

