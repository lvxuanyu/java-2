# java-2
一、实验目的

（1）初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；

（2）掌握面向对象的类设计方法（属性、方法）；

（3）掌握类的继承用法，通过构造方法实例化对象；

（4）学会使用super()，用于实例化子类；

（5）掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。


二、实验要求

1.编写上述实体类以及测试主类（注意类之间继承关系的适用）

2.在测试主类中，实例化多个类实体，模拟学生选课操作、打印课程信息（信息包括：编号、课程名称、上课地点、时间、授课教师 等）；模拟学生退课操作，再打印课程信息。

3.编写实验报告。


三、实验过程

1.确定Personnel为父类，Teacher和Student为子类， 用extends继承父类的属性和方法

2.确定每个类所拥有的属性并依据属性类型定义为整型，字符型等

3.利用super函数调用父类的构造方法，实例化子类

4.用this关键字给每一个变量传递它们的值

5.在父类Personnel和Courses类里利用toString来返回字符串本身，生成的值可以很直观的看出内容

6. 利用Scanner来获取用户的输入，跟if一起实现判断选课和退课的操作，利用while和break对于退课环节加深处理，只能退已选课程

7.最后把所有需要的信息输出出来


四、核心代码
package Homework2;

public class Course {
       String bianhao;
       String name;
       String dress;
       String time;
       Teacher teacher;
       Course(){
    	   
       }
       Course(String bianhao,String name,String dress,String time,Teacher teacher){
    	   this.bianhao=bianhao;
           this.name=name;
           this.dress=dress;
           this.time=time;
           this.teacher=teacher;
       }
  五、实验感想
于if循环函数加深了了解，尤其是使用循环函数时一定要注意break函数的使用。对于extends继承函数也有了初步的了解，还有super关键字直接访问父类的属性，用toString更容易直观看出内容。这次的实验需要先确定类和对象，找好继承关系，接下来就相对容易一些，通过这次实验我收获很大。
