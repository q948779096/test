1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:var h1 = document.getElementById("h1");
			var str1="这是第一个字符串";
			var str2="这是第二个字符串";
			var d = str1.concat(str2);
			h1.innerHTML=d;

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:var money=parseInt(prompt("存储金额："));
			var h2=document.getElementById("h2");
			h2.innerHTML="您的存储金额为："+money;

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答: 
<script>
			var h3 = document.getElementById('h3');
			var a = 79387.348;
			var b = a.toFixed(2); 
			h3.innerHTML = b;
		</script>

4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:<img src="img/head/icon/1.jpg" id="img"/>
		<h4 id="h4"></h4>
		<script type="text/javascript">
			var img=document.getElementById("img");
			var h4=document.getElementById("h4");
			h4.innerHTML=img.src;
                </script>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答:<script>
			var h1 = document.getElementById('h1');
			var in1 = document.getElementById('in1');
			var btn = document.getElementById('btn');
			btn.onclick = function(){
				var s1 = in1.value
				var s2 = s1.toLowerCase()
				//console.log(s2);
				h1.innerHTML=s2;
				
			}
		</script>
