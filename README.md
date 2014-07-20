# jquery-selection [![spm version](http://spmjs.io/badge/jquery-selection)](http://spmjs.io/package/jquery-selection)

AUTHOR WEBSITE: [http://ydr.me/](http://ydr.me/)

jquery.fn.selection 输入框内选区操作

**五星提示：当前脚本未作优化、未完工，请勿用在生产环境**

__IT IS [A SPM PACKAGE](http://spmjs.io/package/jquery-selection).__





#USAGE
```
var $ = require('jquery');
require('jquery-selection')($);


// 1. 获取当前光标的开始位置
$("#input").selection().start;

// 2. 获取当前光标的结束位置
$("#input").selection().end;

// 3. 获取选中的文本内容
$("#input").selection().val;

// 4. 选中文本
$("#input").selection().select("text");

// 6. 设置光标的起始和结束位置
$("#input").selection().select(start);
$("#input").selection().select(start,end);

// 5. 定位光标
$("#input").selection().to(position);

// 7. 定位光标到文本起始位置
$("#input").selection().toStart();

// 8. 定位光标到文本结束位置
$("#input").selection().toEnd();

// 9. 插入文本到当前光标之前并选中该文本
$("#input").selection().before("text");

// 10. 插入文本到当前光标之后并选中该文本
$("#input").selection().after("text");

// 11. 替换当前选中的文本并选中该文本
$("#input").selection().replace("text");

// 12. 移除当前选中的文本
$("#input").selection().remove();

// 13. 在当前文本之前插入文本并选中该文本
$("#input").selection().prepend("text");

// 14. 在当前文本之后插入文本并选中该文本
$("#input").selection().append("text");

// 15. 在当前光标位置开始向前删除指定长度文本
$("#input").selection().backspace(length);

// 16. 在当前光标位置开始向后删除指定长度文本
$("#input").selection().delete(length);
```



#OPTIONS
```
null
```
