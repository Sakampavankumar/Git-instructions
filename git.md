# Using Git and GitHub

## Pre-requisites
* A GitHub Acoount . If you don't have one make it [here](https://github.com/join)
* Git . Install Git [here](https://git-scm.com/)
![git download](git.PNG)
* Run the setup file,click **next**
 
![git file](1st.PNG)

* Check 2nd checkbox as shown and click **next**

![checkbox](2nd.PNG)

* Check with **_use the native window secure channel library_** and click **next**

![windowcheckbox](3rd.PNG)

* Check with **_use MinTTY_** and click **next**

![checkboxlast](4th.PNG)

* Check first two checkbox and click **next**

![checkboxx](5th.PNG)

* Installation process start

![Installation](6th.PNG)
 
## Create new repository on Github

1. Open your Github account . You will see a page somewhat like this .
![new repository](newrepo.PNG)
2. Click on **Start Project** Button to create a new project repository.
3. Alternatively you can also click on the **new repository** as shown in the bottom corner of the image .
4. Once you have clicked you'll be directed to this page.
![new repo1](newrepo1.PNG)
5. Enter the repository name you want . Remembere there are some conventions to naming the repositories .
When you enter the name wait for a while until the green tick comes as shown in the image .
6. Then you can Click on the green **create Repository** button .
7. Then you will be redirected to the next page.
![newrepo3](newrepo3.PNG)
8. You have **succesfully** created a new repository on github .
9. Now we will see how we can **_push_** our data in the repository

## Using Git

1. Once you have installed Git on your system we can push our projects through it.
2. Open Git Bash and you will something like this.
 ![git bash](git1.PNG)
3. The First two commands you need to run are just to get youself registered on Git.
```   
 git config --global.user "santk97"
    
 git config --global user.email "****@gmail.com"
```
![git2](git2.PNG)    
*  **Make sure the username and email you enter are  github registered**(_not necessary but makes work easy_)

4. Now you need to direct your git to the destined folder .For that we use the ```cd "path"```  command .
   In the double quotes you need to enter the full path of your project .
   ![git path](git3.PNG)
   
5  Now that we have reached ou project folder the first thing  we need to do is  initialise out git in the project .
``` 
git init 
```   
Use this  command. It will make a .git folder in your project .
![gitinit](git4.PNG)
![gitnew](git5.PNG)

6 . Now that we have created the git folder . We will now add the files to be pushed , It can be done in two ways:
* Selectively
```python
git add filename
```
* All Files
```python
git add .
```
7 . We will use the    _**git add .**_ command
![git add . ](git6.PNG)
8 . Once we have added , the next thing we need to do is commit these changes .
```python

git commit -m "your commit message"

```
**Remember:**_The commit message should be a meaningful one ._
![git commit](git7.PNG)


9. Next we will connect our GitHub repo with this project using the link given to us on the github page .
 ![github link](git8.PNG)
 **Copy the blue highlighted part** 
 
10 . Next we will use the URI Link to connect our project to github .

11. For that we will use 
```python
git remote add origin ** paste here**

```

![git remote add](git9.PNG)
 
12 . The last step is to to **_push_** the changes to the repository.
  ```python

git push origin master

```
![git ](git10.PNG)


13 . If everything you have done is correct and followed the guide correctly your github repository should have been updated.
![gitrepo](git11.PNG)
_something like this_
 
14.  In some cases when you push you might have to sign up . 
 **Remember** : _when pushing your network should be working_
 
15. For the next times you just need to remember these commands _in this order_
 ```python
git add . 
git commit -m "your message"
git push origin master 

```
 
16. Some other useful commands are :
 ```python

git log #tells the log of your commits 
```
![gitlog](gitlog.PNG)

```python

git status # used to know the status of the files being tracked or not

```
![git status](gitstatus.PNG)

17 . Thank you . 
