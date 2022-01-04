# Command pattern
...いってみれば、オブジェクト指向でクロージャー(関数)を実現するようなものかもしれない。  
本来であれば実行ごとに破棄される引数や周辺環境などを、オブジェクトという形に保存することで、同じ条件での再実行や複製を可能にする。

オブジェクト指向に慣れた諸氏にはCommand patternでの実装のほうが馴染みやすい部分はあるだろう。  
関数型プログラミングのスタイルで書くなら、関数と引数でおおかたの役者が揃うクロージャーでの記述量が少なく、見やすくなるかもしれない。