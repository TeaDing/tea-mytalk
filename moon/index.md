## Hi 亲爱的，当你看到这个时候应该已经拿到了茉莉香水
## 为什么那么多的香水中我选中了茉莉香水呢
## 这来自一段歌词
## 如果成功的话你可以听到这段《念念不忘》
## "赠你哈罗基蒂那玩具，这天却变作茉莉香水"
## 谈到这首歌呢，大概的意思就是男主念念不忘女主十年，十年后的物是人非，天真少女手中的Hello Kitty玩具也变成了茉莉香水
## 人总是在变的，我有时候常常在想我们之间那没有联系的三四年中各自的变化，接触的人和事物造就了今天的你我
## 或许你曾经喜欢过Hello Kitty，那时候的我没有给你过，没有机会给，今天这你手中的茉莉香水是否也是你喜欢的呢

  <audio id="bg-audio" src="bg.mp3" loop="loop" autoplay="autoplay"></audio>

*js*

    var bgAudio = document.getElementById('bg-audio');
    bgAudio.load();
    bgAudio.play();
    // 兼容在微信里自动播放
    document.addEventListener("WeixinJSBridgeReady", function () {
        bgAudio.load();
        bgAudio.play();
    }, false);
