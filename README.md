# js-basic
JavaScript のみの基本的な処理
## js-basic-01
![image](https://user-images.githubusercontent.com/1501327/129836056-bb8bca7d-0681-481e-82d7-85440e01dac7.png)
```javascript
function lang_test() {

    // 変数作成
    var work;

    work = document.getElementById("fld").value;

    if ( work == "1"  ) {
        alert( work + " : 一致しました" );
    }
    else {
        alert("一致しません。　1を入力してください");
    }

}
```
## js-basic-02
![image](https://user-images.githubusercontent.com/1501327/129836343-14af3fd3-d653-4908-b745-157915bfb0f4.png)
```javascript
function lang_test() {

    // 変数作成
    var work;

    // この時点では文字列
    work = document.getElementById("fld").value;

    // 整数に変換
    work = parseInt(work);

    if ( isNaN( work ) ) {
        alert("変換できません");
        return;
    }

    // 整数同士で比較
    if ( work < 1  ) {
        alert("★条件に一致します");
    }
    else {
        alert("条件に一致しません　0以下を入力してください");
    }

}
```
## js-basic-03
![image](https://user-images.githubusercontent.com/1501327/129836483-9b70c984-4d01-4341-abdb-26ecaefcf08d.png)
```javascript
function lang_test() {

    // 変数作成
    var work;

    console.log( typeof(work) );

    // この時点では文字列
    work = document.getElementById("fld").value;

    console.log( typeof(work) );

    // 整数に変換
    work = parseInt(work);

    console.log( typeof(work) );

    if ( isNaN( work ) ) {
        alert("変換できません");
        return;
    }

    // 整数同士で比較
    if ( work < 1  ) {
        alert("★条件に一致します");
    }
    else {
        alert("条件に一致しません　0以下を入力してください");
    }

}
```


