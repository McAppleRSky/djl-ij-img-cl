Install IJava kernel for jupyter
  ~~git clone https://github.com/frankfliu/IJava.git
  cd IJava/
  gradlew installKernel~~

python3 install.py --sys-prefix
jupyter kernelspec install java
jupyter kernelspec list
  Available kernels:
    python3    D:\Program Files\Python312\share\jupyter\kernels\python3
    java       C:\ProgramData\jupyter\kernels\java

kernel.json
```
{
    "argv": [
        "D:/tools/java/jdk-11.0.23+9/bin/java",
        "-jar",
        "D:/tools/ijava/ijava-1.3.0/java/ijava-1.3.0.jar",
        "{connection_file}"
    ],
    "display_name": "Java",
    "language": "java",
    "interrupt_mode": "message",
    "env": {
        
    }
}
```

JDK 11
java --list-modules
  jdk.jshell@12.0.1
pip3 install jupyter

jupyter notebook
