# Noob Note

* 格式化代码：`ctrl` + `i`
* `F1`查看定义


# Qt QML GUI Programing



* [查找色块](https://www.w3.org/TR/css-color-3/#svg-color)




# Qt C++ GUI Programing

 ## ｗｉｄｇｅｔ中的信号与槽

槽：处理函数，发送的信号，需要处理，处理的函数即为槽



两种写法：

```
connect(closeButton, SIGNAL(clicked()), this, SLOT(close()));
connect(closeButton, &QPushButton::clicked, this, &FindDialog::c;lose);
//connect(信号的发送者，信号函数的地址，信号的接收者，槽的地址)；
```