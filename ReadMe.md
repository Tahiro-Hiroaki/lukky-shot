# サイト名

敬語道場

# 概要

就活生を対象にした、正しい敬語の使い方を実践的に学べるクイズサイトです。

# 使用言語・OSなど

HTML、CSS、JavaScript（v1.7）、Ruby on Rails（v6.0.3.4）

# 機能一覧

ログイン、ページ遷移、問題遷移（1問解いた後、次の問題へ移動）、レスポンス（回答に対する正解、不正解）、  
フォーム（入力した記述の回答を送信）、スコア（正解数の記録と階級の表示）

# 工夫した点

・問題形式が2つある。（選択、記述）  
・正解数を記録し、それに応じた階級が表示される。  
・1問解くごとに正解、不正解、解説が表示され、次の問題へと移動する。（以下のソースコード）

  function quiz1(){
    answer=document.getElementById("answer1").value;

    if(answer=="おうかがい"){
        alert("正解：「行く」の謙譲語→『伺う』、『参る』など");
        index += 1;
    }
    else{
        alert("不正解。正解は、おうかがい：「行く」の謙譲語→『伺う』、『参る』など");
    }   

    //クイズ１を非表示にして、クイズ２を表示させる関数を書く
    // noneで非表示
    document.getElementById("quiz_area1").style.display ="none";
    // blockで表示
    document.getElementById("quiz_area2").style.display ="block";
  }

# デモ動画
![UniConverter_20210126173231](https://user-images.githubusercontent.com/77783073/105836442-84483500-6010-11eb-87e1-f95eaa7361fb.gif)
![UniConverter_20210126180658](https://user-images.githubusercontent.com/77783073/105837167-a2626500-6011-11eb-8a28-abb7c8c2aaab.gif)
![UniConverter_20210126194416](https://user-images.githubusercontent.com/77783073/105837060-78a93e00-6011-11eb-83f7-b0c311c4ea8f.gif)  
テスト用アカウント  
・E-mial（test1234@outlook.com）  
・パスワード（test1234）

# 注意点

ページレイアウトはMicrosoft Edge、Google Chromeのwebブラウザーにのみ対応しております。  
他のブラウザーでは、レイアウトに大きなずれが生じる可能性があります。

# 作成情報

・作成者（田代裕誠）  
・所属（佐賀大学大学院1年生）  
・E-mail（shobon1019@outlook.com）

