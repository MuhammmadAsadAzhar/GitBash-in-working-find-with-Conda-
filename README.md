# GitBash-in-working-find-with-Conda-
GitBash in working find with Conda 

Table of Contents

- [Introduction](#introduction)
- [Step 1: Install GitBash](#step-1-install-gitbash)
- [Step 2: Install Miniconda](#step-2-install-miniconda)
- [Step 3: Set up Conda in GitBash](#step-3-set-up-conda-in-gitbash)
- [Step 4: Test Conda in GitBash](#step-4-test-conda-in-gitbash)
- [Step 5: If it is not working at all](#step-5-if-it-is-not-working-at-all)

## Introduction

This is  a lightweight terminal that is easy to use and has a lot of features that make it easy to work with. However, some people have reported that they are having trouble getting GitBash to work with Conda. In this guide, we will show you how to get GitBash working with Conda so that you can use it for the course.



> ## Step 1: Install GitBash

The first step is to install GitBash on your computer. You can download it from the official website [here](https://git-scm.com/downloads). Once you have downloaded the installer, run it and follow the instructions to install GitBash on your computer.

> ## Step 2: Install Miniconda

The next step is to install Miniconda on your computer. You can download it from the official website [here](https://docs.conda.io/en/latest/miniconda.html). Once you have downloaded the installer, run it and follow the instructions to install Miniconda on your computer.

> ## Step 3: Set up Conda in GitBash

Once you have installed GitBash and Miniconda, you need to set up Conda in GitBash. To do this, open GitBash and run the following command:

```bash
conda init bash
```

This will set up Conda in GitBash so that you can use it to manage your Python environments.

> ## Step 4: Test Conda in GitBash

To test that Conda is working in GitBash, run the following command:

```bash
conda list
```

This will show you a list of all the packages that are installed in your current Conda environment. If you see a list of packages, then Conda is working correctly in GitBash.

> ## Step 5: If it is not working at all

If you are still having trouble getting GitBash to work with Conda, you can try running the following command in GitBash:

```bash
source ~/.bashrc
```
If you have this error: `bash: $'\377\376.': command not found`

Then you have to go to similar path similar to this accordin to your user name `C:\Users\Asad\miniconda3\etc\profile.d` in your miniconda installed folder copy the path and then run the following commands in the gitbash.
> Note: Remember to use your own path.

```bash
cd C:/Users/Asad/miniconda3/etc/profile.d
echo ". ${PWD}/conda.sh" >> ~/.bashrc
```

> If your path has spaces in it, you will need to use quotes around the path like this:
```bash
echo ". '${PWD}'/conda.sh" >> ~/.bashrc
```

After running the above command, close GitBash and reopen it. Conda should now be working correctly in GitBash.

Reopen the GitBash and run the following command to test that Conda is working correctly:

```bash
conda list
```

If you see a list of packages, then Conda is working correctly in GitBash.

## Conclusion

In this guide, i have shown you how to get GitBash working with Conda so that you can use it for the course. By following these steps, you should be able to use GitBash to manage your Python environments and work with Conda without any issues.

If you have any questions or run into any problems, please let us know and we will be happy to help you out, using issues of this github repository.
