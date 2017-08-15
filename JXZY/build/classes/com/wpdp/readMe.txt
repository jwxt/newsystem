
1、在Const.java文件中配置各个文件。
2、重新设置登录的路径：例如，public static final String LOGIN = "/login_toLogin.do";//登录地址
3、重新设置分页的条数：例如，public static final String PAGE= "admin/config/PAGE.txt";//分页条数配置路径

4、统一的日期设置：
	/**
	 * 获取YYYY格式
	 * @return
	 */  getYear() 

	/**
	 * 获取YYYY-MM-DD格式
	 * @return
	 */  getDay()
	
	/**
	 * 获取YYYYMMDD格式
	 * @return String
	 */  getDays()

	/**
	 * 获取YYYY-MM-DD HH:mm:ss格式
	 * @return String
	 */  getTime()
	 
	 /**
	 * 格式化日期 （获取YYYYMMDD格式）
	 * @return  Data
	 */  fomatDate(String date) 
	 
5、	 MD5处理

	/**
	 * MD5加密
	 * @param str
	 * @return
	 */  md5(String str)
	 
6、 ReflectHelper类，用于获取文件信息

7、手机号验证，checkMobileNumber（String）
	 
	 
	 
	 
	 