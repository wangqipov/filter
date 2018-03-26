# filter
过滤特殊字符



	// 清除掉所有特殊字符
    String regEx="[`~!@#$%^&*()+=|{}':;',\\[\\].<>/?~！@#￥%……&*（）——+|{}【】‘；：”“’\"。，、？\\\\]";
	Pattern p = Pattern.compile(regEx);
	Matcher m = p.matcher(str);
	return m.replaceAll("").trim();
