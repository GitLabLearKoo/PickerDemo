# PickerDemo

## 效果图：

只贴了2张图，支持最低1级联动，最大5级联动的动态联动效果：

 <img src="https://github.com/66668/PickerDemo/blob/master/pictures/3_picker.jpeg" with="400" height="640" alt="3级联动图"/>
 
 <img src="https://github.com/66668/PickerDemo/blob/master/pictures/5_picker.jpeg" with="400" height="640" alt="5级联动图"/>
 
## UI修改
请在lib_picker中修改自己需要的UI样式

## 测试数据：

1. 后台返回的json小区数据1：

    {"tree":{"node_name":"测试","parent_id":-1,"node_id":111056,"child":[{"node_name":"A区","parent_id":111056,"node_id":113687,"child":[{"node_name":"1栋","parent_id":113687,"node_id":113688,"child":[{"node_name":"1单元","parent_id":113688,"node_id":113694,"child":[{"node_name":"1层","parent_id":113694,"node_id":113736,"child":[{"node_name":"0101","parent_id":113736,"node_id":113904,"child":[],"level":"6"},{"node_name":"0102","parent_id":113736,"node_id":113905,"child":[],"level":"6"},{"node_name":"0103","parent_id":113736,"node_id":113906,"child":[],"level":"6"},{"node_name":"0104","parent_id":113736,"node_id":113907,"child":[],"level":"6"},{"node_name":"0105","parent_id":113736,"node_id":113908,"child":[],"level":"6"},{"node_name":"0106","parent_id":113736,"node_id":113909,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113694,"node_id":113737,"child":[{"node_name":"0201","parent_id":113737,"node_id":113910,"child":[],"level":"6"},{"node_name":"0202","parent_id":113737,"node_id":113911,"child":[],"level":"6"},{"node_name":"0203","parent_id":113737,"node_id":113912,"child":[],"level":"6"},{"node_name":"0204","parent_id":113737,"node_id":113913,"child":[],"level":"6"},{"node_name":"0205","parent_id":113737,"node_id":113914,"child":[],"level":"6"},{"node_name":"0206","parent_id":113737,"node_id":113915,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113694,"node_id":113738,"child":[{"node_name":"0301","parent_id":113738,"node_id":113916,"child":[],"level":"6"},{"node_name":"0302","parent_id":113738,"node_id":113917,"child":[],"level":"6"},{"node_name":"0303","parent_id":113738,"node_id":113918,"child":[],"level":"6"},{"node_name":"0304","parent_id":113738,"node_id":113919,"child":[],"level":"6"},{"node_name":"0305","parent_id":113738,"node_id":113920,"child":[],"level":"6"},{"node_name":"0306","parent_id":113738,"node_id":113921,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113694,"node_id":113739,"child":[{"node_name":"0401","parent_id":113739,"node_id":113922,"child":[],"level":"6"},{"node_name":"0402","parent_id":113739,"node_id":113923,"child":[],"level":"6"},{"node_name":"0403","parent_id":113739,"node_id":113924,"child":[],"level":"6"},{"node_name":"0404","parent_id":113739,"node_id":113925,"child":[],"level":"6"},{"node_name":"0405","parent_id":113739,"node_id":113926,"child":[],"level":"6"},{"node_name":"0406","parent_id":113739,"node_id":113927,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"2单元","parent_id":113688,"node_id":113695,"child":[{"node_name":"1层","parent_id":113695,"node_id":113740,"child":[{"node_name":"0101","parent_id":113740,"node_id":113928,"child":[],"level":"6"},{"node_name":"0102","parent_id":113740,"node_id":113929,"child":[],"level":"6"},{"node_name":"0103","parent_id":113740,"node_id":113930,"child":[],"level":"6"},{"node_name":"0104","parent_id":113740,"node_id":113931,"child":[],"level":"6"},{"node_name":"0105","parent_id":113740,"node_id":113932,"child":[],"level":"6"},{"node_name":"0106","parent_id":113740,"node_id":113933,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113695,"node_id":113741,"child":[{"node_name":"0201","parent_id":113741,"node_id":113934,"child":[],"level":"6"},{"node_name":"0202","parent_id":113741,"node_id":113935,"child":[],"level":"6"},{"node_name":"0203","parent_id":113741,"node_id":113936,"child":[],"level":"6"},{"node_name":"0204","parent_id":113741,"node_id":113937,"child":[],"level":"6"},{"node_name":"0205","parent_id":113741,"node_id":113938,"child":[],"level":"6"},{"node_name":"0206","parent_id":113741,"node_id":113939,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113695,"node_id":113742,"child":[{"node_name":"0301","parent_id":113742,"node_id":113940,"child":[],"level":"6"},{"node_name":"0302","parent_id":113742,"node_id":113941,"child":[],"level":"6"},{"node_name":"0303","parent_id":113742,"node_id":113942,"child":[],"level":"6"},{"node_name":"0304","parent_id":113742,"node_id":113943,"child":[],"level":"6"},{"node_name":"0305","parent_id":113742,"node_id":113944,"child":[],"level":"6"},{"node_name":"0306","parent_id":113742,"node_id":113945,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113695,"node_id":113743,"child":[{"node_name":"0401","parent_id":113743,"node_id":113946,"child":[],"level":"6"},{"node_name":"0402","parent_id":113743,"node_id":113947,"child":[],"level":"6"},{"node_name":"0403","parent_id":113743,"node_id":113948,"child":[],"level":"6"},{"node_name":"0404","parent_id":113743,"node_id":113949,"child":[],"level":"6"},{"node_name":"0405","parent_id":113743,"node_id":113950,"child":[],"level":"6"},{"node_name":"0406","parent_id":113743,"node_id":113951,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"3单元","parent_id":113688,"node_id":113696,"child":[{"node_name":"1层","parent_id":113696,"node_id":113744,"child":[{"node_name":"0101","parent_id":113744,"node_id":113952,"child":[],"level":"6"},{"node_name":"0102","parent_id":113744,"node_id":113953,"child":[],"level":"6"},{"node_name":"0103","parent_id":113744,"node_id":113954,"child":[],"level":"6"},{"node_name":"0104","parent_id":113744,"node_id":113955,"child":[],"level":"6"},{"node_name":"0105","parent_id":113744,"node_id":113956,"child":[],"level":"6"},{"node_name":"0106","parent_id":113744,"node_id":113957,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113696,"node_id":113745,"child":[{"node_name":"0201","parent_id":113745,"node_id":113958,"child":[],"level":"6"},{"node_name":"0202","parent_id":113745,"node_id":113959,"child":[],"level":"6"},{"node_name":"0203","parent_id":113745,"node_id":113960,"child":[],"level":"6"},{"node_name":"0204","parent_id":113745,"node_id":113961,"child":[],"level":"6"},{"node_name":"0205","parent_id":113745,"node_id":113962,"child":[],"level":"6"},{"node_name":"0206","parent_id":113745,"node_id":113963,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113696,"node_id":113746,"child":[{"node_name":"0301","parent_id":113746,"node_id":113964,"child":[],"level":"6"},{"node_name":"0302","parent_id":113746,"node_id":113965,"child":[],"level":"6"},{"node_name":"0303","parent_id":113746,"node_id":113966,"child":[],"level":"6"},{"node_name":"0304","parent_id":113746,"node_id":113967,"child":[],"level":"6"},{"node_name":"0305","parent_id":113746,"node_id":113968,"child":[],"level":"6"},{"node_name":"0306","parent_id":113746,"node_id":113969,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113696,"node_id":113747,"child":[{"node_name":"0401","parent_id":113747,"node_id":113970,"child":[],"level":"6"},{"node_name":"0402","parent_id":113747,"node_id":113971,"child":[],"level":"6"},{"node_name":"0403","parent_id":113747,"node_id":113972,"child":[],"level":"6"},{"node_name":"0404","parent_id":113747,"node_id":113973,"child":[],"level":"6"},{"node_name":"0405","parent_id":113747,"node_id":113974,"child":[],"level":"6"},{"node_name":"0406","parent_id":113747,"node_id":113975,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"},{"node_name":"2栋","parent_id":113687,"node_id":113689,"child":[{"node_name":"1单元","parent_id":113689,"node_id":113701,"child":[{"node_name":"1层","parent_id":113701,"node_id":113764,"child":[{"node_name":"0101","parent_id":113764,"node_id":114072,"child":[],"level":"6"},{"node_name":"0102","parent_id":113764,"node_id":114073,"child":[],"level":"6"},{"node_name":"0103","parent_id":113764,"node_id":114074,"child":[],"level":"6"},{"node_name":"0104","parent_id":113764,"node_id":114075,"child":[],"level":"6"},{"node_name":"0105","parent_id":113764,"node_id":114076,"child":[],"level":"6"},{"node_name":"0106","parent_id":113764,"node_id":114077,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113701,"node_id":113765,"child":[{"node_name":"0201","parent_id":113765,"node_id":114078,"child":[],"level":"6"},{"node_name":"0202","parent_id":113765,"node_id":114079,"child":[],"level":"6"},{"node_name":"0203","parent_id":113765,"node_id":114080,"child":[],"level":"6"},{"node_name":"0204","parent_id":113765,"node_id":114081,"child":[],"level":"6"},{"node_name":"0205","parent_id":113765,"node_id":114082,"child":[],"level":"6"},{"node_name":"0206","parent_id":113765,"node_id":114083,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113701,"node_id":113766,"child":[{"node_name":"0301","parent_id":113766,"node_id":114084,"child":[],"level":"6"},{"node_name":"0302","parent_id":113766,"node_id":114085,"child":[],"level":"6"},{"node_name":"0303","parent_id":113766,"node_id":114086,"child":[],"level":"6"},{"node_name":"0304","parent_id":113766,"node_id":114087,"child":[],"level":"6"},{"node_name":"0305","parent_id":113766,"node_id":114088,"child":[],"level":"6"},{"node_name":"0306","parent_id":113766,"node_id":114089,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113701,"node_id":113767,"child":[{"node_name":"0401","parent_id":113767,"node_id":114090,"child":[],"level":"6"},{"node_name":"0402","parent_id":113767,"node_id":114091,"child":[],"level":"6"},{"node_name":"0403","parent_id":113767,"node_id":114092,"child":[],"level":"6"},{"node_name":"0404","parent_id":113767,"node_id":114093,"child":[],"level":"6"},{"node_name":"0405","parent_id":113767,"node_id":114094,"child":[],"level":"6"},{"node_name":"0406","parent_id":113767,"node_id":114095,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"2单元","parent_id":113689,"node_id":113702,"child":[{"node_name":"1层","parent_id":113702,"node_id":113768,"child":[{"node_name":"0101","parent_id":113768,"node_id":114096,"child":[],"level":"6"},{"node_name":"0102","parent_id":113768,"node_id":114097,"child":[],"level":"6"},{"node_name":"0103","parent_id":113768,"node_id":114098,"child":[],"level":"6"},{"node_name":"0104","parent_id":113768,"node_id":114099,"child":[],"level":"6"},{"node_name":"0105","parent_id":113768,"node_id":114100,"child":[],"level":"6"},{"node_name":"0106","parent_id":113768,"node_id":114101,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113702,"node_id":113769,"child":[{"node_name":"0201","parent_id":113769,"node_id":114102,"child":[],"level":"6"},{"node_name":"0202","parent_id":113769,"node_id":114103,"child":[],"level":"6"},{"node_name":"0203","parent_id":113769,"node_id":114104,"child":[],"level":"6"},{"node_name":"0204","parent_id":113769,"node_id":114105,"child":[],"level":"6"},{"node_name":"0205","parent_id":113769,"node_id":114106,"child":[],"level":"6"},{"node_name":"0206","parent_id":113769,"node_id":114107,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113702,"node_id":113770,"child":[{"node_name":"0301","parent_id":113770,"node_id":114108,"child":[],"level":"6"},{"node_name":"0302","parent_id":113770,"node_id":114109,"child":[],"level":"6"},{"node_name":"0303","parent_id":113770,"node_id":114110,"child":[],"level":"6"},{"node_name":"0304","parent_id":113770,"node_id":114111,"child":[],"level":"6"},{"node_name":"0305","parent_id":113770,"node_id":114112,"child":[],"level":"6"},{"node_name":"0306","parent_id":113770,"node_id":114113,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113702,"node_id":113771,"child":[{"node_name":"0401","parent_id":113771,"node_id":114114,"child":[],"level":"6"},{"node_name":"0402","parent_id":113771,"node_id":114115,"child":[],"level":"6"},{"node_name":"0403","parent_id":113771,"node_id":114116,"child":[],"level":"6"},{"node_name":"0404","parent_id":113771,"node_id":114117,"child":[],"level":"6"},{"node_name":"0405","parent_id":113771,"node_id":114118,"child":[],"level":"6"},{"node_name":"0406","parent_id":113771,"node_id":114119,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"3单元","parent_id":113689,"node_id":113703,"child":[{"node_name":"1层","parent_id":113703,"node_id":113772,"child":[{"node_name":"0101","parent_id":113772,"node_id":114120,"child":[],"level":"6"},{"node_name":"0102","parent_id":113772,"node_id":114121,"child":[],"level":"6"},{"node_name":"0103","parent_id":113772,"node_id":114122,"child":[],"level":"6"},{"node_name":"0104","parent_id":113772,"node_id":114123,"child":[],"level":"6"},{"node_name":"0105","parent_id":113772,"node_id":114124,"child":[],"level":"6"},{"node_name":"0106","parent_id":113772,"node_id":114125,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113703,"node_id":113773,"child":[{"node_name":"0201","parent_id":113773,"node_id":114126,"child":[],"level":"6"},{"node_name":"0202","parent_id":113773,"node_id":114127,"child":[],"level":"6"},{"node_name":"0203","parent_id":113773,"node_id":114128,"child":[],"level":"6"},{"node_name":"0204","parent_id":113773,"node_id":114129,"child":[],"level":"6"},{"node_name":"0205","parent_id":113773,"node_id":114130,"child":[],"level":"6"},{"node_name":"0206","parent_id":113773,"node_id":114131,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113703,"node_id":113774,"child":[{"node_name":"0301","parent_id":113774,"node_id":114132,"child":[],"level":"6"},{"node_name":"0302","parent_id":113774,"node_id":114133,"child":[],"level":"6"},{"node_name":"0303","parent_id":113774,"node_id":114134,"child":[],"level":"6"},{"node_name":"0304","parent_id":113774,"node_id":114135,"child":[],"level":"6"},{"node_name":"0305","parent_id":113774,"node_id":114136,"child":[],"level":"6"},{"node_name":"0306","parent_id":113774,"node_id":114137,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113703,"node_id":113775,"child":[{"node_name":"0401","parent_id":113775,"node_id":114138,"child":[],"level":"6"},{"node_name":"0402","parent_id":113775,"node_id":114139,"child":[],"level":"6"},{"node_name":"0403","parent_id":113775,"node_id":114140,"child":[],"level":"6"},{"node_name":"0404","parent_id":113775,"node_id":114141,"child":[],"level":"6"},{"node_name":"0405","parent_id":113775,"node_id":114142,"child":[],"level":"6"},{"node_name":"0406","parent_id":113775,"node_id":114143,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"4单元","parent_id":113689,"node_id":113704,"child":[{"node_name":"1层","parent_id":113704,"node_id":113776,"child":[{"node_name":"0101","parent_id":113776,"node_id":114144,"child":[],"level":"6"},{"node_name":"0102","parent_id":113776,"node_id":114145,"child":[],"level":"6"},{"node_name":"0103","parent_id":113776,"node_id":114146,"child":[],"level":"6"},{"node_name":"0104","parent_id":113776,"node_id":114147,"child":[],"level":"6"},{"node_name":"0105","parent_id":113776,"node_id":114148,"child":[],"level":"6"},{"node_name":"0106","parent_id":113776,"node_id":114149,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113704,"node_id":113777,"child":[{"node_name":"0201","parent_id":113777,"node_id":114150,"child":[],"level":"6"},{"node_name":"0202","parent_id":113777,"node_id":114151,"child":[],"level":"6"},{"node_name":"0203","parent_id":113777,"node_id":114152,"child":[],"level":"6"},{"node_name":"0204","parent_id":113777,"node_id":114153,"child":[],"level":"6"},{"node_name":"0205","parent_id":113777,"node_id":114154,"child":[],"level":"6"},{"node_name":"0206","parent_id":113777,"node_id":114155,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113704,"node_id":113778,"child":[{"node_name":"0301","parent_id":113778,"node_id":114156,"child":[],"level":"6"},{"node_name":"0302","parent_id":113778,"node_id":114157,"child":[],"level":"6"},{"node_name":"0303","parent_id":113778,"node_id":114158,"child":[],"level":"6"},{"node_name":"0304","parent_id":113778,"node_id":114159,"child":[],"level":"6"},{"node_name":"0305","parent_id":113778,"node_id":114160,"child":[],"level":"6"},{"node_name":"0306","parent_id":113778,"node_id":114161,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113704,"node_id":113779,"child":[{"node_name":"0401","parent_id":113779,"node_id":114162,"child":[],"level":"6"},{"node_name":"0402","parent_id":113779,"node_id":114163,"child":[],"level":"6"},{"node_name":"0403","parent_id":113779,"node_id":114164,"child":[],"level":"6"},{"node_name":"0404","parent_id":113779,"node_id":114165,"child":[],"level":"6"},{"node_name":"0405","parent_id":113779,"node_id":114166,"child":[],"level":"6"},{"node_name":"0406","parent_id":113779,"node_id":114167,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"5单元","parent_id":113689,"node_id":113705,"child":[{"node_name":"1层","parent_id":113705,"node_id":113780,"child":[{"node_name":"0101","parent_id":113780,"node_id":114168,"child":[],"level":"6"},{"node_name":"0102","parent_id":113780,"node_id":114169,"child":[],"level":"6"},{"node_name":"0103","parent_id":113780,"node_id":114170,"child":[],"level":"6"},{"node_name":"0104","parent_id":113780,"node_id":114171,"child":[],"level":"6"},{"node_name":"0105","parent_id":113780,"node_id":114172,"child":[],"level":"6"},{"node_name":"0106","parent_id":113780,"node_id":114173,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113705,"node_id":113781,"child":[{"node_name":"0201","parent_id":113781,"node_id":114174,"child":[],"level":"6"},{"node_name":"0202","parent_id":113781,"node_id":114175,"child":[],"level":"6"},{"node_name":"0203","parent_id":113781,"node_id":114176,"child":[],"level":"6"},{"node_name":"0204","parent_id":113781,"node_id":114177,"child":[],"level":"6"},{"node_name":"0205","parent_id":113781,"node_id":114178,"child":[],"level":"6"},{"node_name":"0206","parent_id":113781,"node_id":114179,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113705,"node_id":113782,"child":[{"node_name":"0301","parent_id":113782,"node_id":114180,"child":[],"level":"6"},{"node_name":"0302","parent_id":113782,"node_id":114181,"child":[],"level":"6"},{"node_name":"0303","parent_id":113782,"node_id":114182,"child":[],"level":"6"},{"node_name":"0304","parent_id":113782,"node_id":114183,"child":[],"level":"6"},{"node_name":"0305","parent_id":113782,"node_id":114184,"child":[],"level":"6"},{"node_name":"0306","parent_id":113782,"node_id":114185,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113705,"node_id":113783,"child":[{"node_name":"0401","parent_id":113783,"node_id":114186,"child":[],"level":"6"},{"node_name":"0402","parent_id":113783,"node_id":114187,"child":[],"level":"6"},{"node_name":"0403","parent_id":113783,"node_id":114188,"child":[],"level":"6"},{"node_name":"0404","parent_id":113783,"node_id":114189,"child":[],"level":"6"},{"node_name":"0405","parent_id":113783,"node_id":114190,"child":[],"level":"6"},{"node_name":"0406","parent_id":113783,"node_id":114191,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"6单元","parent_id":113689,"node_id":113706,"child":[{"node_name":"1层","parent_id":113706,"node_id":113784,"child":[{"node_name":"0101","parent_id":113784,"node_id":114192,"child":[],"level":"6"},{"node_name":"0102","parent_id":113784,"node_id":114193,"child":[],"level":"6"},{"node_name":"0103","parent_id":113784,"node_id":114194,"child":[],"level":"6"},{"node_name":"0104","parent_id":113784,"node_id":114195,"child":[],"level":"6"},{"node_name":"0105","parent_id":113784,"node_id":114196,"child":[],"level":"6"},{"node_name":"0106","parent_id":113784,"node_id":114197,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113706,"node_id":113785,"child":[{"node_name":"0201","parent_id":113785,"node_id":114198,"child":[],"level":"6"},{"node_name":"0202","parent_id":113785,"node_id":114199,"child":[],"level":"6"},{"node_name":"0203","parent_id":113785,"node_id":114200,"child":[],"level":"6"},{"node_name":"0204","parent_id":113785,"node_id":114201,"child":[],"level":"6"},{"node_name":"0205","parent_id":113785,"node_id":114202,"child":[],"level":"6"},{"node_name":"0206","parent_id":113785,"node_id":114203,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113706,"node_id":113786,"child":[{"node_name":"0301","parent_id":113786,"node_id":114204,"child":[],"level":"6"},{"node_name":"0302","parent_id":113786,"node_id":114205,"child":[],"level":"6"},{"node_name":"0303","parent_id":113786,"node_id":114206,"child":[],"level":"6"},{"node_name":"0304","parent_id":113786,"node_id":114207,"child":[],"level":"6"},{"node_name":"0305","parent_id":113786,"node_id":114208,"child":[],"level":"6"},{"node_name":"0306","parent_id":113786,"node_id":114209,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113706,"node_id":113787,"child":[{"node_name":"0401","parent_id":113787,"node_id":114210,"child":[],"level":"6"},{"node_name":"0402","parent_id":113787,"node_id":114211,"child":[],"level":"6"},{"node_name":"0403","parent_id":113787,"node_id":114212,"child":[],"level":"6"},{"node_name":"0404","parent_id":113787,"node_id":114213,"child":[],"level":"6"},{"node_name":"0405","parent_id":113787,"node_id":114214,"child":[],"level":"6"},{"node_name":"0406","parent_id":113787,"node_id":114215,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"7单元","parent_id":113689,"node_id":113707,"child":[{"node_name":"1层","parent_id":113707,"node_id":113788,"child":[{"node_name":"0101","parent_id":113788,"node_id":114216,"child":[],"level":"6"},{"node_name":"0102","parent_id":113788,"node_id":114217,"child":[],"level":"6"},{"node_name":"0103","parent_id":113788,"node_id":114218,"child":[],"level":"6"},{"node_name":"0104","parent_id":113788,"node_id":114219,"child":[],"level":"6"},{"node_name":"0105","parent_id":113788,"node_id":114220,"child":[],"level":"6"},{"node_name":"0106","parent_id":113788,"node_id":114221,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":113707,"node_id":113789,"child":[{"node_name":"0201","parent_id":113789,"node_id":114222,"child":[],"level":"6"},{"node_name":"0202","parent_id":113789,"node_id":114223,"child":[],"level":"6"},{"node_name":"0203","parent_id":113789,"node_id":114224,"child":[],"level":"6"},{"node_name":"0204","parent_id":113789,"node_id":114225,"child":[],"level":"6"},{"node_name":"0205","parent_id":113789,"node_id":114226,"child":[],"level":"6"},{"node_name":"0206","parent_id":113789,"node_id":114227,"child":[],"level":"6"}],"level":"5"},{"node_name":"3层","parent_id":113707,"node_id":113790,"child":[{"node_name":"0301","parent_id":113790,"node_id":114228,"child":[],"level":"6"},{"node_name":"0302","parent_id":113790,"node_id":114229,"child":[],"level":"6"},{"node_name":"0303","parent_id":113790,"node_id":114230,"child":[],"level":"6"},{"node_name":"0304","parent_id":113790,"node_id":114231,"child":[],"level":"6"},{"node_name":"0305","parent_id":113790,"node_id":114232,"child":[],"level":"6"},{"node_name":"0306","parent_id":113790,"node_id":114233,"child":[],"level":"6"}],"level":"5"},{"node_name":"4层","parent_id":113707,"node_id":113791,"child":[{"node_name":"0401","parent_id":113791,"node_id":114234,"child":[],"level":"6"},{"node_name":"0402","parent_id":113791,"node_id":114235,"child":[],"level":"6"},{"node_name":"0403","parent_id":113791,"node_id":114236,"child":[],"level":"6"},{"node_name":"0404","parent_id":113791,"node_id":114237,"child":[],"level":"6"},{"node_name":"0405","parent_id":113791,"node_id":114238,"child":[],"level":"6"},{"node_name":"0406","parent_id":113791,"node_id":114239,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"}],"level":"2"},{"node_name":"B区","parent_id":111056,"node_id":136812,"child":[{"node_name":"1栋","parent_id":136812,"node_id":136813,"child":[{"node_name":"1单元","parent_id":136813,"node_id":136814,"child":[{"node_name":"1层","parent_id":136814,"node_id":136815,"child":[{"node_name":"0101","parent_id":136815,"node_id":136816,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"},{"node_name":"2栋","parent_id":136812,"node_id":136817,"child":[{"node_name":"1单元","parent_id":136817,"node_id":136818,"child":[{"node_name":"1层","parent_id":136818,"node_id":136820,"child":[{"node_name":"0101","parent_id":136820,"node_id":136824,"child":[],"level":"6"},{"node_name":"0102","parent_id":136820,"node_id":136825,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136818,"node_id":136821,"child":[{"node_name":"0201","parent_id":136821,"node_id":136826,"child":[],"level":"6"},{"node_name":"0202","parent_id":136821,"node_id":136827,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"2单元","parent_id":136817,"node_id":136819,"child":[{"node_name":"1层","parent_id":136819,"node_id":136822,"child":[{"node_name":"0101","parent_id":136822,"node_id":136828,"child":[],"level":"6"},{"node_name":"0102","parent_id":136822,"node_id":136829,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136819,"node_id":136823,"child":[{"node_name":"0201","parent_id":136823,"node_id":136830,"child":[],"level":"6"},{"node_name":"0202","parent_id":136823,"node_id":136831,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"}],"level":"2"},{"node_name":"管理处","parent_id":111056,"node_id":111060,"child":[],"level":"999"}],"level":"1"},"current_node_id":113694}

2. 后台返回的json小区数据2(json都没有level=2节点，开发规定)：
    
    {"tree":{"node_name":"测试无二道门","parent_id":-1,"node_id":136779,"child":[{"node_name":"管理处","parent_id":136779,"node_id":136810,"child":[],"level":"999"},{"node_name":"1栋","parent_id":136779,"node_id":136780,"child":[{"node_name":"1单元","parent_id":136780,"node_id":136782,"child":[{"node_name":"1层","parent_id":136782,"node_id":136786,"child":[{"node_name":"0101","parent_id":136786,"node_id":136794,"child":[],"level":"6"},{"node_name":"0102","parent_id":136786,"node_id":136795,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136782,"node_id":136787,"child":[{"node_name":"0201","parent_id":136787,"node_id":136796,"child":[],"level":"6"},{"node_name":"0202","parent_id":136787,"node_id":136797,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"2单元","parent_id":136780,"node_id":136783,"child":[{"node_name":"1层","parent_id":136783,"node_id":136788,"child":[{"node_name":"0101","parent_id":136788,"node_id":136798,"child":[],"level":"6"},{"node_name":"0102","parent_id":136788,"node_id":136799,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136783,"node_id":136789,"child":[{"node_name":"0201","parent_id":136789,"node_id":136800,"child":[],"level":"6"},{"node_name":"0202","parent_id":136789,"node_id":136801,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"},{"node_name":"2栋","parent_id":136779,"node_id":136781,"child":[{"node_name":"1单元","parent_id":136781,"node_id":136784,"child":[{"node_name":"1层","parent_id":136784,"node_id":136790,"child":[{"node_name":"0101","parent_id":136790,"node_id":136802,"child":[],"level":"6"},{"node_name":"0102","parent_id":136790,"node_id":136803,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136784,"node_id":136791,"child":[{"node_name":"0201","parent_id":136791,"node_id":136804,"child":[],"level":"6"},{"node_name":"0202","parent_id":136791,"node_id":136805,"child":[],"level":"6"}],"level":"5"}],"level":"4"},{"node_name":"2单元","parent_id":136781,"node_id":136785,"child":[{"node_name":"1层","parent_id":136785,"node_id":136792,"child":[{"node_name":"0101","parent_id":136792,"node_id":136806,"child":[],"level":"6"},{"node_name":"0102","parent_id":136792,"node_id":136807,"child":[],"level":"6"}],"level":"5"},{"node_name":"2层","parent_id":136785,"node_id":136793,"child":[{"node_name":"0201","parent_id":136793,"node_id":136808,"child":[],"level":"6"},{"node_name":"0202","parent_id":136793,"node_id":136809,"child":[],"level":"6"}],"level":"5"}],"level":"4"}],"level":"3"}],"level":"1"},"current_node_id":136779}

 