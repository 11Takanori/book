<!-- # Object-Oriented Programming Features of Rust -->

# Rustのオブジェクト指向プログラミング機能

<!-- Object-oriented programming (OOP) is a way of modeling programs. Objects came -->
<!-- from Simula in the 1960s. Those objects influenced Alan Kay’s programming -->
<!-- architecture in which objects pass messages to each other. He coined the term -->
<!-- *object-oriented programming* in 1967 to describe this architecture. Many -->
<!-- competing definitions describe what OOP is; some definitions would classify -->
<!-- Rust as object oriented, but other definitions would not. In this chapter, -->
<!-- we'll explore certain characteristics that are commonly considered object -->
<!-- oriented and how those characteristics translate to idiomatic Rust. We’ll then -->
<!-- show you how to implement an object-oriented design pattern in Rust and discuss -->
<!-- the trade-offs of doing so versus implementing a solution using some of Rust’s -->
<!-- strengths instead. -->

オブジェクト指向プログラミング(OOP)は、プログラムをモデル化する手段です。オブジェクトは、
1960年代のSimulaで導入されました。このオブジェクトは、
お互いにメッセージを渡し合うというアラン・ケイ(Alan Kay)のプログラミングアーキテクチャに影響を及ぼしました。
彼は、このアーキテクチャを解説するために、*オブジェクト指向プログラミング*という用語を造語しました。
多くの競合する定義がOOPが何かを解説しています; Rustをオブジェクト指向と区分する定義もありますし、
しない定義もあります。この章では、広くオブジェクト指向と捉えられる特定の特徴と、
それらの特徴がこなれたRustでどう表現されるかを探求します。それからオブジェクト指向のデザインパターンをRustで実装する方法を示し、
そうすることとRustの強みを活用して代わりの解決策を実装する方法の代償を議論します。
