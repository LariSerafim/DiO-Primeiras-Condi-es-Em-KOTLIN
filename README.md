# DiO-Primeiras-Condi-es-Em-KOTLIN
//Desafio Faça um programa que receba  Caso a média seja &lt; 5 imprima "REP"; Caso a média seja >= 5 e &lt; 7 imprima "REC"; Caso a média seja >7 imprima "APR".


fun main() {

  val media = readLine()!!.toDouble();

  

  when {

    media < 5 -> println("REP");

    media < 7 -> println("REC")

    else -> println("APR")

  }

}
