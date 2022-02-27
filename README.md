# fizz-buzz-hackathon

## 課題内容
1から100までの数を出力していき、3の倍数のときは数の代わりに｢Fizz｣、5の倍数のときは｢Buzz｣と出力し、3と5両方の倍数の場合に「FizzBuzz」と出力する。　　

## クリア条件
標準出力で正しくFizz, Buzz, FizzBuzzと出力されること。

## 使用したプログラム言語
・Java

## 動かし方  
・[dokojava](https://dokojava.jp/sources/Main.java)へ移動  
・ソースコードを入力  
・コンパイルをクリック  
・実行をクリック  

作成したソースコード  
```bash
public class Main{
 public static void main(String[] args){
  int i=1;
  do{
   if(i%3==0 && i%5==0){
    System.out.println("FizzBuzz");
   }else if(i%3==0){
    System.out.println("Fizz");
   }else if(i%5==0){
    System.out.println("Buzz");
   }else{
    System.out.println(i);
   }
   i++;
  }while(i<100);
 }
}
```
