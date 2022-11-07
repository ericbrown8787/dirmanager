# Directory Manager With Typescript

This is a simple CLI for managing directories.

## Usage

To install globally from the app directory:

```npm install -g```


After installation, the app can be run using:

```dirmanager [option] <value>```


To display a list of valid options

```dirmanager``` OR ```dirmanager -h```

![image](https://user-images.githubusercontent.com/90017825/200213275-10a3406e-e8cd-47d2-84a8-7ac3d5a03ed3.png)


To display the current app version:

```dirmanager -V``` OR ```dirmanager --version```

![image](https://user-images.githubusercontent.com/90017825/200213345-f88a6a65-18cb-4add-af26-a9041b2a1b19.png)


To list directory contents: 

```dirmanager -l <path>``` OR ```dirmanager --ls <path>```

![image](https://user-images.githubusercontent.com/90017825/200213569-0b088beb-46bf-4215-a492-c8d1c0cecb48.png)


To create a directory:

```dirmanager -m <filename>``` OR ```dirmanager -mkdir <filename>```

![image](https://user-images.githubusercontent.com/90017825/200213656-12db3046-4dd6-449e-a094-da2f3cec4586.png)


To create an empty file:

```dirmanager -t <value>``` OR ```dirmanager -touch <value>```

![image](https://user-images.githubusercontent.com/90017825/200213698-2cecf849-c58a-42fe-8b64-57318b8d6485.png)


## Sources

[Building a TypeScript CLI with Node.js and Commander, by Stanley Ulili](https://blog.logrocket.com/building-typescript-cli-node-js-commander/)

**NOTE:** The .gitignore file has been modified so that the dist folder is pushed.
