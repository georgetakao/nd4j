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
[Github](http://en.wikipedia.org/wiki/GitHub) is a web-based [Revision Control System](http://en.wikipedia.org/wiki/Revision_control), _the [de facto host](http://opensource.com/life/12/11/code-hosting-comparison) for open source projects_ (click [here](http://en.wikipedia.org/wiki/Comparison_of_open-source_software_hosting_facilities) for a comparison between existing open-source software hosting facilities).

### Why you need it
If you just want to use the ND4J libraries, you do not need GitHub, Maven will take care of the .jar files. However, if you are planning to contribute to the [ND4J](https://github.com/SkymindIO/nd4j) or the [DeepLearning4J](https://github.com/SkymindIO/deeplearning4j) project, you are very welcome to report bugs. By the way, thanks for all the people already doing so.

### Is it already installed?
Just check your installed programs.

### Installation
Download GitHub for [Mac](https://mac.github.com/), [Windows](https://windows.github.com/), etc.
To clone the ND4J files, enter this command into your terminal (Mac) or Git Shell (Windows):

      git clone https://github.com/SkymindIO/nd4j

# 3. Maven

### What it is
Maven is an automated build tool for Java projects (among other [things](http://maven.apache.org/what-is-maven.html)), that basically knows where the latest version of the libraries (ND4J .jar files) are, and downloads them automatically into your computer, ready to reference.

### Why you need it
Maven will allow you to install both ND4J and Deeplearning4j projects with a single command. Moreover, it integrates with an Integrated Development Environment ([IDE](https://github.com/globalcaos/nd4j/blob/gh-pages/getstarted.md#4-ide-for-java)), which you will install later (see below). If you really know what you are doing, and still do not align with Maven's paradigm, you can alternatively bypass it visiting our [downloads](http://nd4j.org/downloads.html) page.

### Is it already installed?
To see if Maven is installed in your machine, enter the following into the command line:

		mvn --version

### Installation
Instructions to install Maven are [here](https://maven.apache.org/download.cgi). 

Download the compressed file containing Maven's latest stable version, following the instructions that pertain to your operating system; e.g. *"Unix-based Operating Systems (Linux, Solaris and Mac OS X)."* 

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


