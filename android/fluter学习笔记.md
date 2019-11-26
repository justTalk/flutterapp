1.入口：void main() => runApp(MyApp());
2.flutter中view的基类是Widget,Widget只负责内容的布局，
3.flutter中view有对应的状态对象（State的子类），每个状态对象有四种状态：created,initialized, ready, defunct
4.每一次调用setState导致状态的改变都会触发该状态绑定的Widget对象重新创建
5.flutter中提供了基本的UI脚手架，类似于：Scaffold等，可以方便的搭建一些常用UI界面：比如上中下结构的界面或者Material风格的界面
