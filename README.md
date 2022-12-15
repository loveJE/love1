# love1
love1
str = "";
Regex r = new Regex("/\w[-\w.+]*@([A-Za-z0-9][-A-Za-z0-9]+\.)+[A-Za-z]{2,14}/");
if (!r.IsMatch(str))
{
	return "此次验证不通过";
}
//需要添加此引用：using System.Text.RegularExpressions;
