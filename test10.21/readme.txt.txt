1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:var h1 = document.getElementById("h1");
			var str1="���ǵ�һ���ַ���";
			var str2="���ǵڶ����ַ���";
			var d = str1.concat(str2);
			h1.innerHTML=d;

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:var money=parseInt(prompt("�洢���Ϊ��"));
			var h2=document.getElementById("h2");
			h2.innerHTML="���Ĵ洢���Ϊ��"+money;

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��: 
<script>
			var h3 = document.getElementById('h3');
			var a = 79387.348;
			var b = a.toFixed(2); 
			h3.innerHTML = b;
		</script>

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:<img src="img/head/icon/1.jpg" id="img"/>
		<h4 id="h4"></h4>
		<script type="text/javascript">
			var img=document.getElementById("img");
			var h4=document.getElementById("h4");
			h4.innerHTML=img.src;
                </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:<script>
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