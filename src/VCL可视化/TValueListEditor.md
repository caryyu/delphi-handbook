# Delphi TValueListEditor

**新增**

```pascal
ValueListEditor1.InsertRow('pp', 'pp1', true);
```

* 第一个参数：key 的值(字符串型)
* 第二个参数：value 的值(字符串型)
* 第三个参数：是否追加, `true` 在最后一行追加, `false` 在获得焦点的一行的后面加上一行.

**修改**

可以修改对应 Key 的值, 如你想修改第四行的值(索引不能超过已有行数):

```pascal
ValueListEditor1.Keys[1] := 'Name';
```

根据已知的 Key 修改其 Value，如下:

```pascal
ValueListEditor1.Values['Name'] := 'Tom';
```

**删除**

根据索引删除指定行:

```pascal
ValueListEditor1.DeleteRow(1);
```

**属性与方法**

| 属性/方法 | 取值 | 备注
| - | - | - | 
| Keys | 字符串 | 根据行索引修改 Key 的值, `Keys[1] := 'Name'` 
| Values | 字符串 | 根据 Key 修改 Value 的值, `Values['Name'] := 'Tom'`
| KeyOptions | keyEdit, keyAdd, keyDelete, keyUnique | 可编辑与否, keyUnique 表示 KV 对不允许重复, KeyOptions := [keyEdit,...]
