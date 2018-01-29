正则：字符串检索或替换的规则
/\d\d\d/.test("123");//true
new RegExp("Bosn").test("Hi,Bosn");//true
/\^abc/.test("^abc");//true, \为转义
