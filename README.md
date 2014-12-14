The GitHub Matrix
====================

<blockquote>The latest commits from GitHub visualized in a Matrix-style animation.</blockquote>

<img src="http://winterbe.com/image/matrix-has-you.gif">

The GitHub [Matrix](http://en.wikipedia.org/wiki/The_Matrix) shows a constant stream of latest commits from GitHub. Click on the drops to open the corresponding Revision on GitHub in a new tab. Use the pause/play button at the lower right corner to pause and resume the matrix animation (or press SPACE).

<img src="http://winterbe.com/image/matrix.png">

### Build your own

The tool is a [Spring Boot](http://projects.spring.io/spring-boot/) webapp written in Java 8. You need JDK 8 + Maven 3 preinstalled in order to run the app by yourself. [Fork](https://github.com/winterbe/github-matrix/fork) and clone the repository to your local machine, then `cd` into the project directory and run the following command:

```bash
mvn package
java -jar target/*.jar -XX:MaxMetaspaceSize=64m -Xmx256m -Djava.awt.headless=true
```

### Compatibility

The frontend is written in JavaScript and HTML5 (Canvas). It's heavily is tested and optimized for current desktop browser versions (Chrome, Firefox, Safari) and mobile iOS Safari. If you find any issues related to Internet Explorer or other browsers, please let me know.

### Contribute

Feel free to [fork](https://github.com/winterbe/github-matrix/fork) this project and send me pull requests. You can also send me feedback via [Twitter](https://twitter.com/benontherun) or by [opening an issue](https://github.com/winterbe/github-matrix/issues).

### License

The source code is published under the MIT license. If you reuse parts of the code for your own projects please preserve information about me as original author visible in your application.
