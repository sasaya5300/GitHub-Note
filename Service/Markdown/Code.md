# コードの挿入

## インラインコード
* 文章中に含まれるコード `a = b;` は `` ` (バッククォート、日本語キーだと Shift + @)`` で囲む
* インラインコード中に `n ` 回連続の `` ` `` を含めたい場合は、 `n + 1` 回の `` ` `` で囲む
* `` ` ``のみの場合には前後に空白を入れる



## ブロックコード
* バッククォート `3` つのみで出来た行で囲む
* バッククォート行の前後には空行が必用
* 最初の ```` ``` ```` の直後に言語コードを入れれば指定した言語としてシンタックスハイライトが効く
* `GitHub` ではファイル名が入らない？

> (空行)  
> \`\`\` csharp:Class.cs  
> public class Class  
> {  
> }  
> \`\`\`  
> (空行)

```csharp:Class.cs
public class Class
{
}
```



## 言語

| 言語     | 言語コード                    | 拡張子                                                                       |
|:---------|:----------------------------|:----------------------------------------------------------------------------|
| Makefile | make, makefile, mf, bsdmake | *.mak, *.mk, Makefile, makefile, Makefile.*, GNUmakefile                    |
| C        | c                           | *.c, *.h, *.idc                                                             |
| CMake    | cmake                       | *.cmake, CMakeLists.txt                                                     |
| C++      | cpp, c++                    | *.cpp, *.hpp, *.c++, *.h++, *.cc, *.hh, *.cxx, *.hxx, *.C, *.H, *.cp, *.CPP |
| C#       | csharp, C#                  | *.cs                                                                        |
| VB.net   | vb.net, vbnet               | *.vb, *.bas                                                                 |
| verilog  | verilog, v                  | *.v                                                                         |
| vhdl     | vhdl                        | *.vhdl, *.vhd                                                               |
| Scala    | scala                       | *.scala                                                                     |
| Haskell  | haskell, hs                 | *.hs                                                                        |


## 参考資料
* [Pygmentsの対応言語一覧](http://hhsprings.pinoko.jp/site-hhs/2015/06/pygments%E3%81%AE%E5%AF%BE%E5%BF%9C%E8%A8%80%E8%AA%9E%E4%B8%80%E8%A6%A7/)
