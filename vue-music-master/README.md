# 基于vue的音乐移动端web app
* 主要功能有：推荐歌单、搜索歌曲、歌词滚动等;
## 用到的部分技术

* 构建工具：Vue cli3;
* 框架：Vue + Vue router + Vuex;
* http请求：axios;
* 歌词滚动：better-scroll;
* 部分UI组件：Vux;

## 运行此项目  
  npm install
  
  npm run serve (开发编译)

  npm run build (打包发布)
  ```

## 项目结构

<details>
<summary>展开查看</summary>
<pre><code>

│  App.vue    //根组件
│  main.js    //项目入口
│  router.js  //vue router路由配置
│
├─api                       
│      getData.js           // Api数据请求参数配置
│
├─assets                    // 静态资源
│      disc_default.png
│      disc_plus.png
│      find.svg
│      foot.svg
│      footbg.png
│      hot_bg.jpg
│      hot_icon.png
│      like.svg
│      logo.svg
│      needle_plus.png
│      playbar.png
│      play_btn.png
│
├─components               //组件目录
│  │  comment.vue          //单个评论组件
│  │  header.vue           //首页头部
│  │  miniPlayer.vue       //底部迷你播放器
│  │  song.vue             //单个歌曲组件
│  │  
│  ├─indexTab              //index选项卡
│  │      footer.vue       //index底部
│  │      index.vue        //index选项卡组件入口
│  │      recommendList.vue  //推荐歌单组件
│  │
│  ├─rankTab               //排行榜选项卡
│  │      index.vue        //排行榜组件
│  │      
│  └─searchTab             //搜索选项卡
│          index.vue       //搜索选项卡组件入口
│          trending.vue    //热门搜索词组件
│
├─page                     //页面目录
│      home.vue            //主页
│      player.vue          //播放页面
│      playList.vue        //歌单页面
│
├─store                    //Vuex
│      actions.js
│      getters.js
│      index.js
│      mutations.js
│      state.js
│
├─styles                    //css目录
│      comment.css
│      player.css
│      playlist_page.css
│      remd_list.css
│      song_item.css
│
└─utils                      //公用JS目录
        global.js            //图片懒加载配置
        lrcparse.js          //歌词数据解析

</code></pre>

</details>
