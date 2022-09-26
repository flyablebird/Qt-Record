QObject::tr（使用多级函数调用来翻译，影响效率）一般不要使用，除非国际化。
creator无论使用何种编码(比如utf-8,gbk,system)，其中硬编码的中文转为QString时，都是使用System编码的
