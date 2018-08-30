# Set Enviroments

## Change user to `root`

```shell
>sudo su - root 
```

## Edit the `/etc/Profile` file

```shell
>vi /etc/profile
```

then change the `profile` as you want to

some changes eg.
``` shell

#jdk home by HQF
JAVA_HOME=/home/tools/jdk1.8.0_77
PATH=$JAVA_HOME/bin:$PATH
CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar
export JAVA_HOME
#export PATH
export CLASSPATH


#maven by hqf
M2_HOME=/home/tools/apache-maven-3.3.9
PATH=$PATH:$M2_HOME/bin

export M2_HOME
export PATH

```


## Make all Available

```shell
>source /etc/profile
```


## More
