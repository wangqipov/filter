# filter
过滤特殊字符



	// 清除掉所有特殊字符
    String regEx="[`~!@#$%^&*()+=|{}':;',\\[\\].<>/?~！@#￥%……&*（）——+|{}【】‘；：”“’\"。，、？\\\\]";
	Pattern p = Pattern.compile(regEx);
	Matcher m = p.matcher(str);
	return m.replaceAll("").trim();





停服务sh s.sh 回车
起服务nohup sh s.sh &

杀进程
netstat -p 显示pid

kill -s 9 pid           //9表示强制

 ps -ef|grep java）

输出日志
grep -n 'g' p.log
 sed -n '236983050,236983800p' p.log 
 tail -f n.out
