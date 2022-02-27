# FizzBuzz-issue

概要
1から100までの数を出力していき、3の倍数のときは数の代わりに｢Fizz｣、5の倍数のときは｢Buzz｣と出力し、3と5両方の倍数の場合に「FizzBuzz」と出力する。　　

## Deacription
詳細の説明

## 必要な要件
・JAVA

## How to run
動かし方  
・[dokojava](https://dokojava.jp/sources/Main.java)を開く  
・ソースコードを入力  
・コンパイルをクリック  
・実行をクリック  
↓ソースコード  
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
