1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��: var h1 = document.getElementById(h1);
      var s1 = '123';
      var s2 = '456';
      var s3 = s1.concat(s2);
      console.log(s3);

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:<script type="text/javascript">
			var btn=document.getElementById("btn");
			var txt=document.getElementById("txt");
			var h2=document.getElementById("h2");
			btn.onclick=function(){
				var mp= txt.value.padEnd(6,"0");
				h2.innerHTML="���Ĵ洢���Ϊ��"+mp;
			}
		</script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��: <script>
        var h3 = document.getElementById('h3');
        var num = new Number(79387.348);
        h3.innerHTML = num.toFixed(2);
    </script>

4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:   <script>
			var img=document.getElementById("img");
			var h4=document.getElementById("h4");
			h4.innerHTML=img.src;

    </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����
��: <script type="text/javascript">
                var txt = document.getElementById("txt");
                var pwd = document.getElementById("pwd");
                var btn = document.getElementById("btn");
                var code = 'ABCDE';
                btn.onclick=function(){
                    if(pwd.value=="123"){
                    }else{
                        alert("���벻��ȷ����������");
                    }
                    do{
                        var nums=prompt('��������֤��'+code);
                        if(nums.toLowerCase()==code.toLowerCase()){
                            alert('ͨ��');
                            
                            break;
                        }else{
                            alert('����');
                        }
                    }while(true)
                }
            </script>
        
