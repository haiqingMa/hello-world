# hello-world 一级标题
## my first git repository。二级标题
### Create by mahaiqing 2016.3.31。三级标题
#### This is a test message。四级标题

1. 我的第一个git存储库，数字列表
2. 2016.3.31创建。数字列表
3. 测试一下MarkDown语法定义；

***

* HELLO
* WORLD
* THANK
* YOU

| TableColumn1-左对齐 | TableColumn2-居中对齐 | TableCoulmn3-右对齐 |
| ------ |:--------:|------:|
| 12345 | 23456 | 34567 |
| ABCDE | **粗体文字在这里** | *斜体文字在这里* |
| WWW | THIS IS A TEST LANGUAGE DO YOU KNOW |  PP DD WW |
| 12345 | 23456 | 34567 |
| ~~ABCDE~~ | **粗体文字在这里** | *斜体文字在这里* |
| WWW | ==THIS IS A TEST LANGUAGE DO YOU KNOW== |  PP DD WW |


- HELLO
- WORLD
- THANK
- YOU


-------

`
render: function() {  
    var make = CAR_MAKES_AND_MODELS[this.state.carMake];  
    var selectionString = make.name + ' ' + make.models[this.state.modelIndex];  
    return (  
        <PickerIOS  
        itemStyle={{fontSize: 25, color: 'red', textAlign: 'left', fontWeight: 'bold'}}  
        selectedValue={this.state.carMake}  
        onValueChange={(carMake) => this.setState({carMake, modelIndex: 0})}>  
        {Object.keys(CAR_MAKES_AND_MODELS).map((carMake) => (  
            <PickerItemIOS  
            key={carMake}  
            value={carMake}  
            label={CAR_MAKES_AND_MODELS[carMake].name}  
            />  
        ))}  
        </PickerIOS>  
    );  
  },  
});  
`
