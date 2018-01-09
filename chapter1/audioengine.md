# audioengine
## 模块: cc
> cc.audioengine是单例对象。
* 主要用来播放音频，播放的时候会返回一个 audioID，之后都可以通过这个 audioID 来操作这个音频对象。
* 不使用的时候，请使用 cc.audioEngine.uncache(filePath); 进行资源释放 
注意：
<pre>在 Android 系统浏览器上，不同浏览器，不同版本的效果不尽相同。<br/>
比如说：大多数浏览器都需要用户物理交互才可以开始播放音效，<br/>
有一些不支持 WebAudio，有一些不支持多音轨播放。<br/>
总之如果对音乐依赖比较强，请做尽可能多的测试。</pre>
