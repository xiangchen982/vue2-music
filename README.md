# vue2.0-music

[![标签](https://img.shields.io/teamcity/codebetter/bt428.svg)]() [![标签](https://img.shields.io/npm/v/@cycle/core.svg)]() [![标签](https://img.shields.io/npm/dm/localeval.svg)]()


> Vue.js 打造高级实战——音乐 App
Vue2.0 云音乐播放器，QQ音乐API，可听QQ音乐高品质付费歌曲。 


## 项目截图

![vue2-music](http://ojmcn9nlw.qnssl.com/blog/20170901/173812115.png?imageslim)

### 安装与运行

```
git clone https://github.com/HuangCongqing/vue2-music.git

cd vue-music

npm install

npm run dev //服务端运行 访问 http://localhost:8080

npm run build 项目打包 

感兴趣的童鞋可以来个star


## 项目树
```
.
├── README.md
├── build
│   ├── build.js
│   ├── check-versions.js
│   ├── dev-client.js
│   ├── dev-server.js
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config
│   ├── dev.env.js
│   ├── index.js
│   └── prod.env.js
├── index.html
├── package.json
├── prod.server.js
├── src
│   ├── App.vue
│   ├── api
│   │   ├── config.js
│   │   ├── rank.js
│   │   ├── recommend.js
│   │   ├── search.js
│   │   ├── singer.js
│   │   └── song.js
│   ├── base
│   │   ├── confirm
│   │   │   └── confirm.vue
│   │   ├── listview
│   │   │   └── listview.vue
│   │   ├── loading
│   │   │   ├── loading.gif
│   │   │   └── loading.vue
│   │   ├── no-result
│   │   │   ├── no-result.vue
│   │   │   ├── no-result@2x.png
│   │   │   └── no-result@3x.png
│   │   ├── progress-bar
│   │   │   └── progress-bar.vue
│   │   ├── progress-circle
│   │   │   └── progress-circle.vue
│   │   ├── scroll
│   │   │   └── scroll.vue
│   │   ├── search-box
│   │   │   └── search-box.vue
│   │   ├── search-list
│   │   │   └── search-list.vue
│   │   ├── slider
│   │   │   └── slider.vue
│   │   ├── song-list
│   │   │   ├── first@2x.png
│   │   │   ├── first@3x.png
│   │   │   ├── second@2x.png
│   │   │   ├── second@3x.png
│   │   │   ├── song-list.vue
│   │   │   ├── third@2x.png
│   │   │   └── third@3x.png
│   │   ├── switches
│   │   │   └── switches.vue
│   │   └── top-tip
│   │       └── top-tip.vue
│   ├── common
│   │   ├── fonts
│   │   │   ├── music-icon.eot
│   │   │   ├── music-icon.svg
│   │   │   ├── music-icon.ttf
│   │   │   └── music-icon.woff
│   │   ├── image
│   │   │   └── default.png
│   │   ├── js
│   │   │   ├── cache.js
│   │   │   ├── config.js
│   │   │   ├── dom.js
│   │   │   ├── jsonp.js
│   │   │   ├── mixin.js
│   │   │   ├── singer.js
│   │   │   ├── song.js
│   │   │   └── util.js
│   │   └── stylus
│   │       ├── base.styl
│   │       ├── icon.styl
│   │       ├── index.styl
│   │       ├── mixin.styl
│   │       ├── reset.styl
│   │       └── variable.styl
│   ├── components
│   │   ├── add-song
│   │   │   └── add-song.vue
│   │   ├── disc
│   │   │   └── disc.vue
│   │   ├── m-header
│   │   │   ├── logo@2x.png
│   │   │   ├── logo@3x.png
│   │   │   └── m-header.vue
│   │   ├── music-list
│   │   │   └── music-list.vue
│   │   ├── player
│   │   │   └── player.vue
│   │   ├── playlist
│   │   │   └── playlist.vue
│   │   ├── rank
│   │   │   └── rank.vue
│   │   ├── recommend
│   │   │   └── recommend.vue
│   │   ├── search
│   │   │   └── search.vue
│   │   ├── singer
│   │   │   └── singer.vue
│   │   ├── singer-detail
│   │   │   └── singer-detail.vue
│   │   ├── suggest
│   │   │   └── suggest.vue
│   │   ├── tab
│   │   │   └── tab.vue
│   │   ├── top-list
│   │   │   └── top-list.vue
│   │   └── user-center
│   │       └── user-center.vue
│   ├── main.js
│   ├── router
│   │   └── index.js
│   └── store
│       ├── actions.js
│       ├── getters.js
│       ├── index.js
│       ├── mutation-types.js
│       ├── mutations.js
│       └── state.js
└── static
    ├── 1.png
    ├── 2.png
    ├── 3.png
    ├── 4.png
    └── 5.png

```

# vue-music
