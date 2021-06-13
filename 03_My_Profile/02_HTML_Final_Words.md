**01_Comments**

Comments are developers best friends 💙. They help identify steps and explain things in the code, so when anyone reads our code or we read it in the future we can remember what we did easily. 
In HTML comments are written as following: 
```html
<!-- ... -->
```
Comments are not visible to the user in the websites, that is why it's nice to have them without affecting the site's look. You will never believe that this page: 

![img](https://lh4.googleusercontent.com/BGpSkOF08v3bFSQ8Ci0uJpdV2Li3t9ezqFmx3Tl7WeBBSZFd_ifwK975IK1O3cGvLmB_37xBvUhsNTpeLgT7Ked2Weqc3ECmhBgSRGuRbFu9nOT7iMJ9V0qmtxGGO7aDXv_5a3ds)

Has this in its code: 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- This is the title -->
    <title>My Profile</title>
</head>
<body>
    <!-- My Name -->
    <h2>My Name is Bob</h2>
    <!-- Image imported locally -->
    <img src="images/bob.png" alt="Bob image" height="130px">
    <!-- Simple paragraph -->
    <p>I am a web development student</p>
    <h4>My hobbies</h4>
    <!-- Unordered list -->
    <ul>
        <li>Sleeping</li>
        <li>Eating</li>
        <li>Cooking</li>
    </ul>
    <!-- Public link -->
    <a href="https://github.com/">Check my GitHub</a>
    <!-- New Line -->
    <br>
    <!-- Image imported from the web -->
    <img src="https://banner2.cleanpng.com/20180824/jtl/kisspng-computer-icons-logo-portable-network-graphics-clip-icons-for-free-iconza-circle-social-5b7fe46b0bac53.1999041115351082030478.jpg"
        alt="GitHub icon" height="40px">
</body>
</html>
```

**02_Buttons**

Now since we know how to add links, a word by itself sometimes is not clear that is clickable. That is way we are using a new tag which is the `<button>` , and it can be used like this: 
```html 
    <button>Check my GitHub</button>
```
Buttons which will look like this on a website: 

![img](https://lh5.googleusercontent.com/djpR3Fw3hQws-oX6tZ2Qbv2TDHy7-hReyHWXPbi8C6BN0RRxN9Ij-HP_AiDuWWg6aJLM2faSb-ca4pXpiPAhkbjqI8lrb_4LKqS3rwd1tRFB9CKU9Z42eirlY5L-yI1IskIgxdJw)

**📝 Note:** 

> Notice that the button is unclickable, to make it clickable we need to see the next section which is `Nested Tags`to make the buttons and the image clickable.

**03_Nested_Tags**

Finally guys we reached the last thing we need to know with `HTML` before going to another part of Web development!!!! 
So we are here to learn what are nested tags? 🤔
You might be surprised if I told you that you used them without feeling it 👀
Nested is a term we give it when a thing is being bounded by another thing, lets see a huge example: 

![image-20210613183930110](C:\Users\Malba\AppData\Roaming\Typora\typora-user-images\image-20210613183930110.png)

In the image above, all the elements inside the body are considered in the `<body>` nest and these elements will be called a nested element. 
Some other example will be: 

1. `<html>` has elements inside it
2. `<ol>` and `<ul>` always contains `<li>`in them
3. `<head>` will be caring the `<title>` and future things 😉

**Using Nested tags with Buttons:** 

Now it is the time to make our button clickable 🔥
As we know that the `<a>` tag is clickable so if we changed this code:

```html 
    <a href="https://github.com/">Check my GitHub</a>
    <button>Check my GitHub</button>
```
In a way that we let the closing tag of the link `</a>` be after the closing tag of the button `</button>` while removing the text between the `<a>` tag to look like this: 
```html 
       <a href="https://github.com/">
        <button>Check my GitHub</button>
    </a>
```

![img](https://lh3.googleusercontent.com/DkrmGeKDQw4TnCFI811yhGusH4cLXK8NYJ-ZcVrySG0mS8C2VnD2fjtvLSaA8wgMMvxzSfbUbmIp_mD1wxEFuCWAjZ8qHMSpzrd18KrgjCUwi2Y4pS9MG1bFyFCpvYhBO_rBxVkP)

Looks better and clickable 😎

**Using Nested tags with Images:**

We will do what we did with the `<button>` with the github `<img>` to get this code: 
```html 
  <a href="https://github.com/">
        <img src="https://banner2.cleanpng.com/20180824/jtl/kisspng-computer-icons-logo-portable-network-graphics-clip-icons-for-free-iconza-circle-social-5b7fe46b0bac53.1999041115351082030478.jpg"
            alt="GitHub icon" height="40px">
    </a>
```
Now even our image is clickable 🔥

**Source Code:** 

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <!-- This is the title -->
    <title>My Profile</title>
</head>

<body>
    <!-- My Name -->
    <h2>My Name is Bob</h2>
    <!-- Image imported locally -->
    <img src="images/bob.png" alt="Bob image" height="130px">
    <!-- Simple paragraph -->
    <p>I am a web development student</p>
    <h4>My hobbies</h4>
    <!-- Unordered list -->
    <ul>
        <li>Sleeping</li>
        <li>Eating</li>
        <li>Cooking</li>
    </ul>
    <!-- Public link -->
    <a href="https://github.com/">
        <button>Check my GitHub</button>
    </a>
    <!-- New Line -->
    <br>
    <!-- Image imported from the web -->
    <a href="https://github.com/">
        <img src="https://banner2.cleanpng.com/20180824/jtl/kisspng-computer-icons-logo-portable-network-graphics-clip-icons-for-free-iconza-circle-social-5b7fe46b0bac53.1999041115351082030478.jpg"
            alt="GitHub icon" height="40px">
    </a>
</body>

</html>
```

**Result Website:** 

![img](https://lh5.googleusercontent.com/BrnwLanONkW8kcLaVE_ndJHLaW0ZlqhunLxafCRs3svYkby_66RYqx_J9eI66zFZRAdoFri7BZPilvycnKzihT3JWEiqj4ZKOG2Az7BBpPP34cLdNfLabqS2-7TsA1ILV-_opuoT)

