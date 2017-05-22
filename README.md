
IKAnalyzer
==========

An open source word breaker with lucene supported.  See http://code.google.com/p/ik-analyzer/



### Change

update to support Lucene 6.5.1 API.

参考来源 http://blog.csdn.net/fanpei_moukoy/article/details/67637851

## Gradle

**Step 1.** Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

```groovy
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Copy
```

**Step 2.** Add the dependency

```groovy
	dependencies {
	        compile 'com.github.chuangxian:IKAnalyzer:6ab2884ce6T'
	}
```

## Maven

**Step 1.** Add the JitPack repository to your build file

```xml
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

**Step 2.** Add the dependency

```xml
	<dependency>
	    <groupId>com.github.chuangxian</groupId>
	    <artifactId>IKAnalyzer</artifactId>
	    <version>6ab2884ce6</version>
	</dependency>
```

