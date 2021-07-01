Exception in thread "main" java.lang.RuntimeException: Could not load wrapper properties from 'C:\Users\admin\AndroidStudioProjects\flutter_app\android\gradle\wrapper\gradle-wrapper.properties'.
	at org.gradle.wrapper.WrapperExecutor.<init>(WrapperExecutor.java:64)
	at org.gradle.wrapper.WrapperExecutor.forWrapperPropertiesFile(WrapperExecutor.java:47)
	at org.gradle.wrapper.GradleWrapperMain.main(GradleWrapperMain.java:60)
Caused by: java.net.URISyntaxException: Illegal character in path at index 62: https://services.gradle.org/distributions/gradle-x.x.x-all.zip to gradle-5.6.2-all.zip 
	at java.net.URI$Parser.fail(URI.java:2848)
	at java.net.URI$Parser.checkChars(URI.java:3021)
	at java.net.URI$Parser.parseHierarchical(URI.java:3105)
	at java.net.URI$Parser.parse(URI.java:3053)
	at java.net.URI.<init>(URI.java:588)
	at org.gradle.wrapper.WrapperExecutor.readDistroUrl(WrapperExecutor.java:81)
	at org.gradle.wrapper.WrapperExecutor.prepareDistributionUri(WrapperExecutor.java:70)
	at org.gradle.wrapper.WrapperExecutor.<init>(WrapperExecutor.java:57)
	... 2 more
Exception: Gradle task assembleDebug failed with exit code 1
   
