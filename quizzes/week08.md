# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```

It holds various metadata relevant to the project and is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```

At the level you need it installed, the root.

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```

 npm run build

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
env

```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```

You can view logs with the Heroku CLI, the dashboard, your logging add-on, or in your log drain.

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
You dont. You reset the repo and redeploy it.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```

Branching helps software development teams work in parallel. It separates out “in-progress work” from tested and stable code.

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```

Code reviews occur after all automation checks and before the working branch merges with the main branch (source code).

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```

Merge

```