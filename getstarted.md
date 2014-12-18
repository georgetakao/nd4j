---
layout: page
title: "Getting Started"
description: ""
---
{% include JB/setup %}

# 簡単なスタート方法について

ND4Jを始めるためには、以下のプログラムをインストールする必要があります。

1. [Java](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#1-java)
2. [Github](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#2-github)
3. [Maven](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#3-maven)
4. [IDE for Java](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#4-ide-for-java)

<iframe width="750" height="560" src="//www.youtube.com/embed/D0TrW9ht2Qo" frameborder="0" allowfullscreen></iframe>

この手順に沿ってダウンロードすれば、どなたでも簡単にND4Jをスタートすることができます。

# 1. Java

### Javaとは何か
 [Java](http://ja.wikipedia.org/wiki/Java)とは、プログラミング言語及びコンピュータープラットフォームのことを指します。

### なぜ必要か
 Janaを活用することでプラットフォームに依存しないアプリケーションソフトウェアの開発と配備を行うことができます。

### Javaのバージョン確認方法
 コマンドラインに以下の文書を入力することで、既にインストールされているJavaのバージョンを確認することができます。

		java -version

 ND4Jを始めるためには「Java7」が必要になるため、古いバージョンをお使いの場合には、再度インストールが必要になります。

### インストール方法
 最新のJavaは[オラクルホームページ](https://java.com/ja/download/)を通じて、無料でダウンロードいただけます。ダウンロード方法はお使いの端末によって異なります。

# 2. GitHub

### GitHubとは
 [Github](http://en.wikipedia.org/wiki/GitHub) は [Revision Control System](http://ja.wikipedia.org/wiki/Revision_Control_System)に基づいた、ソフトウェア開発プロジェクトのための共有ウェブサービスであり, [open source](http://ja.wikipedia.org/wiki/オープンソース) projects向けの無料アカウントを提供しています。

### なぜ必要か
 GitHubをインストールしなくても、Mavenがあれば[JAR](http://ja.wikipedia.org/wiki/JAR_%28%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88%29)をコントロールすることはできます。しかし、プロジェクトの状況やバグの報告をチームメンバー間で共有する際には、GitHubが役立ちます。

### イントール状況の確認
 インストールプログラムにて、ご確認いただけます。

### インストール方法
 以下のURLを通じて無料でダウンロードいただけます。
[Macはこちら](https://mac.github.com/), [Windowsはこちら](https://windows.github.com/)
ND4Jのファイルを複製するためには以下の文章をterminal (Mac) もしくは Git Shell (Windows)へ入力してください。

      git clone https://github.com/SkymindIO/nd4j

# 3. Maven

### Mavenとは
 MavenとはJava用プロジェクト管理ツールとして活用される、[オープンソースソフトウェア](http://ja.wikipedia.org/wiki/%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%82%BD%E3%83%BC%E3%82%B9%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2)である。([Mavenホームページ](http://maven.apache.org/what-is-maven.html)), Mavenをインストールすることで、最新版のND4Jのば[JAR](http://ja.wikipedia.org/wiki/JAR_%28%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%83%95%E3%82%A9%E3%83%BC%E3%83%9E%E3%83%83%E3%83%88%29)を自動的にアップロードし続けることができます。

### なぜ必要か
 Mavenを活用することで、より簡単にND4JとDeeplearning4j projectsをインストールすることができます。なお、最終的にダウンロードする[IDE](http://ja.wikipedia.org/wiki/%E7%B5%B1%E5%90%88%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83)を操作するうえでも、Mavenは役立ちます。([IDE](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#4-ide-for-java))また、もしMavenの内容をご理解いただいているは、以下の[downloads](http://nd4j.org/downloads.html) ページにアクセスいただくことで、この過程をスキップすることができます。

### イントール状況の確認
コマンドラインに、以下のコードをご入力ください。

		mvn --version

### インストール方法
以下のURLを通じて、無料でダウンロードいただけます
[here](https://maven.apache.org/download.cgi). 

お持ちのパソコンのオペレーティングシステムに適応する、最新版のMavenを含む圧縮ファイルをダウンロードしてください。
*"Unix-based Operating Systems (Linux, Solaris and Mac OS X)."* 

If you want to develop for ND4J, just *git clone* the software (explained above) and run this Maven command within the ND4J directory:

    mvn clean install -DskipTests -Dmaven.javadoc.skip=true


# 4. IDE for Java

### What it is
An Integrated Development Environment ([IDE](http://encyclopedia.thefreedictionary.com/integrated+development+environment)) will allow you to edit the source code, debug it and build it with a few clicks. The ones suggested here will use your installed version of Java, will talk with GitHub and Maven, which will take care of the dependencies for you. Visit our [dependencies](http://nd4j.org/dependencies.html) page to know how to 'easily' change the dependencies later on.

### Why you need it
You want to set up a hassle-free development environment so that you only worry about your code.

### Is it already installed?
Just check your installed programs.

### Installation
We recommend installing [IntelliJ](https://www.jetbrains.com/idea/download/). You will be perfectly fine with the free community edition.

For picky ones, these are some equivalent IDEs: [Eclipse](http://books.sonatype.com/m2eclipse-book/reference/creating-sect-importing-projects.html) or [Netbeans](http://wiki.netbeans.org/MavenBestPractices).

Now you can easily import the ND4J project via [Intellij](http://stackoverflow.com/questions/1051640/correct-way-to-add-lib-jar-to-an-intellij-idea-project) (or again, for picky ones via [Eclipse](http://stackoverflow.com/questions/3280353/how-to-import-a-jar-in-eclipse) or [Netbeans](http://gpraveenkumar.wordpress.com/2009/06/17/abc-to-import-a-jar-file-in-netbeans-6-5/)).

# Next Steps

Now you're ready to run the examples cited in our [documentation](../elementwise.html). We recommend that you launch your IDE, load the ND4J project and open the examples subdirectory. Locate one of them and click run. If everything was installed correctly you should see numbers appear as the program output. You can start inspecting/messing with the code.

Once you are comfortable with the examples, you might want to change the dependencies defined in the POM files. Learn how to change the [dependencies here](http://nd4j.org/dependencies.html).

For further questions or feedback please contact us through our [Google Groups Forum](https://groups.google.com/forum/#!forum/nd4j).

Useful links:

* ND4J [project](http://nd4j.org/) and [Github repository](https://github.com/SkymindIO/nd4j).
* DeepLearning4J [project](http://deeplearning4j.org/) and [Github repository](https://github.com/SkymindIO/deeplearning4j).


