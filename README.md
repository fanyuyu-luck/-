# uni-app swiper
uni-app 微信小程序 swiper轮播图 走马灯

使用：

```vue
<fy-swiper :posterList="posterList" @getItem="getItem"></fy-swiper>

import fySwiper from '../../../components/fy-swiper/fy-swiper.vue'
components:{
	fySwiper
},
getItem(e){
	console.log(e,'eeee')
},
```

