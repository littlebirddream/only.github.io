# only.github.io
<!DOCTYPE html>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="http://cdn.zhouql.vip/cdn/2023fire/main.css">
	<link rel="shortcut icon" href="http://cdn.zhouql.vip/cdn/2023fire/%E6%96%B0%E5%B9%B4.png" type="image/x-icon">
	<!-- 这里修改标题 -->
	<title>2023兔年快乐</title>
	<script>
		// 这里是祝福，注意符号输入切换到英文 🧸
		var bless = [
			"呆瓜勇者",
			"李孟然",
			"新的一年里，希望lmr快快乐乐，健健康康♥"
		]
		// 祝福文字修改 🌴
		var blessStyle = {
			color: "#c7f0ff",          	    // 文字颜色
			shadowColor: "#00aeec",   // 文字阴影颜色
			fontSize: "3",   		 // 文字大小
			blod: 1                 		// 文字加粗，1加粗，0不加粗
		}
		// 音乐配置 🎵
		var music = {
			src: "https://music.163.com/song/media/outer/url?id=529257644",  // 音乐地址，不需要音乐，写成""
			loop: 1,		// 音乐循环播放吗？ 1循环播放 0 只播放一遍
			volume: 1,		// 音乐大小，默认为1，范围【0~1】，注意0~1
		}
	</script>
</head>

<body onselectstart="return false">
	<canvas id='cas' style="background-color:rgba(0,5,24,1)">不支持canvas</canvas>
	<div class="city"><img src="http://cdn.zhouql.vip/cdn/2023fire/city.png" alt="" /></div>
	<img src="http://cdn.zhouql.vip/cdn/2023fire/moon.png" alt="" id="moon" style="visibility: hidden;" />
	<div class="content"></div>
	<script src="http://cdn.zhouql.vip/cdn/2023fire/main.js"></script>
</body>

</html>
