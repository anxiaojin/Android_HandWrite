# 
手写签名

## How to ##

To get a Git project into your build:

### Step 1. Add the JitPack repository to your build file ###

Add it in your root build.gradle at the end of repositories:

    allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

### Step 2. Add the dependency ###

    dependencies {
	        implementation 'com.github.nangongyibin:Android_HandWrite:1.0.1'
	}
	

## 效果图：##

![](https://github.com/nangongyibin/Android_HandWrite/blob/master/1.gif?raw=true)