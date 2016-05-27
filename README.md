# hello-world
## my first git repository。
### Create by mahaiqing 2016.3.31。
#### This is a test message。

1. 我的第一个git存储库
2. 2016.3.31创建。

***

* HELLO
* WORLD
* THANK
* YOU

| TableColumn1 | TableColumn2 | TableCoulmn3 |
| ------------ |:------------:|-------------:|
| 12345 | 23456 | 34567 |
| ABCDE | EDFGHJ | OOP |
| WWW | THIS IS A TEST | DDD |

- HELLO
- WORLD
- THANK
- YOU

**粗体文字在这里**
*斜体文字在这里*

'
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
'
