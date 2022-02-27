# FizzBuzz-issue

概要

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
