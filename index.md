## GlassPE下载站

欢迎来到GlassPE下载站，版权所有@Bilibili.com 爱玩电脑的命令提示符
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
<link rel="icon" href="logo.ico">
<div id="poem_sentence"></div>
<div id="poem_info"></div>
<script type="text/javascript">
  jinrishici.load(function(result) {
    var sentence = document.querySelector("#poem_sentence")
    var info = document.querySelector("#poem_info")
    sentence.innerHTML = result.data.content
    info.innerHTML = '【' + result.data.origin.dynasty + '】' + result.data.origin.author + '《' + result.data.origin.title + '》'
  });
</script>

<div align="center">
