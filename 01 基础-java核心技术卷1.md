java中没有无符号数值的概念，为了跨平台的移植性，java中的int都是4字节，short都是2字节，long是8字节，float是4字节，double是8字节   
java中不区分变量的声明和定义   
java中常量使用final定义，对于类常量使用 public static final 来定义   
java中的字符串和c++中不一样，java中的string是对象，不是字符型数组，同时需要注意到java中的字符串是不可以修改的类型！！！！
java中字符串判断内容是否相等使用equals，不能使用==。==是判断是否是同一个对象   
java中不能在嵌套的两个块中定义相同的变量，会报错  
java中的数组与c++中动态定义在堆上的数组类似    
java中可以在类里设置main方法来测试类   
java中对象引用是按值传递的！！！如果想交换两个对象引用，可以使用封装类来实现，https://blog.csdn.net/sinat_36246371/article/details/53021839     
